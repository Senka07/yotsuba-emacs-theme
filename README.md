# 4 Chan Theme for Emacs

Theme for Emacs inspired by the aesthetic of the 4chan imageboard.

Those theme maps the original CSS palette to Emacs faces, providing a environment for programmers and writers who appreciate the "old web" design.

## Screenshots

![Yotsuba Theme Preview](img/yotsuba.png)
![Yotsuba B Theme Preview](img/yotsuba_b.png)
![Tomorrow Dark Theme Preview](img/tomorrow-dark.png)

## Installation

### Manual Installation

1. Clone the repository to your themes directory:
   ```bash
   git clone [https://github.com/Senka07/yotsuba-emacs-theme.git](https://github.com/Senka07/yotsuba-emacs-theme.git) ~/.emacs.d/themes/

    Add the following to your init.el:
    

    ;; Add the theme directory to load-path
    (add-to-list 'custom-theme-load-path "~/.emacs.d/themes/")

    ;; Load the theme:
    (load-theme 'theme-name t)
    

### Installation via use-package (Straight.el / Quelpa)

If you use straight.el or quelpa, add this to your configuration:

```elisp
(use-package yotsuba-theme
  :straight (:host github :repo "Senka07/yotsuba-emacs-theme")
  :init
  (load-theme 'theme-name t))
```

