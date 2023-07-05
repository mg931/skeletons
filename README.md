# Vim Templates 

Base templates for new files in vim.

```vim
" vimrc

autocmd BufNewFile *.sh 0r ~/skeletons/bash.sh
autocmd BufNewFile *.py 0r ~/skeletons/template.py
autocmd BufNewFile readme.md 0r ~/skeletons/readme.md

" ... (other settings)
```
- __autocmd__ - Run automatically on some event
- __BufNewFile__ - New file event 
- __*sh__ - Pattern for new file to match
- __~/skeletons/bash.sh__ - File to read in 

