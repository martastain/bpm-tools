bpm-tools
=========
*Tempo (Beats Per Minute) analysis tools*

(C) Copyright 2013 Mark Hills <mark@xwax.org>

See the LICENSE file for licensing terms.

This software is distributed from the following site:

 - http://www.pogo.org.uk/~mark/bpm-tools/

The build is controlled via Makefile variables. In general
you should be able to build using:

```bash
  $ make
  $ make install
```

To change the target prefix, for example:

```bash
  $ make install PREFIX=/opt/bpm-tools
```

The Makefile picks up additional variables from a .config file
in the source directory. You will prefer to use this if you want
to control build flags for testing and debugging.
