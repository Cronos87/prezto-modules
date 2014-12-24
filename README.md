zprezto-modules
===============

I share my personals zprezto modules.

To activate the modules please copy the repositories to:

```
~/.zprezto/modules
```

then edit the file:

```
~/.zpreztorc
```

and find the line:

```
zstyle ':prezto:load' pmodule
```

You have to add at the bottom of the list, the modules you want to enable.

For example:

```zsh
zstyle ':prezto:load' pmodule \
  'environment' \
  'terminal' \
  'editor' \
  'git' \
  'history' \
  'history-substring-search' \
  'directory' \
  'spectrum' \
  'utility' \
  'completion' \
  'prompt' \
  'osx' \
  'symfony2' \
  'laravel'
```
