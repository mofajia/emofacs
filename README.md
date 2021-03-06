# Emofacs

Emofacs is my own Emacs configuration.

## Introduction

"Emofacs" == "E" + "mofa" + "cs", which is a combination of "Emacs", the name of the famous editor, and "mofa", the first part of my GitHub username. As a big fan of Emacs, I store my configuration in this repository both as a backup in case my local one is lost and for sharing. Anybody interested in my configuration may feel free to try it.

## Dependency

* [Emacs 27.2](https://www.gnu.org/software/emacs/)

This is my Emacs version, but Emofacs should also work in some older versions.

* [LLVM](https://llvm.org/)

This is only necessary when you want to code C/C++, because LLVM contains clangd, the language server recommended to use for C/C++ in LSP mode.

## Installation

For the convenience to configure an empty Emacs as simple as possible, most packages in my configuration are contained in the MELPA package manager, so the only file you really need is `init.el`.

Simply put `init.el` into `.emacs.d`, the standard location for additional per-user Emacs-specific files, Emacs is going to configure itself automatically during the next startup. Or if you want, you may git clone this whole repository as your `.emacs.d`. In this way, you may update this configuration using git in the future. For more information about `.emacs.d`, please visit https://www.emacswiki.org/emacs/DotEmacsDotD.

The installation time depends on your internet connection, because the packages need to be downloaded. It takes about 5 minutes on my personal computer at home. During installation, Emacs seems to be stuck, but it is not, so just wait patiently, but if the installation is not complete after 20 minutes, then there might be something wrong. In order to use `all-the-icons` package, you need to manually install its fonts within Emacs by `M-x all-the-icons-install-fonts`. You may also choose to disable features using `all-the-icons`, although in this way Emofacs may look less pretty.

Even if everything goes well, Emacs may still display some warnings and errors after initialization. Just ignore them and restart Emacs, and then there should be no warnings any more;

## Packages

* [use-package](https://github.com/jwiegley/use-package) (allows you to isolate package configuration in a way that is both performance-oriented and, well, tidy)
* [exec-path-from-shell](https://github.com/purcell/exec-path-from-shell) (ensures environment variables inside Emacs look the same as in the user's shell)
* [Dracula](https://draculatheme.com/emacs/) (dark theme)
* [all-the-icons](https://github.com/domtronn/all-the-icons.el) (used to include fancy icons)
* [Power Line](https://github.com/milkypostman/powerline) (Emacs version of the Vim powerline)
* [Dashboard](https://github.com/emacs-dashboard/emacs-dashboard) (a startup dashboard which provides certain information about your recent Emacs activities)
* [Zoom](https://github.com/cyrus-and/zoom) (fixed and automatic balanced window layout for Emacs)
* [Ivy](https://github.com/abo-abo/swiper) (generic completion mechanism)
* [Projectile](https://github.com/bbatsov/projectile) (project interaction library)
* [Treemacs](https://github.com/Alexander-Miller/treemacs) (tree layout file explorer)
* [Company](https://company-mode.github.io/) (text completion framework)
* [LSP](https://emacs-lsp.github.io/lsp-mode/) (language server protocal)
* [YASnippet](https://github.com/joaotavora/yasnippet) (template system)
* [Flycheck](https://www.flycheck.org/en/latest/) (modern on-the-fly syntax checking extension)
* [Smartparens](https://github.com/Fuco1/smartparens) (dealing with pairs)
* [Magit](https://magit.vc/) (complete text-based user interface to [Git](https://git-scm.com/))

They are the external packages and their links.

## Usage

The learning curve of Emacs is steep, but once you get it, you may feel the power that Emacs brings you. With emacs, you may discover that a mouse is not that important. Most actions can be done using your keyboard withouy your hands moving away.

However, I am not going to teach you how to use Emacs or any of the specific packages mentioned above. Instead, I have listed their official websites or GitHub links so that you may easily find documents on each of them and begin exploring.

## License

MIT License © Jiacheng Huang

