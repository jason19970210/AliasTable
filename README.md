# AliasTable
A table which shows the `alias` from shell run command file (rc) 

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
$ alias.sh [ -l | -h | -v | -i ]

    -l, --list              Full information of alias
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