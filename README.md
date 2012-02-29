A set of Haskell snippets to use with
[yasnippet](http://capitaomorte.github.com/yasnippet/).

## Installation

1. Clone the repo into e.g. `~/emacs.d/mysnippets/haskell-mode`.

2. Tell yasnippet about the snippets, by adding them to your `init.el`
   file.

        ;; Tell yasnippet where it can find the Haskell snippets
        (setq yas/root-directory "~/emacs.d/mysnippets/haskell-mode")
        
        ;; Load the snippets
        (yas/load-directory yas/root-directory)

## Usage

In a Haskell source file, with haskell-mode loaded, type e.g. `imp`
and press tab.
