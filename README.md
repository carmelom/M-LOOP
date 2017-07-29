# M-LOOP

The Machine-Learner Online Optimization Package is designed to automatically and rapidly optimize the parameters of a scientific experiment or computer controller system.

## Installation

To install M-LOOP simply run:

    pip install --user -e .

In the M-LOOP source folder. this is recommended over `python setup.py develop` beacuse allows pip to track the installed files (using an .egg-link from the $HOME/.local/lib/python**/site-packages folder to the M-LOOP source)

## Docs

For more details on how to use the package see the documentation. You can see it online at

http://m-loop.readthedocs.io/

Or you can build it by entering the docs folder and running:

build html

The docs can then be found in docs/build/html

## Uninstall

    pip uninstall M-LOOP

## Cite

If you use M-LOOP please cite its first application:

http://www.nature.com/articles/srep25890

M-LOOP is written and maintained by Michael R Hush MichaelRHush@gmail.com.
