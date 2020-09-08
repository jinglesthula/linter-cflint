# linter-cflint :shirt:

## NOTICE: FORK BY DCE CO

The below info is from the original README.

Set Java Path to:

    C:\ColdFusion2018\jre\bin\java.exe

---

https://atom.io/packages/linter-cflint

This linter plugin for [Linter](https://github.com/AtomLinter/Linter) provides
an interface to [CFLint](https://github.com/cflint/CFLint). It will be used with files that have the "ColdFusion" syntax.

## Installation

```
apm install linter-cflint
```

`linter-cflint` requires Java >= 1.6, JRE or JDK, on your system and either the `JAVA_HOME` environmental variable to be set or for the user to specify the location of the Java executable in the configuration options.

## Configuration
* Similar to `.eslintrc`, you can use a `.cflintrc` file in your project or in a subfolder to exclude rules from the linter. See [the wiki page](https://github.com/ditinc/linter-cflint/wiki/Excluding-rules) for details.

## Roadmap
* Add additional rules to [CFLint](https://github.com/cflint/CFLint) (with an emphasis on indentation and formatting rules)
* Remove the dependency on Java?
* Better error handling / reporting.

## Contributing

If you would like to contribute enhancements or fixes, please do the following:

0. Fork the plugin repository
0. Hack on a separate topic branch created from the latest `master`
0. Commit and push the topic branch
0. Make a pull request

Please note that modifications should pass the `eslint` linter with the provided `.eslintrc`.

Thank you for helping out!
