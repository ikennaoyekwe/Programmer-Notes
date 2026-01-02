## Pacman Install

> if `pacman -S somePackage` didn't work
>
> do : `pacman -S somePackage --overwrite '*'`
>
> ### to see all your installed packages use :
>
> __pacman -Qe__

## xh

> better alternative for `curl` , installed with `winget install ducaale.xh`

## bat

> better than `cat`

## lsd

> better than `ls`

## ag

> use for searching text in files ( fast )
>
> ```
> ag "arash"
> ```

## fd

> better solution to find that 'ls' and 'find' or 'grep'
>
> ```
> fd "someFile"
> // by extension
> fd -e js
> ```
>

## dust

> to see file and folder sizes
>
> ```
> dust -t ( sort by file type )
> dust -d 1 ( for depth )
> dust -n 5 ( show the 5 number of most heavy files )
> ```

## tree

> use to see the tree structure of your folder .
>
> ```
> tree -L 2  ( show only 2 level depth )
> tree -L 2 -I 'node_modules|.git|dist'   ( -I exclude folder )
> tree -L 2 -h  ( shows file size too )
> ```

## jq

> use for parsing json files
>
> ```
> jq . package.json
> ```

## hx

> helix editor ( commands like Vim )

## micro

> micro editor , use CTRL + Q to exit, ctrl + S ( to save ) and etc ( just like windows )

## fzf

> fuzzy finder , use to sort your search by files better
>
> ```
> example :
> ag "arash" | fzf
> ```
>
> - K , J ( to move Up & Down )
> - Enter ( to return result )
