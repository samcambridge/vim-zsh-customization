# Purpose

Customize your dev-box env with your own dotfiles and packages.

Here, dotfiles are taken from an external github repo.

This installation sets up bundled `vim` and `zsh`

Zsh gets charged with `powerlevel10k`.

After you ssh to your dev-box, type `zsh` and enjoy. 

You can also add the last two lines to your `.ssh/config`:
```
Host my-dev-box
    HostName 1.2.3.4
    RequestTTY yes
    RemoteCommand zsh
```
