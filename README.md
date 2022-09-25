.tmux
=====

Просто мой конфиг для tmux
Основано на [gpakosz/.tmux](https://github.com/gpakosz/.tmux)

Установка
------------

Требования:

  - tmux **`>= 2.4`** в Linux, Mac, OpenBSD, Cygwin или WSL
  - awk, perl и sed
  - переменная `$TERM` должна иметь значение `xterm-256color`

Для установки просто запусти указанные ниже команды в терминале: (возможно, сначала стоит сделать бэкап уже имеющегося конфига `~/.tmux.conf`)

```
$ cd
$ git clone https://github.com/dbconfig/.tmux.git
$ ln -s -f .tmux/.tmux.conf
$ cp .tmux/.tmux.conf.local .
```

💡 Ты можешь клонировать репозиторий куда угодно, главное - создать соответствующую символическую ссылку `~/.tmux.conf` и скопировать файл `.tmux.conf.local` в домашний каталог:

```
$ git clone https://github.com/dbconfig/.tmux.git /path/to/oh-my-tmux
$ ln -s -f /path/to/oh-my-tmux/.tmux.conf ~/.tmux.conf
$ cp /path/to/oh-my-tmux/.tmux.conf.local ~/.tmux.conf.local
```
