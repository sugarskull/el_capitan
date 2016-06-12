# Emacs Installation Guide


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
