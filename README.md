# [Feilong Wang](http://feilongwang.org)'s [Configuration Files](https://github.com/feil0n9wan9/confiles)
These are configuration files for bash, vim, git, etc to setup a new system fast and easily.


## Installation
**Warning**: If you want to give these profile files a try, you should review the code and backup some old of them since the installation script will override the old ones with same name. 

If you would like to see the old installation, check out [this branch](https://github.com/feil0n9wan9/confiles/tree/standby).

You'll also need to make sure your system has `git`, `curl` or `wget` installed.

### Installation script
To install or update fcfs, you can use the installation script using `curl`:
```bash
curl -o- https://raw.githubusercontent.com/feil0n9wan9/confiles/master/install.sh | bash
```
or `wget`
```bash
wget -qO- https://raw.githubusercontent.com/feil0n9wan9/confiles/master/install.sh | bash
```

### Add extra commands
If `~/.extra` exist, it will be sourced along with the other files. You can use it to add commands you don’t want to commit to a public repository, or to override settings, functions and aliases from the repository.


## License
The MIT License (MIT)


## Thanks
* [mathiasbynens](https://mathiasbynens.be) and his [dotfiles repository](https://github.com/mathiasbynens/dotfiles)
* [skwp](http://yanpritzker.com) and his [dotfiles repository](https://github.com/skwp/dotfiles)
* [ryanb](http://railscasts.com) and his [dotfiles repository](https://github.com/ryanb/dotfiles)
