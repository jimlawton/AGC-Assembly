# AGC Assembly
[Sublime Text](http://www.sublimetext.com) syntax-highlighting for [Apollo Guidance Computer (AGC)][1] assembly [source code][2].

This syntax supports the following filetypes:
 - `agc` - AGC (Command Module and Lunar Module) assembly language source.
 - `ags` - AGS (Lunar Module Abort Guidance System) aseembly language source.
 - `binsource` - AGC/AGC core rope memory binary source files.

## Installation

### [Package Control][3]

 - Command Palette (OS X: `Cmd-Shift-P`, Linux/Windows: `Ctrl-Shift-P`)
 - Select `Package Control: Install Package`.
 - Select `AGC Assembly`

Package Control will automatically keep `AGC Assembly` up to date.

### Manual Installation

Locate the Sublime Text [packages directory][4] on your machine and use Git to
clone the repostory from Github into that directory:
```
$ cd </sublime/packages/directory>
$ git clone https://github.com/jimlawton/sublime-agc.git 
```

## Contributing

Pull requests are welcome. Please do *not* edit the `.tmLanguage` files
directly. Instead, edit the `.YAML-tmLanguage` files and build the
`.tmLanguage` file from it using
[AAAPackageDev](https://github.com/SublimeText/AAAPackageDev).


[1]:http://www.ibiblio.org/apollo/
[2]:https://github.com/rburkey2005/virtualagc
[3]:https://packagecontrol.io/
[4]:http://docs.sublimetext.info/en/latest/basic_concepts.html#the-packages-directory
