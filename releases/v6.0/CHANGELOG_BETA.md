# What's New in DocInsight Beta

## [Unreleased]

## [6.0.0.18] - 2024-11-15

- FIX: docinsight panicked with existing project group

## [6.0.0.17] - 2024-11-14 (YANKED)

### New

- Introducing Insiders edition
- Add the Microsoft HTML Help Workshop component to the installer
- Normalize text encoding of source files
- Clear shortcuts using the Backspace key in the Options
- Move docinsight.exe and DocInsightWizard.exe to bin folder
- Extend the trial period of the previous version

### Fixes

- Fix: DocInspector/DocExplorer editor may be empty in Delphi 12 (DPI Unaware)
- Fix: Go to Definition navigate to incorrect location when xmldoc changed
- Fix: Code editor may not scroll to the expected location when Go to Definition
- Fix: Whitespaces adjacent to inline tags are trimmed
- Fix: docinsight.exe panicked with ANSI encoded file
- Fix: docinsight.exe panicked when xml doc comment contains invalid UTF-8 sequenece
- Fix: docinsight.exe panicked with "Fail to convert uri to file path"

## [6.0.0.16] - 2024-10-30

- Fix broken CHM due to assets
- Fix project group topic failure
- Fix missing Result section
- Optimize DocInspector/DocExplorer to be more responsive
- Group symbols by kind in the TOC
- Sort members by name (except enumeration members)

## [6.0.0.15] - 2024-10-28

### General

- Change product version to **DocInsight 2025**
- Add End User License Agreement (EULA) in `license.md`
- Reorganize the extension dlls and legacy theme files
- Automatically uninstall previous DocInsight 2025 before new installation

### DocInsight CLI

- `docinsight license show|set|remove` Display and manage license information
- **BREAK** Change positional `manifest-path` to long argument: `docinsight build|check|open [--manifest-path <PATH>]`
- `docinsight build [--accept]` Accept trial license agreement
- Add log options for `build`/`check` command `--log-file <PATH> [--log-level <LEVEL>]`
- Support legacy V3.x command line syntax `docinsight.exe <filename> -doc [-silent]`
- Remove dependency on MSVCRT

### Extension

- Manage license in Extensions (_DocInsight_ menu > _License..._)
- Add Build (dry-run) in DocProjectWizard
- Change default documentation output directory when creating manifest (`build/docs/html`)

### Notable fixes

- Fix Delphi 12.x incompatibility issue
- Fix some formatter bugs
- Fix incorrect handling of XML comments within <Sources> element of _diproj_ file

## [6.0.0.10]

### Features

- Add Implements section
- Add “Implemented by” section for interface members
- Auto-inherited documentation
- Generate type hyperlinks
- Prompt the user to install CHM compiler in CLI
- Copy user images to output directory when building docs

### Fixes

- Doc editor cannot display images with relative path
- Failed to update documentation for single-line enum members
- Editor toolbar is missing in DocExplorer
- DocInsight Wizard Error: List index out of bounds (-1). ComboBoxStrings range is 0…258. C-bug

## [6.0.0.7]

### Fixes

- Fix: DocInspector don’t sync with active editor when docked
- Fix: Task error in DocInspector on cursor hover over local declarations
- Fix: Task error when document inactive source files in DocExplorer

### Improvements

- Group extensions and automatically select for installed Delphi IDEs
- Install only the selected extensions for Delphi
