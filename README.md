## Configuration
___


Clone repository:


```
    cd /local/projects
    git clone https://github.com/p7cq/vim.git
    ln -s /local/projects/vim/.vim/vimrc ~/.vim/vimrc
```

Create a directory layout for Vim:

```
    mkdir -p ~/.vim/{autoload,bundle}
```

- Download and install Tim Pope's [Pathogen](https://github.com/tpope/vim-pathogen.git)

```
    cd ~/.vim/autoload
    wget https://raw.githubusercontent.com/tpope/vim-pathogen/master/autoload/pathogen.vim -
```
Add [yapf](https://github.com/google/yapf)

```
    cd ../bundle
    git clone https://github.com/google/yapf
    cp yapf/plugins/vim/autoload/yapf.vim ../autoload
    cp -r yapf/plugins/vim/plugin ..
```

Add [tabular](https://github.com/godlygeek/tabular.git)

```
    git clone https://github.com/godlygeek/tabular.git
```

Add [Markdown](https://github.com/plasticboy/vim-markdown)

```
    git clone https://github.com/plasticboy/vim-markdown
```

Add [limelight](https://github.com/junegunn/limelight.vim)

```
    git clone https://github.com/junegunn/limelight.vim
```

Add [goyo](git clone https://github.com/junegunn/goyo.vim)

```
    git clone https://github.com/junegunn/goyo.vim
```

Dark theme: [Solarized 8](https://github.com/lifepillar/vim-solarized8)

```
    git clone https://github.com/lifepillar/vim-solarized8
```

Light theme: [Solarized](https://github.com/altercation/vim-colors-solarized):

```
    git clone git://github.com/altercation/vim-colors-solarized.git
```
