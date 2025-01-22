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

My own theme (tomghuang.omp.json) is based on Powershell-nord-theme:
https://github.com/AntonRyadovoy/Powershell-nord-theme

## Clink

Clink is installed under:
C:\Opt\clink

Clink configuration is under:
C:\Users\tomgh\clink_settings
C:\Users\tomgh\clink_aliases

To add the aliases into Clink, we have to use the following command in the Windows Terminal setting:
%SystemRoot%\System32\cmd.exe /s /k "C:\\Opt\\clink\\clink_x64.exe inject --profile C:\\Users\\tomgh && doskey.exe /macrofile=C:\\Users\\tomgh\\clink_aliases"

As you can see, the key is calling the doskey command and set the alias file with the /macrofile command-line option.

For more information:
https://chrisant996.github.io/clink/clink.html

## Git

Git configuration is under:
C:\Users\tomgh\.git-commit-template
C:\Users\tomgh\.gitconfig

