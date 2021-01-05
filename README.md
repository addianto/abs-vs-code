# Abs support for Visual Studio Code

This repository adds support for the Abs language in Visual Studio
Code.  To install, issue the following
commands in a terminal: `cd ~/.vscode/extensions ; ln -s
/path/to/project/abs-vs-code abs`

It is also possible to bundle the extension to a VSIX package and install it
to Visual Studio Code. Run the following commands to create the package:

```bash
npm install
npm run package
```

## Features

Syntax highlighting only, for now.
