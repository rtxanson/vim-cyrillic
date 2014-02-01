
Vim Cyrillic -> Finnish Extended for Macbook keyboards
======================================================

Forked originally from `x1024`, but modified for this specific use case.

This file contains normal mode mappings that allow easier vim editing
on a phonetic cyrillic keyboard without using langmap/keymap.

Every cyrillic character is mapped to its corresponding latin character.
Every Ctrl-command with a cyrillic character is mapped to its corresponding latin Ctrl-character command.

What works:
-----------

Single-character verbs (including ones that take arguments) like "d$", "O", "A" all work.


What doesn't work:
------------------

Multi-character commands like "dd", "d10d", etc.



To use, just source vim_cyrillic.vim. Seriously, it's that simple.

