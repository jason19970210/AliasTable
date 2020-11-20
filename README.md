AliasTable [![MIT License](https://img.shields.io/apm/l/atomic-design-ui.svg?)](https://github.com/tterb/atomic-design-ui/blob/master/LICENSEs)
[![Active](http://img.shields.io/badge/Status-Active-green.svg)](https://tterb.github.io)
[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://GitHub.com/Naereen/StrapDown.js/graphs/commit-activity)
[![Version](https://img.shields.io/badge/version-1.0-green.svg)](https://shields.io/)
===

Show alias in an effective way.

## Installation
```zsh
$ git clone https://github.com/jason19970210/AliasTable.git ~/.zsh/AliasTable
```

### Setting Environment Variable
```zsh
$ nano ~/.zshrc
```

Put following line into `.zshrc`
```zsh
export PATH=$HOME/.zsh/AliasTable:$PATH
```

## Usage
```
$ alias.sh -h

Show alias in an effective way.
Usage: alias.sh [ -l | -h | -v | -i ]

   -l, --list 11             Full information of alias
   -h, --help              Show this help
   -v, --version           Show script version
   -i, --info              Show script information

```

## Uninstallation
1. Remove source code
    ```
    $ rm -rf ~/.zsh/AliasTable
    ```
2. Remove environment variable in `.zshrc`
    ```sh
    ## Remove following line 

    export PATH=$HOME/.zsh/AliasTable:$PATH
    ```
