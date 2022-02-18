# logseq-vim-mode
A better set of vim keybindings in logseq

## Vim -> Logseq Translation Rules

Where possible, vim commands are copied directly (e.g. zc to close a fold). If the command needs to exist during editing mode, add a ctrl+command options (e.g. ctrl+z ctrl+c). If the command has ctrl in vim, keep that in logseq.

For commands that don't have a direct vim equivalent or where conflicts exist, use something similar (e.g. ctrl+shift+; for the command pallette, reminiscent of vim ":"). These are labeled with LIKE in a comment.

## Quirks

Some commands are personal preferences. They are labeled with P, with an explanation of why I like it.

The commands "g h" and "h" interfere if you go to your homepage while a block is selected, so I've added "g shift+`" as a way to go home.

