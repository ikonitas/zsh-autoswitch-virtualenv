Autoswitch Python Virtualenv
============================

*zsh-autoswitch-virtualenv* automatically detects and activates your virtualenv if matching project
name exists in ``AUTOSWITCH_VIRTUAL_ENV_DIR``:

::

  export AUTOSWITCH_VIRTUAL_ENV_DIR="/var/envs"


Installing
----------

**oh-my-zsh**

Copy this repository to ``$ZSH_CUSTOM/plugins``, where ``$ZSH_CUSTOM``
is the directory with custom plugins of oh-my-zsh `(read more) <https://github.com/robbyrussell/oh-my-zsh/wiki/Customization/>`_:

::

    git clone "https://github.com/ikonitas/zsh-autoswitch-virtualenv.git" "$ZSH_CUSTOM/plugins/autoswitch_virtualenv"

Then add this line to your ``.zshrc``. Make sure it is **before** the line ``source $ZSH/oh-my-zsh.sh``.

::

    plugins=(autoswitch_virtualenv $plugins)
