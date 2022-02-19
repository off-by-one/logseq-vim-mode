# logseq-vim-mode
A better set of vim keybindings in logseq

## Vim -> Logseq Translation Rules

Where possible, vim commands are copied directly (e.g. zc to close a fold). If the command needs to exist during editing mode, add a ctrl+command options (e.g. ctrl+z ctrl+c). If the command has ctrl in vim, keep that in logseq.

For commands that don't have a direct vim equivalent or where conflicts exist, use something similar (e.g. ctrl+shift+; for the command pallette, reminiscent of vim ":"). These are labeled with VIMISH in a comment.

## Quirks

Some commands are personal preferences. They are labeled with PERSONAL, sometimes with an explanation of why I like it. I keep them here because they may be resolving conflicts that I didn't notice.

Some command functions overlap without breaking the function. Some commands conflict when a block is selected but not when nothing is selected. Logseq's pseudo-modal system is too complicated for me to document them, but I will occasionally push fixes when they bother me too much.
