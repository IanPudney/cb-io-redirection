cb-io-redirection
=================

Adds support in Code::Blocks for input/output stream redirection

This is a drop-in upgrade for Code::Blocks that adds support for the
"<" and ">" input/output redirection operators in program arguments.
 
===== Installation from Binary =====
To install from binary, simply navigate to your Code::Blocks install
directory and replace cb_console_runner.exe with the provided version.

===== Installation from Source =====
Simply open and compile the provided Code::Blocks project, then follow
the instructions above for installation from binary. You must have a
Code::Blocks compatible C++ compiler installed.

===== Limitations =====
Currently, this upgrade is limited to Windows systems.

===== Future Plans =====
 - Create a Code::Blocks plugin for this upgrade, which will allow
   installation via the built-in plugin menu.
 - Possibly add support for UNIX-based systems.