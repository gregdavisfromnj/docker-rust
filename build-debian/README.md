This directory is intended to be a template directory that holds
files that will be copied into the individual build directories for
each platform that the `x.py` script creates on the `update` command.
The dockerfile templates read by the `x.py` script may reference these
files in ADD/COPY commands, for example, and may even rewrite the
files if they are also templates with placeholder macros in need of
replacement.
