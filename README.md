# Vim and zsh customization

This is a repository to show how to customize your dev-box environment with your own dotfiles and packages.

In this example the dotfiles are taken from an external github repo. If you want to put your `.` files directly, use `home` directory.

Zsh gets charged with powerlevel10k here.

After you ssh to your dev-box, type `zsh` or in your .ssh/config add:
```
Host dev-box
    HostName 1.2.3.4
    RequestTTY yes
    RemoteCommand zsh
```
