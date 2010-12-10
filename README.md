# vim-symfony-snipmate #

## overview ##

vim-symfony-snipmate introduces some snippets for symfony when using [snipmate.vim](https://github.com/msanders/snipmate.vim).

To activate snippets in a vim file, use following in your vim command line:

  :set ft=php.symfony

to activate xml propel snippets, just do 

  :set ft=xml.propelxml

To always activate a snippets set for given filetype, just use the following in your .vimrc

  autocmd FileType php set ft=php.symfony

if you want to always enable snippets in a given file, just add following line at the end:

  <!--
  vim:ft=xml.propelxml
  -->

or, in a php file

  // vim:ft=php.symfony

## deploy snippets ##

You can find a shell script packaged with the plugin, just execute it from anywhere to 
copy snippets included with this repo to your ~/.vim directory

  $ ./vim-snippets-update

