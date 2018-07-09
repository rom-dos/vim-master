`.` - repeats the last *complete, combined* editing command (not movement commands)
`di>` - delete inner angle-block
`di(` / `di)` / `dib` - delete inner parenthesized block
`di[` / `di]` - delete inner bracketed block
`di{` / `di}` - delete inner braced block

"...although you will use hjkl to move around at first, once you master vi/vim you probably won't use 'h' and 'l' ('left' and 'right') at all, and you will use 'j' and 'k' sparingly. Why is that? Because there are other, more powerful motions, that will often get you where you want to go much faster. When moving inside a line, I find that there is always a motion to take me straight to where I want to go, so I use those motions: 'f' followed by any other character to find its next occurrence, '%' to use matching parens to go where you want to go, etc... When navigating the file, you have motions to go to the top/middle/bottom of the screen directly, '/' which is effortless to type to search for a string, ']]' and the likes to navigate by functions, etc." -- [Why, oh WHY, do those #?@! nutheads use vi?](http://www.viemu.com/a-why-vi-vim.html)

`H` - move cursor to the highest line on the screen
`M` - move cursor to the middle line on the screen
`L` - move cursor to the lowest line on the screen

`zt` - keep cursor at the current position but scroll the view so that it is at the top of the screen.
`zz` - keep cursor at the current position but scroll the view so that it is at the middle of the screen.
`zb` - keep cursor at the current position but scroll the view so that it is at the bottom of the screen.

`*` - search forward for the next occurrence of the current word under the cursor
`#` - search backwards for the last occurrence of the current word under the cursor

`>aB` - indent code block under cursor
`<aB` - reverse-indent code block under cursor

`dap` - delete a whole paragraph (i.e. *delete around paragraph*)

http://www.viemu.com/a_vi_vim_graphical_cheat_sheet_tutorial.html

http://thomer.com/vi/vi.html

# vim-galore bookmark: First Steps
