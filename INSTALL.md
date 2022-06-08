### [emacs](https://www.emacs.org/)

#### Install in Emacs 28+

minimal-mistakes is available in [NonGNU Elpa](https://elpa.nongnu.org/nongnu/minimal-mistakes-theme.html) and thus, will be directly available starting from that version of Emacs.

```
M-x package-install <RET> minimal-mistakes-theme
```

#### Install using MELPA

First, make sure to have [enabled MELPA repository in your configuration](https://melpa.org/#/getting-started). Then, you will find minimal-mistakes in the regular package listing.

```
M-x package-install <RET> minimal-mistakes-theme
```

#### Install from Download

Download using the [GitHub .zip](https://github.com/Minimal-Mistakes/emacs/archive/main.zip) download option

Add the emacs theme files to ~/.emacs.d/themes.
To load a theme add the following to your init.el

```
(add-to-list 'custom-theme-load-path "~/.emacs.d/themes")
(load-theme 'minimal-mistakes t)
```

#### Install using Git

If you are a git user, you can install the theme and keep up to date by cloning the repo:

```
git clone https://github.com/Minimal-Mistakes/emacs.git ~/.emacs.d/themes/
```

To load a theme add the following to your init.el

```
(add-to-list 'custom-theme-load-path "~/.emacs.d/themes")
(load-theme 'minimal-mistakes t)
```

#### Configure

Some aspects of this theme are customizable. You can change them by doing `M-x customize-group minimal-mistakes`. Then restart Emacs to apply them.

#### Activating theme

Reload emacs for the config to take affect.
