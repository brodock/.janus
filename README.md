Custom Janus plugins
====================

This repository is made of custom vim plugins that you should use with a
Janus installation.

For more information about Janus, please visit:
https://github.com/carlhuda/janus

Setup
-----

You need to first install Janus and follow all the instructions to git
it in working conditions.

After you can clone this repository to your $HOME/.janus (the dot in
the name is essential).

As this repository uses Git submodules, you need to type the following:

```
  cd $HOME/.janus
  git submodule init
  git submodule update
```

After that, you need to merge the ".vimrc.after" located inside that
folder with your current $HOME/.vimrc.after, or just copy my version if
you haven't made any customization yet.

If you want to have full support from airline plugin, you should patch
your current terminal font. I've included *PowerlineSymbols.otf* and *10-powerline-symbols.conf*
to speedup the process, but you should follow instructions here:
https://powerline.readthedocs.org/en/latest/installation/linux.html#font-installation

You can also find pre-patched fonts here:
https://github.com/powerline/fonts

And there is a different strategy for fallback symbols without patching
fonts explained here:
https://github.com/gabrielelana/awesome-terminal-fonts

Happy coding :)

What's inside?
--------------

Here are the list of plugins:

* airline
* gitgutter

Customizations:

There are some more customizations like enabling mouse support, ctags
support for rubygems (to be used with Guard), some pre-selected themes,
with monokay as default.
