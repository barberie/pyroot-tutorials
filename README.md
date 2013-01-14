pyroot-tutorials
================

[![Build Status](https://travis-ci.org/rootpy/pyroot-tutorials.png)](https://travis-ci.org/rootpy/pyroot-tutorials)


[PyROOT](http://root.cern.ch/drupal/content/pyroot) is a [Python](http://en.wikipedia.org/wiki/Python_(programming_language)) programming language extension module that allows the user to interact with any [ROOT](http://root.cern.ch) class from the Python interpreter.
The [``rootpy``](https://github.com/rootpy/rootpy) and [``root_numpy``](https://github.com/rootpy/root_numpy) projects build on top of ``PyROOT`` to make working with ROOT from Python more user-friendly and faster, they come with their own [webpage](http://rootpy.org), which contains links to tutorials and reference documentation.

``PyROOT`` does come with a [manual](http://wlav.web.cern.ch/wlav/pyroot/) and tutorial example scripts at ``tutorials/pyroot/*.py`` (see online [here](https://github.com/bbannier/ROOT/tree/master/tutorials/pyroot)).

Here we aim to provide additional ``PyROOT`` tutorials and documentation that are supposed to
* make it easier to get started with ``PyROOT`` (check out the introduction IPython notebook)
* learn some tricks that are important to know when using ``PyROOT`` (like what is fast and what isn't)
* cover more ROOT functionality (e.g. RooStats, RooFit, TMVA) than the official ``PyROOT`` tutorials.

Any contribution is very welcome (via a [pull request](https://help.github.com/articles/using-pull-requests) for the [pyroot-tutorials](https://github.com/rootpy/pyroot-tutorials/) repo on [github](https://github.com)), specifically we are looking for more
* Python scripts or IPython notebooks that showcase / explain some aspect of ``ROOT`` / ``PyROOT`` in the [``tutorials``](https://github.com/rootpy/pyroot-tutorials/blob/master/tutorials) folder.
* Tips and tricks on working with ``PyROOT`` (e.g. how ROOT library loading in the background works, tab completion in IPython, C++ to Python translation recipes, ...) in the [``docs``](https://github.com/rootpy/pyroot-tutorials/blob/master/docs) folder, although in most cases an IPython notebook would probably work better  and go in the [``tutorials``](https://github.com/rootpy/pyroot-tutorials/blob/master/tutorials) folder.
* C++ to Python translations of official ROOT tutorials ([html](http://root.cern.ch/root/html/tutorials/), [code](https://github.com/bbannier/ROOT/tree/master/tutorials)) (as of January 2013 there's 565 `.C` files there and only 39 `.py` files) in the ``official`` folder.
* Links to other good ``ROOT`` / ``PyROOT`` resources in [``docs/Resources.rst``](https://github.com/rootpy/pyroot-tutorials/blob/master/docs/Resources.rst)
