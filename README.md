# ⌨️ Common VIM Usage
This repository is a list of the most commonly used VIM motions and commands that I use in my day to day coding. There are other resources that cover this a lot better. This one serves more as a memory jogger for when my hands fail to remember the pattern.

## Quick Reference
- `ct'` - Cut to the `'` then enter insert mode
- `yt'` - Yank to the `'` and remain in normal mode
- `:%y` - yank all contents of file to the register
- `dat` - Delete around tags. Deletes contents of an html tag including the tag that the cursor is on
- `dit` - Delete the contents of a tags that that the cursor is on
- `%y+` - Yank to he clipboard instead of the vim register
- `dw` - Delete word
- `dvb` - Delete word going backwards

## Commands
- `:h rtp` - view neovim's folder location
- `:Ex` - file explorer

## Substitutions
- `:%s/;.*/helloworld` - Substitute the `;` and everything after it `.*` with `helloworld`.
- `:%s/replacethis\(.*\)/replacethis\1\r"Month":\1/g` - Example for substitution using **capture groups**

## File Navigation
- `cd directory` - Changes directory to specified
- `:Ex` - enter explore mode
  - `%` - to enter a new file
  - `d` - to make a new directory

## Commenting a block of code
- Position cursor to the first line you wish to comment, 
- `SHIFT - V` to enter visual block mode
- `j` of `k` to select the lines
- `SHIFT - i` to enter insert mode
- type your comment, eg. `//`
- `ESC` to complete the comment

## Sessions
- :mksession! ~/today.ses - Saves a new session
- vim -S ~/today.ses - Loads the saved session

# Contributing
Pull requests are welcome!
