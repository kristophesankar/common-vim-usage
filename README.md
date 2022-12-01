# Common VIM Usage
This repository is a list of the most commonly used VIM motions and commands that I use in my day to day coding. There are other resources that cover this a lot better. This one serves more as a memory jogger for when my hands fail to remember the pattern.

## Quick Reference
- `ct'` - Cut to the `'` then enter insert mode
- `yt'` - Yank to the `'` and remain in normal mode
- `dat` - Delete around tags. Deletes contents of an html tag including the tag that the cursor is on
- `dit` - Delete the contents of a tags that that the cursor is on
- `%y+` - Yank to he clipboard instead of the vim register

## Substitutions

`:%s/;.*/helloworld`- Substitute the `;` and everything after it `.*` with `helloworld`.
