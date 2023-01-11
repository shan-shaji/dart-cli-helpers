# Dart CLI Packages

The repo contains a collection of packages that will assist you in developing CLI applications in Dart. Please feel free to update this list as there may be packages that I am unaware of.


## [very_good_cli](very_good_cli)

Generate a Dart CLI with Very Good CLI. If you are making a CLI package for the first time this is the needed tool for you.
They also have pretty good [documentation](very_good_cli_documentation) about using this template.


## [mason_logger](mason_logger)

The package is more than just a logger and allows you to accept user inputs and will help you to build lot of other cool things. 

Some feature are:

- Show progress to user.
- Allows users to select from different options.
- Prompts to accept user inputs.

## [args](args)
This library lets you define parsers for parsing raw command-line arguments into a set of options and values using GNU and POSIX style options.

note: If you are using [very_good_cli](very_good_cli) then by default this package will be included in the boilerplate.

## [pub_updater](pub_updater)
A Dart package which enables checking whether packages are up to date and supports updating them.
Intended for use in CLIs for prompting users to auto-update.


## [pubspec_parse](pubspec_parse)
Simple package for parsing pubspec.yaml files with a type-safe API and rich error reporting.
You may not be able to find the documentation in their README. I am adding a snippet
that will helpe you to use this package.

```dart

final rawString = await rootBundle.loadString("pubspec.yaml");
final pubspec = Pubspec.parse(rawString);

```

## [dart_console](dart_console)

This library contains a variety of useful functions for console application development, including:

- Reading the current window dimensions (height, width)
- Reading and setting the cursor location
- Setting foreground and background colors
- Manipulating the console into "raw mode", which allows more advanced keyboard input processing than the default dart:io library.
- Reading keys and control sequences from the keyboard
- Writing aligned text to the screen
- Tabular data display, including month calendar

The [example](dart_console_example) folder of this pacakge contains all the necessary implementations to understand the pacakge.

## [cli_completion](cli_completion)

Dart package that aims to enable Dart CLI applications to receive shell completions with minimal setup. This package helps you to enhance the user experiance of your CLI tools.

It works on bash and zsh on Linux, macOS, and Windows.

[very_good_cli]: https://pub.dev/packages/very_good_cli
[very_good_cli_documentation]: https://verygood.ventures/blog/generate-command-line-application-cli
[mason_logger]:https://pub.dev/packages/mason_logger
[args]: https://pub.dev/packages/args
[pub_updater]: https://pub.dev/packages/pub_updater
[pubspec_parse]: https://pub.dev/packages/pubspec_parse
[dart_console]: https://pub.dev/packages/dart_console
[dart_console_example]: https://github.com/timsneath/dart_console/tree/main/example
[cli_completion]: https://pub.dev/packages/cli_completion