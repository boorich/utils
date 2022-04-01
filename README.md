# utils
little helpers

## timer
This script can be used to track time. I use this to track my work because separate tools added too much overhead to be effective and ergonomic.

Usage:

```
$ timer Customer "Task Description" Seconds

```

Example:
```
martin@martin-tp:~$ timer ElonMusk "Revamping Falcon Heavy for increased load" 1500
... tracking you time: 
1498  
```

## man colors
This scripts adds some color coding to your man pages. It helps me to find things more quickly as it visually groups keywords. This goes to .bashrc.

## google the return
This script allows to directly google upon the return of a command in your terminal. I mainly use this to quickly google for lengthy errors or when I am just to lazy to alt+tab.

Usage:

```
$ google $(somecommand)
$ google keyword

```

Example:
```
martin@martin-tp:~$ google $(pwd)
martin@martin-tp:~$ google foobar

```
