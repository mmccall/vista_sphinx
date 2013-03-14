This repository is for executing a sphinx-build for OSEHRA documentation.  It is independent of current documentation efforts, as this code will be run on a web server to render existing documentation in a more human friendly format.

To execute the build, after installing Sphinx, from the root directory execute the following:

sphinx-build -a -b html -c ./sphinx ./documentation ./_build

-a : Always rebuild all files (good for testing themes).
-b : Build format (html for web).
-c : location of sphinx configuration files.

Other operators are source and target directories.