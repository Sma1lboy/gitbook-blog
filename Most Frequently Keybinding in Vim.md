---
Date: 2024-10-04
---
明白了，我会保留所有内容，只转换 Markdown 语法。以下是更新后的版本：

The purpose of this article is to provide students who already know how to use Vim basics, but want to operate without leaving the keyboard in more situations.
Here we will summarize the most common scenarios.

Common shortcuts:
```plain
$ means last char of current line
0 means first index of current line
^ means first non-white space index of current line
gg means head of file
G means end of file
<c-f> next page
<c-b> prev page
try H M L 
w to next word first char
b when at middle of char, go to first char, when at first char, go to prev word
```

Jumping between brackets:
```plain
[[ //prev block
]] //next block 
]) ]} ]>
[( [{ [< //jump to next or prev second char
```

Swapping two lines:
```plain
ddp
```
![](assets/Most%20Frequently%20Keybinding%20in%20Vim/Screen%20Recording%202024-10-04%20at%2021.09.20.mov)

Inserting repeated code:
```plain
(repeat numbers) -> a -> (content) -> esc
```
![](assets/Most%20Frequently%20Keybinding%20in%20Vim/Screen%20Recording%202024-10-04%20at%2021.14.04.mov)

Deleting content inside brackets (large, medium, small, ", '):
```plain
d/c -> i -> (/[/{/"/' also back bracket works as well
```
![](assets/Most%20Frequently%20Keybinding%20in%20Vim/Screen%20Recording%202024-10-04%20at%2021.19.41.mov)

Auto-align:
```plain
(selection) -> =
```
![](assets/Most%20Frequently%20Keybinding%20in%20Vim/Screen%20Recording%202024-10-04%20at%2021.28.22.mov)