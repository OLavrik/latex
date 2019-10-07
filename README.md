## Установите соответсвующую библиотеку 
At the command line, first install the texlive package if it isn't already installed:
```
sudo apt-get install texlive
```
There are several settings that you can read about in the help for pdflatex:
```
pdflatex --help
```
## Установите пакеты:
```
\usepackage[utf8]{inputenc}
\usepackage[english,russian]{babel}
\usepackage{cmap}
\usepackage{geometry}
```

## Поменяйте нужную информацию 
```
nano main.tex
```
## Запустите Makefile
```
make run
```
