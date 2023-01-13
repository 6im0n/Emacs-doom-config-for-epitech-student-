# Emacs-doom-config

**To install doom emacs :**

```
git clone --depth 1 https://github.com/doomemacs/doomemacs ~/.emacs.d
~/.emacs.d/bin/doom install
```

**To activate mouse control in doom emacs**

edit the file below : 

```~/.doom.d/init.el```

uncomment the line with tty to activate it !
```
       :os
       (:if IS-MAC macos)  ; improve compatibility with macOS
       ;;tty   
```

```
       :os
       (:if IS-MAC macos)  ; improve compatibility with macOS
       tty   
```

After that, 

you need to reopen emacs and make ```alt + x``` and type ```doom/reload``` and wait to doom emacs get and
install package. 

you're done ! you now have the mouse control in your emacs-nox 


**for epitech student: (add the snippet hedear plugin to doom emacs)**

in ``` ~/.doom.d/config.el```

add the tow lines : 

```
(load! "std.el")
(load! "std_comment.el")
```

get the two .el files in the repos and put it in : 


```~/.doom.d/```


