# lifecycle-tester

[![npm version](https://badge.fury.io/js/lifecycle-tester.png)](https://badge.fury.io/js/lifecycle-tester)

npm package with benign preinstall and postinstall scripts. Use it to securely test whether your npm, Bun or Deno installations are configured to ignore these scripts (as they should be).

If the scripts are run, they will exit with a non-zero exit code and display an error message.

## Usage

Install this package as any other, i.e. `npm install lifecycle-tester` or `bun add lifecycle-tester`

