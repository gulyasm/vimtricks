# Vim Magic

 - `gg=G` Indent all rows
 - `==` Indent current row
 - `zz` Current line to center
 - `zt` Current line to top
 - `zb` Current line to bottom
 - `ZZ` Save and quit
 - `ciw` Change word
 - `ci"` Change everything inside double quotes (Works with other characters)
 - `gd` Go to definition
 - `gg` Go to start of the document
 - `G` Go to end of the document
 - `J` Join lines
 - `gJ` Join lines without inserting space
 - `%` Jump to corresponding item ((),{},[])
 - `.` Repeat previous command
 - `*` Search for next occurance under cursor
 - `#` Search for previous occurance under cursor
 - `%` Move cursor to the first character of line
 - `$` Move cursor to the last character of line
 - `gi` Go insert mode where you were last insert mode
 - `D` Delete the rest of the line
 - `dd` Delete line
 - `zo` Open fold
 - `zc` Close fold
 - `zz` Move cursor to center of screen
 - `zt` Move cursor to top of screen
 - `zb` Move cursor to bottom of screen
 - `:jumps` Jump list
 - <number>`Ctrl-o` - Jump to <number> backwards element in jump list
 - <number>`Ctrl-i` - Jump to <number> forwards element in jump list
 - `{` Move to start of previous paragraph or code block.
 - `}` Move to end of next paragraph or code block.
 - `Ctrl+F` Move forward one screenful.
 - `Ctrl+B` Move backward one screenful.
 - `~` Toggle case under cursor
 - `o` Edit in a new line below the current
 - `O` Edit in a new line above the current
 - `:r`[name] Insert the file [name] below the cursor.
 - `~`  Switch case of the character under the cursor and move the cursor to the right. If a [count] is given, do that many characters. 
 - `D` Delete until end of line
 - `dG` Delete until end of file
 - `R` Go to overwriting mode (edit mode but doesn't insert text but overwrites)

## Search:
 - / search
 - ? search

 - `gi` insert mode where insert mode was exited last time
 - `gJ` lines without space
 - `ga` ASCII code of the character under cursor
 - `gf` editing the file under the cursor
 - `[I` Show lines with matching word under cursor
 - `:grep Vim *.md` and after `:copen` to open grep result in quickfix

## Moving until search term
 - `y/search<Enter>`
 - `y?search<Enter>`
 - `d/search<Enter>`
 - `d?search<Enter>`
 - `c/search<Enter>`
 - `c?search<Enter>`

## Other
 - `!sort` sort visually selected lines

## .vimrc
 - `inoremap jj <Esc>`
