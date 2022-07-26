# incorporate-constrains
Incorporate mopro-style CONSTRAIN file into shelx-style res file,
by Daniel Tchoń (dtchon@chem.uw.edu.pl). MIT license.

Use this tool from command line with python3.5+, eg.:
    python3 ./incorporate_constrains.py

Provide the res_path and con_path as subsequent positional arguments:
    python3 ./incorporate_constrains.py path_to.res CONSTRAIN.txt

If any of the files is missing, the working directory is scanned in order to
find the files with matching names (one "\*.res" and one "CONSTRAIN.\*").
Please mind that the incorporated labels must match between files.

For further details, run
    python3 ./incorporate_constrains.py --help

