# Installation

To install DocInsight, download the latest version from the [Releases](../../releases/README.md), run the installer, and follow the instructions to complete the installation process.

## System Requirements

- Windows 10/11 (x86-64/arm64)
- Delphi XE7 or higher

## Installation Mode

![](../../releases/v6.0/images/install-mode.png)

### For current user

By default, DocInsight is installed in the following directory:
`%LocalAppData%\Programs\DevJet\DocInsight\6.0`.

### For all users (Requires Admin privileges)

If you install DocInsight for all users, the default installation directory is:
`%ProgramFiles(x86)%\DevJet\DocInsight\6.0`.

## Setup Command Line Parameters

You can use the `/silent` or `/verysilent` option to install DocInsight silently. For more information, please see the [Setup Command Line Parameters](https://jrsoftware.org/ishelp/topic_setupcmdline.htm) in the [Inno Setup](https://jrsoftware.org/isinfo.php) documentation.

## Alternative Root Registry

If you use the `bds.exe -r` command line switch to start Delphi with an alternative root registry, you may need to manually add the DocInsight extension to the registry.

### Example

Take Delphi 12 for instance, if you launch Delphi with `bds.exe -rTest`, add the following registry key:

`HKEY_CURRENT_USER\Software\Embarcadero\Test\23.0\Experts`
- Key: `DocInsight` (String Value)
- Value: `%LocalAppData%\Programs\DevJet\DocInsight\6.0\DocInsight290.dll`

### Extensions

| DocInsight DLL          | Delphi Version          | BDS Version |
|-------------------------|-------------------------|-------------|
| `DocInsight210.dll`     | Delphi XE7              | 21.0        |
| `DocInsight220.dll`     | Delphi XE8              | 22.0        |
| `DocInsight230.dll`     | Delphi 10 Seattle       | 23.0        |
| `DocInsight240.dll`     | Delphi 10.1 Berlin      | 24.0        |
| `DocInsight250.dll`     | Delphi 10.2 Tokyo       | 25.0        |
| `DocInsight260.dll`     | Delphi 10.3 Rio         | 26.0        |
| `DocInsight270.dll`     | Delphi 10.4 Sydney      | 27.0        |
| `DocInsight280.dll`     | Delphi 11 Alexandria    | 28.0        |
| `DocInsight290.dll`     | Delphi 12 Athens        | 29.0        |