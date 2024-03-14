# jupyter-windows
As it always take me time to looks for commands to do it, this is a small script to install Jupyter on Windows as the official way does not always works.
It uses `python -m pip` instead of direct 'pip', as to avoid to add installation folder to the path (wich is not alwas possible). It also create the configuration file if you want to change Jupyter configuration, see [https://jupyterlab-server.readthedocs.io/en/stable/api/app-config.html]().

# Installation 
Just download and run `install_jupyter.bat` on Windows.

To launch the software, you can use the script `launch-jupyterlab.bat`.

To open Jupyter in a specific repository, you can add ` --notebook-dir="your-repository"`.
