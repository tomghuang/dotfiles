# dotfiles
Configuration for core utilities

## Neovim/LazyVim

Neovim is installed under:
C:\Opt\nvim-win64

Neovim/LazyVim configuration is under:
C:\Users\tomgh\AppData\Local\nvim

## Oh My Posh

Oh My Posh is installed in:
C:\Opt\oh-my-posh

Oh My Posh configuration is in:
C:\Opt\oh-my-posh\themes

## Clink

Clink is installed under:
C:\Opt\clink

Clink configuration is under:
C:\Users\tomgh\clink_settings
C:\Users\tomgh\clink_aliases

To add the aliases into Clink, we have to use the following command in the Windows Terminal setting:
%SystemRoot%\System32\cmd.exe /s /k "C:\\Opt\\clink\\clink_x64.exe inject --profile C:\\Users\\tomgh && doskey.exe /macrofile=C:\\Users\\tomgh\\clink_aliases"

As you can see, the key is calling the doskey command and set the alias file with the /macrofile command-line option.

## Git

Git configuration is under:
C:\Users\tomgh\.git-commit-template
C:\Users\tomgh\.gitconfig

