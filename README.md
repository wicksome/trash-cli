# trash-cli

WIP

## Installation

1. git clone
2. if not exist `$HOME/.Trash` directory, make directory.
3. set alias to `bash_profile` or `bashrc`

    ```bash
    alias trash='/PATH/trash-cli/trash'
    alias rm='trash' 
    ```
    
## Usage

```bash
# remove files
$ trash [file ...]
# help
$ trash -h
# clear trash
$ trash -c
# force clear trash
$ trash -cf
# force clear trash with verbose option
$ trash -cfv
# list trash
$ trash -l
# list all trash
$ trash -al
# rm -rf
$ trash -rf [file ...]
```