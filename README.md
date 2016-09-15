## Sexy monochrome theme for emacs


## Screenshots
### Source Code

![Monochrome Theme for Emacs 24: Source Code](https://raw.githubusercontent.com/nuncostans/sexy-monochrome-theme/master/sexy-monochrome-theme.png)

### Instalation
Just install form MELPA

```elisp
     M-x package-install RET sexy-monochrome-theme RET
```
and then put in your init file

```elisp
     (load-theme 'sexy-monochrome)
```

 OR throw this file into ~/.emacs.d and
 
```elisp
     (add-to-list 'custom-theme-load-path
                  "~/.emacs.d/YOUR_FOLDER_WITH_THEME/")
```
and

```elisp
     M-x load-theme RET sexy-monochrome RET
```
then put in your init file
```elisp
    (load-theme 'sexy-monochrome)
```
This theme is based on the Xavier Noria [monochrome-theme](https://github.com/fxn/monochrome-theme.el).

Works with Emacs 24.
