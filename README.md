The `nm-mode` is mainly for syntax highlighting. It is derived from `f90-mode`, so that it inherits most Fortran syntax font faces.

To use, download `nm-mode.el` and copy it to lisp search path, and add to the `init.el`
```elisp
(require 'nm-mode)
```

To automatically use this mode on `*.ctl` and `*.mod` control files, add the following to `init.el`.
```elisp
(add-to-list 'auto-mode-alist '("\\.ctl\\'" . nm-mode))
(add-to-list 'auto-mode-alist '("\\.mod\\'" . nm-mode))
```

The colors are chosen to work with `gruvbox-light-soft` theme.

<img width="613" height="332" alt="Screenshot 2025-10-17 at 10 16 53 PM" src="https://github.com/user-attachments/assets/335c2dba-b865-4971-b0c2-d2a90dfc0898" />
