This cheat-sheet is for my configuration of Emacs.  [See below](#configuration)

#### Files

* `⌃C p f` Open file in project [ⓘ](https://github.com/bbatsov/projectile)
* `⌃X f` Open file
* `⌃C p s` Switch to another known project [ⓘ](https://github.com/bbatsov/projectile)

#### Windows/Buffers

* `⇧←↑↓→` Navigate windows [ⓘ](http://www.emacswiki.org/emacs/WindMove)
* `⌃X 0` Close current window [ⓘ]((http://www.gnu.org/software/emacs/manual/html_node/emacs/Change-Window.html#Change-Window)
* `⌃X k` Close current buffer
* `⌃X 2 / ⌃X 3` Vertical/horizontal split [ⓘ](http://www.gnu.org/software/emacs/manual/html_node/emacs/Split-Window.html#Split-Window)

#### Navigation

* `⌃S` Search
* `⌥G g` Go to line

#### Editing

* `⌥X replace-string` search and replace

#### REPL

* `⌃C ⌃K` eval current buffer [ⓘ](https://github.com/clojure-emacs/nrepl.el)
* `⌃C ⌥O` clear REPL buffer [ⓘ](https://github.com/clojure-emacs/nrepl.el)



⇧: Shift
⌃: Control
⌥: Alt/Option
⌘: Command

### Configuration

...built off of [Emacs Live](https://github.com/overtone/emacs-live) which has the following plugins:

* Emacs 24
* clojure-mode
* [nREPL.el](https://github.com/clojure-emacs/nrepl.el)
* paredit [cheat sheet](http://www.emacswiki.org/emacs/PareditCheatsheet)
* [SLIME](http://common-lisp.net/project/slime/)

and the following additional plugins

* [windmove](http://www.emacswiki.org/emacs/WindMove)
* [projectile](https://github.com/bbatsov/projectile)
