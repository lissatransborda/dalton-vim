# Dalton.vim

> Dalton.vim is a Vim port of Dalton Theme, check out [Dalton Website](https://lissaferreira.github.io/dalton-website/) to get more dalton theme ports.

Dalton is a minimalist theme for Vim, very based in [Ayu Vim theme](https://github.com/ayu-theme/ayu-vim), only with dark theme.

# Screenshots

## HTML

![HTML File with Dalton](assets/html.png)

## PHP

![PHP File with Dalton](assets/php.png)

## Javascript

![Javascript File with Dalton](assets/js.png)

## Golang

![Golang File with Dalton](assets/golang.png)

## Dalton for Vim-Airline

![Airline](assets/daltonairline.png)

# Install

Add the Dalton to your Vim plugins manager.

## Vundle

Add these lines to your Vim config file:

```vim
call vundle#begin()

Plugin 'lissaferreira/dalton-vim'

call vundle#end()

color dalton
```

## Vim Plug

```vim
call plug#begin()

Plug 'lissaferreira/dalton-vim'

call plug#end()

color dalton
```

## Vim Airline

To use dalton in Vim Airline, change/add this line to your vim conig file:

```
let g:airline_theme='dalton'
```
