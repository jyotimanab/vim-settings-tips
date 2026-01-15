vim-settings-tips

#Modifiy .vimrc to add space/ tab/ vertial lines in files open with vim with.sh file extention
```
vim ~/.vimrc

" YAML specific configuration with custom characters
autocmd FileType sh setlocal tabstop=2
autocmd FileType sh setlocal shiftwidth=2
autocmd FileType sh setlocal softtabstop=2
autocmd FileType sh setlocal expandtab

" Custom list characters for YAML
autocmd FileType sh setlocal listchars=tab:│\ ,trail:·,extends:»,precedes:«,nbsp:×
autocmd FileType sh setlocal list

```
#add commect character befire multiple lines

```
- press ctrl + v [for visual block]
- Select lines
- press shift + I [this will move the cursor to the beginning of the first line]
- Type # and press esc key
- This will add # symbol infront of all selected lines.

```
