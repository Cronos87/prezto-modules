prezto-modules
==============

Please visit the github project: https://github.com/sorin-ionescu/prezto

I share my own prezto modules.

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

Port
====

I port the Symfony2 module from the oh my zsh one.

Please visit the original oh my zsh plugin: https://github.com/robbyrussell/oh-my-zsh/blob/master/plugins/symfony2/symfony2.plugin.zsh
