# winTrace releases

Downloads for **winTrace**, a Windows performance recorder and timeline analyzer by davideAurum. This repository
holds release files only; the source code is not published here.

Releases appear under [Releases](https://github.com/davideAurum/winTrace-releases/releases), with:

- `winTrace-<version>-setup.exe`: an installer for your account; it offers to install the .NET 10 Desktop Runtime
  if it is missing.
- `winTrace-<version>-win-x64-self-contained.zip`: a portable copy that needs nothing else installed.
- `winTrace-<version>-win-x64-framework-dependent.zip`: a smaller portable copy that needs the .NET 10 Desktop Runtime.
- `SHA256SUMS.txt`: checksums to verify the downloads.

Each download carries its license in `LICENSE.txt`. The builds are not code-signed yet, so Windows SmartScreen may warn
the first time you run one.
