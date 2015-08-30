An obsolete distribution point for Win64 binaries for the Vim editor.

This project is no longer maintained. Please refer to the Vim Tips Wiki's Where to Download Vim for up-to-date suggestions on obtaining a Win64 build.

Vim 7.3
Vim 7.3 was released on 2010/8/15. Win64Binaries are available here.

The official Win32 installer from vim.org is recommended over the Win64 binaries supplied here:

Full GUI installer
Installs a Win32 or Win64 gvimext.dll Shell Extension appropriate to the target machine. This provides Edit with Vim functionality in Explorer using the 32-bit (g)vim.exe.
"Big" version of GVim that includes language interfaces for Python 2.7, Python 3.1, Ruby 1.9, Tcl 8.3, and Perl 5.12;
CScope and NetBeans integration, and Global Input Method Editors for Chinese, Japanese, and Korean.
Fully supported
The Win64 binaries have:

Command-line installer
"Huge" version of GVim with a language interface for Python 2.7. (Most other languages that Vim has an interface for are not available as Win64 binaries.)
Not supported; not well tested.
There are still a few reasons why one might want a native 64-bit version of Vim (per Craig Barkhouse):

Editing files >4GB in size; rare I know, but still.
64-bit WinPE does not have a WOW64 subsystem, hence you cannot run a 32-bit executable.
Windows Server 2008 R2 (i.e. Win7 Server) also does not have the WOW64 subsystem, by default, although it is an optional component you can install.
Potential for perf gains, particularly in heavy memory operations like memcpy and memcmp which can be optimized for the 64-bit word size.
