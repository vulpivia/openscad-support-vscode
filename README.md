# OpenSCAD Language Support

marketplace: [[OpenSCAD Language Support](https://marketplace.visualstudio.com/items?itemName=Leathong.openscad-language-support)]

Visual Studio Code extension utilizing the [OpenSCAD language server](https://github.com/Leathong/openscad-LSP.git)， provide language support for OpenSCAD. The extension avalible on Mac, Linux and Windows. If you like this extension, please light up the stars in GitHub.

Project is available at: <https://github.com/Leathong/openscad-support-vscode>  
The language server is write in rust, project at <https://github.com/Leathong/openscad-LSP.git>

![screen record](media/screen_record.gif)

## Features

- formatter, you need install clang-format yourself
- jump to definition
- code auto-completion
- include auto-completion
- document symbols (*cmd + shift + o* on Mac)
- hover information
- simple error diagnosis
- preview and CheatSheet (from [vscode-openscad](https://github.com/Antyos/vscode-openscad))


## TODO
- symbol rename.

## Usage

The extension will read OPENSCADPATH Environment Variable to point to the library(s), you can also add paths to the setting `scad-lsp.searchPaths`.

For more information, see: [Using an external Editor with OpenSCAD](https://en.wikibooks.org/wiki/OpenSCAD_User_Manual/Using_an_external_Editor_with_OpenSCAD)


