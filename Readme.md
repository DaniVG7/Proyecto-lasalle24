Git for Windows v2.44.0 Release Notes
Latest update: February 23rd 2024

Introduction
These release notes describe issues specific to the Git for Windows release. The release notes covering the history of the core git commands can be found in the Git project.

See http://git-scm.com/ for further details about Git including ports to other operating systems. Git for Windows is hosted at https://gitforwindows.org/.

▷
Known issues
Should you encounter other problems, please first search the bug tracker (also look at the closed issues) and the mailing list, chances are that the problem was reported already. Also make sure that you use an up to date Git for Windows version (or a current snapshot build). If it has not been reported, please follow our bug reporting guidelines and report the bug.

▷
Licenses
▽
Changes in v2.44.0
since v2.43.0 (November 20th 2023)
Git for Windows for Windows v2.44 is the last version to support for Windows 7 and for Windows 8, see MSYS2's corresponding deprecation announcement (Git for Windows relies on MSYS2 for components such as Bash and Perl).

Please also note that the 32-bit variant of Git for Windows is deprecated; Its last official release is planned for 2025.

New Features
Comes with Git v2.44.0.
Comes with libfido2 v1.14.0.
Comes with the MSYS2 runtime (Git for Windows flavor) based on Cygwin v3.4.10.
Comes with Perl v5.38.2.
Git for Windows learned to detect and use native Windows support for ANSI sequences, which allows using 24-bit colors in terminal windows.
Comes with Git LFS v3.4.1.
The repository viewer Tig that is included in Git for Windows can now be called also directly from PowerShell/CMD.
Comes with OpenSSH v9.6.P1.
Comes with Bash v5.2.26.
Comes with GNU TLS v3.8.3.
Comes with OpenSSL v3.2.1.
Comes with cURL v8.6.0.
Comes with GNU Privacy Guard v2.4.4.
