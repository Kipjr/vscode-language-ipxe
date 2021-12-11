# iPXE Language support

Support for the iPXE scripting language in Visual Studio Code.
## Syntax highlighting

Adds syntax highlighting support for iPXE (.ipxe). 

![Screenshot iPXE](./images/screenshot1.png?raw=true)

## Bugs

If you happen to notice bugs or have suggestions for improvements visit the [issue
section](https://github.com/Kipjr/vscode-language-ipxe/issues) of the
[repository](https://github.com/Kipjr/vscode-language-ipxe/).

## Themes

This extension provides TextMate scopes for use in syntax highlighting, but the colours displayed
depend on the theme being used.    
Unfortunately many themes have incomplete support for the different TextMate scopes, and as a
result different tokens can end up with identical colours.    

## Contributing

This project currently uses the `json-tmLanguage` format for language grammars.
The grammars can be found in the `syntaxes` directory. 
An example of an iPXE-files can be found [netboot.xyz-custom/custom.ipxe.example](https://github.com/netbootxyz/netboot.xyz-custom/blob/master/custom.ipxe.example)

