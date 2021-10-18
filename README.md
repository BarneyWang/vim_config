# vim_config
### vim theme
+ theme:gruvbox
  - https://github.com/morhetz/gruvbox
  - git clone https://github.com/morhetz/gruvbox.git ~/.vim/pack/default/start/gruvbox
+ plugin
  - nerdfont
    - nerdfonts.com
  - nerdtree
    - https://github.com/preservim/nerdtree
    - git clone https://github.com/preservim/nerdtree.git ~/.vim/pack/vendor/start/nerdtree
    - vim -u NONE -c "helptags ~/.vim/pack/vendor/start/nerdtree/doc" -c q
  - airline
    - git clone https://github.com/vim-airline/vim-airline  ~/.vim/pack/dist/start/vim-airline
    - :helptags ~/.vim/pack/dist/start/vim-airline/doc
  - airline-theme
    - git clone https://github.com/vim-airline/vim-airline-themes ~/.vim/pack/dist/start/vim-airline-themes
  - tagbat
    - install ctags first
      - linux : sudo apt install universal-ctags
      - mac  : sudo brew install universal-ctags
    - git clone https://github.com/preservim/tagbar  ~/.vim/pack/dist/start/ 
  - ultisnips
    - git clone https://github.com/SirVer/ultisnips.git ~/.vim/plugins/start/
    - snippets list : https://github.com/fatih/vim-go/blob/master/gosnippets/UltiSnips/go.snippets
