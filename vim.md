# VIM beginner's cheat sheet

Vim (Vi improved) is an extremely powerful editor. This cheatsheet covers only
what you need to edit a few git commit messages.

## Command mode (ESC)

	
    i              go to insert mode
    v              go to visual mode
    (cursor keys)  navigate
    :wq            save and quitreset

    :q             quit, if no unsaved changes
    :q!            quit anyway
    y              yank (=copy)
    c              cut
    p              paste
    u              undo
    Ctrl+R         redo

## Insert mode (i)

    ESC            back to command mode
    (usual editing functionality)

## Visual mode (v)

    ESC            back to command mode
    (cursor keys)  modify selection
    y              yank (=copy) selection
    c              cut selection
    p              paste selection
