# hyspell
 Armenian language spellchecker for Hunspell platform and Vim editor.

## installation
1. Download `hy_AM.dic` and `hy_AM.aff` files.
1. Place them in dictionary folder of hunspell/myspell package, on Gentoo Linux it is located in `/usr/share/hunspell`.
1. Place `hy.utf-8.spl` file under Vim spellchecker folder in `/usr/share/vim/{version}/spell` or in `~/.vim/spell`. To enable spell-checker from command mode type `:set spell spelllang=hy`.
