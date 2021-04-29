Brace matching:
`%`

Fold function:
1. go to start of function, type `mb`
2. type `%`
3. type `zf'b`
with line number:
`:5, 16fo` fold line 5 to 16
open fold:
`zo`
close fold:
`zc`
toggle between open and close:
`za`

Yank or paste without line number:
1. `mk`
2.  `y'k` or `d'k`

Tabs:
open tabs:
`:tabedit filename`

navigate tabs:
`gt` or `gT` or `{i}gt` i is the idx of tabs

`:tabfirst`
`:tablast`
`:tabn`
`:tabp`

list all open tabs:
`:tabs`

close a single tab:
`:tabclose`

close all other except current one:
`:tabonly`

Scenario restore:
store: `:mksession scenario.vim`
restore: `:source scenario.vim` or `$ vim -S scenario.vim`
save scenario back: `:mks!`

Indents:
indent i: `>i` `<i`

auto complete:
`ctl+n` under insert mode

move to end of line:
`shift+a`

Bookmark:
make a bookmark: `m{lowercase}`
go to bookmark: `\`{lowercase}

window split:
`:split filename`
`:vsplit filename`

Reference:
[Vim basic features](https://www.freecodecamp.org/news/learn-linux-vim-basic-features-19134461ab85/)
