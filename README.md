<!-- Badges: -->
[![VIM](https://img.shields.io/badge/VIM-8.2.2121-informational)]()
[![Contributions](https://img.shields.io/badge/contributions-welcome-orange?style=flat-square)](https://github.com/camponogaraviera/vim-editor/pulls)

<!-- Title: -->
<div align="center">
  <h1> 
    <a href="https://en.wikipedia.org/wiki/Vim_(text_editor)">
     VIM Editor Shortcuts
    </a>
  </h1>
</div>

# Table of Contents

- [Opening Vim](#opening-vim)
- [Editing Mode](#editing-mode)
- [Navigation Commands](#navigation-commands)
- [Selection Mode](#selection-mode)
- [Editing Commands](#editing-commands)
- [Saving and Exiting](#saving-and-exiting)
  
## Opening Vim  

To open Vim, type the following command in the Linux terminal:  
```sh
vim
```

## Editing Mode 

- Press `i` to enter **editing mode**.
- Press `ESC` to exit editing mode.

## Navigation Commands 

- `gg` → Move to the **beginning of the file**.  
- `Shift + g` → Move to the **end of the file**.  
- `0` → Move to the **beginning of the line**.  
- `Shift + $` → Move to the **end of the line**.  
- `:number` → Jump to a **specific line number**.  

## Selection Mode  

- Press `v` to enter **selection mode**.  
- `ggVG` → Select **everything** in the file.  

## Editing Commands  

- `u` → Undo changes.
- `ctrl+r` → Redo changes.
- `dd` → Delete the **entire current line**.  
- `>` or `<` → **Indent** or **unindent** selected code.  

## Saving and Exiting  

Save and exit:

```sh
:wq
```

Exit without saving:

```sh
:q!
```
