# CLion MARTe2 Experience

C-Lion version 2022 installed on Ubuntu 20.04 using the (partial) Makefile project support notes
as of 2022-06-01.

- MARTe2 has no top-level Makefile, so create a symlink to Makefile.x86-linux to allow CLion to figure out the build.
- In the preferences, reduce the default jobs=6 which attempts a parallel build to jobs=1 (nominal fault)
- To run a test....
