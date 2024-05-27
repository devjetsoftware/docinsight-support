# Microsoft Help Compilers

## CHM (*hhc.exe*)

CHM files, or Compiled HTML Help files, are primarily used on Windows. To create CHM files, the HTML Help Workshop is required, which includes the hhc.exe compiler.

### Download and Installation

1. Download **HTML Help Workshop**

> [!IMPORTANT]
> The official download is no longer available on the [Microsoft HTML Help Downloads](https://learn.microsoft.com/en-us/previous-versions/windows/desktop/htmlhelp/microsoft-html-help-downloads) page. However, you can download the installer from this GitHub repository:
> https://github.com/EWSoftware/SHFB/raw/master/ThirdPartyTools/htmlhelp.exe

2. Verify the code signing

3. Run the installer (*htmlhelp.exe*)

> [!TIP]
> You can safely ignore the message "This computer already has a newer version of HTML Help" at the end of the installation.

## MSHELP2 (*hxcomp.exe*)

The lastest Microsoft Help 2.0 Compiler is included in Visual Studio 2018 SDK. If you want to install the SDK without Visual Studio, please

- Download [Visual Studio 2008 SDK Vesion 1.0](https://www.microsoft.com/en-us/download/details.aspx?id=508)
- Unzip the *VsSDK_sfx.exe* to *VsSDK_sfx* folder
- Run *vssdk.msi*

You should see *C:\Program Files (x86)\Common Files\Microsoft Shared\Help 2.0 Compiler*
