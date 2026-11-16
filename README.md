# CyberLab

CyberLab is a Windows desktop workspace for documenting authorized security research. It stores projects, findings, evidence, and reports on your computer. The interface supports Arabic and English.

## Download and run

1. Download `CyberLab-0.3.0-win64-portable.zip` from the [CyberLab 0.3.0 release page](https://github.com/OpenYsd/CyberLab/releases/tag/v0.3.0). Version 0.3.0 is the Stable release. The earlier release candidate, 0.3.0-rc.18, remains available as a pre-release.
2. In PowerShell, run `Get-FileHash -Algorithm SHA256 .\CyberLab-0.3.0-win64-portable.zip` from the download folder. Compare the result with the ZIP checksum on the release page.
3. Install **Microsoft Visual C++ Redistributable (x64), version 14.44 or later**, separately. Choose the X64 installer from [Microsoft's official download page](https://learn.microsoft.com/en-us/cpp/windows/latest-supported-vc-redist). CyberLab does not include it.
4. Extract the whole ZIP to a writable folder. Open `Start CyberLab.cmd` from the extracted CyberLab folder as a standard Windows user. At first launch, review and accept the licence terms, then choose a workspace.

## Licence and third-party software

The [CyberLab licence](LICENSE.txt) accompanies the download. The [component notices](NOTICE.txt), [third-party attributions](THIRD-PARTY-NOTICES.txt), and [licence texts](LICENSES/) cover the bundled components.

The corresponding source archives for the bundled LGPL libraries are attached to each release, with `SOURCES.txt` and `SHA256SUMS`. They are the official archives from Qt:

- [Qt Base 6.11.1](https://download.qt.io/official_releases/qt/6.11/6.11.1/submodules/qtbase-everywhere-src-6.11.1.tar.xz)
- [Qt for Python 6.11.1, including PySide6 and shiboken6](https://download.qt.io/official_releases/QtForPython/pyside6/PySide6-6.11.1-src/pyside-setup-everywhere-src-6.11.1.tar.xz)
