# Announcing DocInsight 2024 (Draft)

[DocInsight](https://devjetsoftware.com/products/documentation-insight/), also known as _Documentation Insight_, is an API documentation tool for Delphi developers.

The first release of _DocInsight 2024_ represents a major update, introducing support for **Delphi 12** and a completely redesigned **DocInsight CLI**. This version addresses many long-standing issues from previous versions and provides valuable enhancements.

## Delphi 12

### IDE Insight

## DocInsight CLI

- Progress
- Parallel jobs
- Ctrl+C handler
- Error-handing

![DocInsight CLI](images/docinsight-cli.gif)

### `build` command

![docinsight-build](images/docinsight-build.png)

## Documentation

### Browsing local HTML output

You no longer need to use a web server to browse the HTML output.

![](images/local-html.png)

### CHM font on HighDPI

The font was too small on HighDPI displays. It has been fixed now.

![](images/chm-highdpi.png)

### Package list

![alt text](images/package-list.png)

### Preserve enum order

Enumeration members are now sorted in declaration order, rather than by alphabetical order.

### Misc. changes

- Change the term "Namespace" to "Unit"
- Strip method parameters from topic title
- Improve word wrapping of topic title

## Editor

### Insert image with relative path

![](images/img-relative-path.png)

### Navigate to active file in DocExplorer

### Responsive with large files

## Check Documentation

### Show source location while checking

![](images/check-doc.png)

## Format Documentation

### Convert `<img>` tag to relative path

### Force text wrap after `<br/>` tag

![](images/wrap-after-br.png)

### Bug fixes

- Missing space in adjacent inline tags
- Offset-by-one bug in text wrapping
- Unexpected wrap on punctuation
- Unexpected wrap in inline tags, e.g., `<see>`

## Installer

- Install mode (all users/current user)

## Notable Fixes

- AV when opening a new empty project
- AV when the IDE is started with the `-r` switch
- DocInsight.exe raises an Out of Memory error
- Failed to locate `transform.data`

## Known Issues

The following features are not included in this release. Please provide us with feedback if you require these features.

- _HelpAndManual_ output
- MSHELP2 output
- External XML documentation support
- Surround XML doc comment with a customizable region
