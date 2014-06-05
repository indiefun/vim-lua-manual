# This is a Lua 5.2 Reference Manual document for vim

## Usage:

This vim help doc is a copy of official [Lua 5.2 Reference Manual](http://www.lua.org/manual/5.2/contents.html#index)

All help keywords have the same prefix `lua.`, so you can use like following example:

	// open vim help doc of lua 5.2 reference manual
	:help lua.manual
	
	// open vim help doc of table chapter in lua manual
	:help lua.table
	
	// open vim help doc of function `insert` in table
	:help lua.table.insert
	
## Installation
#### manual
Just
[download](https://github.com/whoisusingmyname/vim-lua-manual/archive/master.zip) the
archive, unzip it and then put `doc` directory into your `~/.vim/`
#### Vundle
Just put following line in your `.vimrc`, also see
[Vundle](https://github.com/gmarik/Vundle.vim)'s Quick Start

    Plugin 'whoisusingmyname/vim-lua-manual'
