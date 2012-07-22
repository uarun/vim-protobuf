# vim-protobuf

Vim syntax highlighting for Google's Protocol Buffers

## Introduction

This plugin exists for the sole purpose of making it easy to install syntax highlighting for protocol buffer 
as a pathogen bundle. If you are not already using Tim Pope's awesome [Pathogen plugin][vim pathogen] you 
should check it out.

The syntax highlighting code was shamelessly copied from [Google Protocol Buffers v2.4.1][proto syntax]

## Installation

Just like how you would install any other vim bundle using pathogen.

If you are not using pathogen (really you don't !), you can manually copy the files as follows:

    cd vim-protobuf
    cp syntax/proto.vim   ~/.vim/syntax/
    cp ftdetect/proto.vim ~/.vim/ftdetect/

[vim pathogen]: http://www.vim.org/scripts/script.php?script_id=2332
[proto syntax]: http://protobuf.googlecode.com/svn/tags/2.4.1/editors/proto.vim
