# my first rust project

[basic tutorial 📦](https://docs.microsoft.com/learn/paths/rust-first-steps/)

```
Rusty Journal 0.1.0
A command line to-do app written in Rust

USAGE:
    rusty-journal [OPTIONS] <SUBCOMMAND>

FLAGS:
    -h, --help       Prints help information
    -V, --version    Prints version information

OPTIONS:
    -j, --journal-file <journal-file>    Use a different journal file

SUBCOMMANDS:
    add     Write tasks to the journal file
    done    Remove an entry from the journal file by position
    help    Prints this message or the help of the given subcommand(s)
    list    List all tasks in the journal file
```

## .bashrc and .zshrc config

```
export PATH=$HOME/"git clone path"/rusty-journal/target/release:$PATH
alias todo="rusty-journal"
```
