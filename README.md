cb-io-redirection
=================

This is a drop-in upgrade for Code::Blocks that adds support for the
"<" and ">" input/output redirection operators in program arguments.
 
===== Installation from Binary =====
To install from binary, simply navigate to your Code::Blocks install
directory and replace cb_console_runner.exe with the provided version.

===== Installation from Source =====
To compile this tool, you must first have downloaded and be able to
compile the Code::Blocks source. Information regarding that can be
found on the Code::Blocks website.
Once you have that capability, follow these steps:
1. Replace the file main.cpp, located in src\tools\ConsoleRunner,
   with the one provided in this repository.
2. open the CodeBlocks.cbp project provided with the source 
   distribution.
3. Select the build target "ConsoleRunner" and build the project.
4. The executable file will be generated in the src\tools\ConsoleRunner
   directory. Copy this executable to your Code::Blocks install directory.
   If you built Code::Blocks from source, this is by default src\output
   (for the "release") version, and src\devel (for the "debug") version.

===== Limitations =====
Currently, this upgrade is limited to Windows systems.

===== Future Plans =====
 - Create a Code::Blocks plugin for this upgrade, which will allow
   installation via the built-in plugin menu.
 - Possibly add support for UNIX-based systems.