# load-bash-shell-aliases

[![License: GPL v3](https://img.shields.io/badge/License-GPL%20v3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)

Convert bash aliases into eshell ones.

# Installation

1. Download and copy **load-bash-shell-aliases.el** into
   **.emacs.d/lisp** directory.
2. Add the following elisp code to your Emacs config:

``` elisp
;; Tell Emacs where is your personal elisp lib directory
(add-to-list 'load-path "~/.emacs.d/lisp/")

;; load-bash-shell-aliases
;; https://github.com/daviderestivo/load-bash-shell-aliases
(load-library "load-bash-shell-aliases")
```

3. Call lbsa/load-bash-alias-into-eshell interactive function to
   convert bash aliases into eshell ones.
