# trash-cli

> Move files and folders to the trash

WIP

## Install

1. git clone
2. if not exist `$HOME/.Trash` directory, make directory.
3. set alias to `bash_profile` or `bashrc`

    ```bash
    alias trash='/PATH/trash-cli/trash'
    ```
    
## Usage

```bash
$ trash --help
```

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
## Tip

Add `alias rm=trash` to your `.zshrc`/`.bashrc` to reduce typing & safely trash files: `$ rm unicorn.png`.

## License

MIT © [Yeongjun Kim](https://wickso.me)
