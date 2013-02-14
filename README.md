vim-bufferclose
===============

Provides a vim command to close the current buffer and replace it with another existing buffer, or a new file if the buffer deleted was the last one listed.

Call the command with <code>:Kwbd</code>, or remap it to \<leader\>kb (mneumonic: <b>k</b>ill <b>b</b>uffer) with something like the following:

<code>:nnoremap \<leader\>kb! <Plug>Kwbd</code>

Calling the command with the ! argument will close the current buffer whether you've saved it or not.

<i>This script is originally from http://vim.wikia.com/wiki/VimTip165.</i>
