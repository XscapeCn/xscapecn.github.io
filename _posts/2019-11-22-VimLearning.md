---
layout:     post
title:      Vim基础操作1.0
subtitle:   
date:       2019-11-22
author:     Song
header-img: img/post-bg-vim.jpg
catalog: true
tags:
    - iOS
---

# VIM

## Two modes

- **Insert mode**, in which you write text as if in normal text editor.

- **Normal mode**, provides efficient ways to navigate and manipulate text.

`ESC`: normal mode 

`i`: insert mode 

check the status in the **status bar**.

## Basic movements

**H J K L : **

## Word movements

**`W`**: start of the next word

**`E`**: end of the word

**`B`**: beginning of the word

## Number powered movements

> combine movement keys with a number

**`3W`**: pressing `w`  three times

## Insert text repeatedly

Ex: to print "Hello Hello Hello"

**`3`**

**`i`**

**`Hello`**

**`ESC`**

## Find a character, f and F

> to find and move to the next (or previous) occurrence of a character, use `f` and `F`

`f` + `o` : find next o 

combine `f` with a number :

`3` + `f` + `q`

## Go to matching parentheses, %

**`%`**： jump to the next matching parentheses **( [ {**

## Go to start/end of line, 0 and $

`0`: reach the beginning of a line

`$`: end of a line

## Find word under cursor, \* and #

`*`: find the next occurrence of the word under cursor

`#`: the previous

## Go to line, g and G

`gg`: takes you to the beginning of the **file**

`G`: to the end of the **file**

`line number` + `G`: jump directly to a specific line. (`2G`)

## Search, /text with n and N

`/` + `text`： search text

`n` `N`： search for  next and previous occurrence

## Insert new line, o and O 

`o` or `O`:  insert new line ,once insert, editor is set to **insert** model

then, `ESC` get back to **normal** model

## Removing a character, x and X

`x` or `X`: delete the character under the cursor, then to the left of the cursor.

## Replacing letter under cursor, r

`r`: replace only one character, without changing in **insert** mode 

## Deleting, d

`d`: is the delete command

`d` `w`: deletes the first word on the right side of the  cursor

## Repetition with .

`.`: repeat the previous command

## Visual mode, v

## Replacing letter under cursor, r

`u`: for undo

`ctrl` + `R`: for redo

`:` + `help`: H E L P !



