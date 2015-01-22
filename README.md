# itamae-snippets

This is vim snippets for [Itamae](http://itamae.kitchen/) inspired by [serverspec-snippets](https://github.com/glidenote/serverspec-snippets).

## Requirement

 * [Shougo/neosnippet.vim](https://github.com/Shougo/neosnippet.vim)

## Install

### Vundle

1. Setup the [vundle](https://github.com/gmarik/vundle) package manager
2. Set the bundles for [itamae-snippets](https://github.com/tacahilo/itamae-snippets)

``` vim
Bundle 'tacahilo/itamae-snippets'
```

3. Open up Vim and start installation with `:BundleInstall`

### Neobundle

1. Setup the [neobundle](https://github.com/Shougo/neobundle.vim) package manager
2. Set the bundles for [itamae-snippets](https://github.com/tacahilo/itamae-snippets)

``` vim
NeoBundle 'tacahilo/itamae-snippets'
```

3. Open up Vim and start installation with `:NeoBundleInstall`

## Setup

Set itamae-snippets directory(`~/.vim/bundle/itamae-snippets`) in your .vimrc.


``` vim 
" setting example
let g:neosnippet#snippets_directory = [
      \'~/.vim/snippets',
      \'~/.vim/bundle/itamae-snippets',
      \]
```

### Usage

open Itamae files and set filetype `ruby.itamae`

``` vim
:set ft=ruby.itamae
```

## License

Lcense: Same terms as Vim itself (see [license](http://vimdoc.sourceforge.net/htmldoc/uganda.html#license))
