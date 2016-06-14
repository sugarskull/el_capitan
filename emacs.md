# Emacs Installation Guide

## Setup

create directory: mkdir in ~/ mkdir .emacs.d
cd in .emacs.de
make init file: touch init.el
customize init file: nano init.el

## General Settings

Go to “Emacs” – “Preferences” – “Environment” – “Ns : GNUstep/Mac OS X specific features” 

    “Ns Command Modifier” -> “meta“ before super
    “Ns Alternate Modifier” -> “No modifier“ before meta


## Auctex

Homepage: https://www.gnu.org/software/auctex/

Install via Emacs:
```sh
M-x package-list-packages
```
Select auctex with i and confirm installation with x.

Hint:
Tex installation necessary.

## Markdown-Mode

Homepage: http://jblevins.org/projects/markdown-mode/

Install via Emacs:
```sh
M-x package-list-packages
```
Select markdown-mode with i and confirm installation with x.

Add to init.el:
```sh
(custom-set-variables
 '(markdown-command "/usr/local/bin/pandoc"))
```

Hint:
Pandoc is necessary.

Links:
http://stackoverflow.com/questions/14231043/emacs-markdown-mode-error-on-preview-bin-bash-markdown-command-not-found
