This repository includes *wlan slovenija* presentation template that is used
for our workshops. Our presentations are written in Beamer, a LaTeX class for
slides. Below are a few instructions on installing the template on different
platforms:

Linux (focused on Ubuntu/Mint/Debian)
-------------------------------------

Assuming that you are using texlive LaTeX distribution all you have to do is to
copy the content of the ``/theme/beamer/`` directory to ``~/.texmf-var/`` and
run ``mktexlsr`` to index the files. If you want to keep the files in the
repository you have to configure environmental variable ``TEXMFHOME`` like
this::

    export TEXMFHOME=~/.texmf-var/:<path to repository>/theme/beamer

Usually this line is written into ``.bashrc`` file so that the variable is
present in every new terminal. You may also have to run ``mktexlsr``.

You can test the configuration by trying to compile sample presentation located
in ``sample`` directory.

Mac OS X
--------

TODO

Windows
-------

TODO
