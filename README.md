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

  cd $HOME/.janus
  git submodule init
  git submodule update

After that, you need to merge the ".vimrc.after" located inside that
folder with your current $HOME/.vimrc.after, or just copy my version if
you haven't made any customization yet.

If you want to have full support from airline plugin, you should patch
your current terminal font. I've included *PowerlineSymbols.otf* and *10-powerline-symbols.conf*
to speedup the process, but you should follow instructions here: 
https://powerline.readthedocs.org/en/latest/installation/linux.html#font-installation

Happy coding :)

What's inside?
--------------

Here are the list of plugins:

* tabline
* airline
* gitgutter
