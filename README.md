Poca Scripts
============

This repository contains a collection of utility scripts that can
be accessed directly from a server and executed on a local machine
using [`poca`](https://github.com/gawhelan/poca.git).

To use these scripts you need to install `poca`:

    $ npm install -g poca

Then create (or edit) a `.poca` file in your home directory to
include one or more of the collections defined in this repo.
The `.soda` file is written in YAML format. For example:

    ---
    collections:
      - name: test
        url: https://github.com/gawhelan/poca-scripts/raw/master/test/

With the above collections defined in your `.soda` file you can
execute any of the scripts in the `test` collection. For example you
can execute the `python` test sxcript by running the following
command:

    $ poca test python

You will need to have a python interpreter aleady installed for the
script to be executed successfully.
