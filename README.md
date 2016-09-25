# AGC Assembly
[Sublime Text](http://www.sublimetext.com) syntax-highlighting for Apollo Guidance Computer assembly source code.

## Installation

### [Package Control][1]

Open the Command Palette (Shift-Cmd-P in OS X, Shift-Ctrl-P in Linux/Windows).
Select "Package Control: Install Package". Find and install `AGC Assembly`.

Package Control will automatically keep `AGC Assembly` up to date.

### Manual Installation

Locate the Sublime Text [packages folder][2] on your machine and use Git to
clone the repoisotry from Github:.

    $ cd </sublime/packages/folder>
    $ git clone https://github.com/jimlawton/sublime-agc.git AGC-Assembly

## Contributing

Pull requests welcome. Please do *not* edit the `.tmLanguage` files
directly. Instead, edit the `.YAML-tmLanguage` files and build the
`.tmLanguage` file from it using
[AAAPackageDev](https://github.com/SublimeText/AAAPackageDev).


[1]:https://packagecontrol.io/
[2]:http://docs.sublimetext.info/en/latest/basic_concepts.html#the-packages-directory
