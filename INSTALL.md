### [emacs](https://www.emacs.org/)

#### Install

Download using the [GitHub .zip](https://github.com/Minimal-Mistakes/emacs/archive/main.zip) download option

Add the emacs theme files to ~/.emacs.d/themes.
To load a theme add the following to your init.el

```
(add-to-list 'custom-theme-load-path "~/.emacs.d/themes")
(load-theme 'dracula t)
```

#### Install using Git

If you are a git user, you can install the theme and keep up to date by cloning the repo:

```
git clone https://github.com/Minimal-Mistakes/emacs.git ~/.emacs.d/themes/
```

To load a theme add the following to your init.el

```
(add-to-list 'custom-theme-load-path "~/.emacs.d/themes")
(load-theme 'dracula t)
```

#### Activating theme

Reload emacs for the config to take affect.
