# DocInsight Command-line Tools

The DocInsight command-line tools (`docinsight.exe`) allow you to check and build the documentation for your projects. It is designed for use in a CI/CD pipeline or as part of a build script. The same executable also acts as a backend server to power the DocInsight Extension for Delphi IDE.

> [!TIP]
>
> You can use `DocInsight > Tools > DocInsight Command Line Prompt` in the IDE to run the command-line tools. This action adds the installation directory of `docinsight.exe` to your `%PATH%` and sets the working directory to your DocInsight project if available.

## Commands

- [`build`](./build.md)
  - **Description**: Build documentation.

- [`check`](./check.md)
  - **Description**: Check documentation for errors.

- [`open`](./open.md)
  - **Description**: Open a specific documentation output.

- [`license`](./license.md)
  - **Description**: Display and manage license information.

## Exit Code

DocInsight CLI returns `0` on success and a non-zero value on failure.
