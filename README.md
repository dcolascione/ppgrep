ppgrep
======

This short program is a convenience wrapper for invoking GNU grep, GNU
find, and GNU parallel together to recursively search one or more
directory trees.  For example:

  ppgrep foo # Defaults to searching $PWD
  ppgrep -i bAr dir1 dir2

Ppgrep also escapes all arguments and filenames passed between the
three programs.  This task is non-trivial.
