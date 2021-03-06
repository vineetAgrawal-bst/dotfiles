# Ayush Mandowara's Vim Config.

### How to setup:
1. Make sure you have at least version 8.2 December 2019 release of Vim or higher.
   - Chocolatey can be used: `choco install vim`
2. Clone this repo: `git clone https://github.com/ayushxx7/dotfiles`
3. Run `run.bat` file with `Admin Priveleges`. This will
   - Setup my vim config
   - Install Chocolatey Package Manager.
   - Install node, fzf, and ripgrep using Chocolatey
4. Open up Gvim or vim, and press enter on all the errors it will throw right now. 
5. Enter this command `:PlugInstall`.
6. Relaunch Gvim.

## Note: 
- You may need to run the `run.bat` file two times.
- I am looking for a fix.
- If anyone has suggestions, please let me know or raise a PR.

## Additional Software Installed
### Chocolatey
This package manager helps us install the other dependencies very easily.

### Node.js
CoC uses Node.js for the language servers required for autocompletion.

### FZF
- Fuzzy file search `ctrl`+`f` or `:Files`
- Fuzzy buffer search `<leader>b` or `:Buffers`

### RG
- Fuzzy line search `<leader>g` or `:Rg`
- Fuzzy line search inside parent Git directory `<leader>G` or `:GGrep`

### BAT
- Preview window with syntax highlighting
- Can be used in place of the `cat` command
