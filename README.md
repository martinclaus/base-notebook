[![DockerHub badge](https://images.microbadger.com/badges/version/jupyter/base-notebook.svg)](https://microbadger.com/images/martinclaus/base-notebook "Recent tag/version of jupyter/base-notebook")
[![Binder badget](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/martinclaus/base-notebook/master "Launch a martinclaus/base-notebook container on mybinder.org")

# Jupyter Docker Stacks base-notebook

`base-notebook` is a ready-to-run [Docker image](https://hub.docker.com/u/martinclaus)
providing Jupyter applications such as Jupyter Server and JupyterLab. It can run as a
stand-alone server, a single-user server behind a Jupyterhub or on binder.

## Jupyter Notebook Deprecation Notice

Following [Jupyter Notebook notice](https://github.com/jupyter/notebook#notice), we encourage users to transition to JupyterLab.
This can be done by passing the environment variable `JUPYTER_ENABLE_LAB=yes` at container startup, 
more information is available in the [documentation](https://jupyter-docker-stacks.readthedocs.io/en/latest/using/common.html#docker-options).

## Quick Start

You can try a
[relatively recent build of the jupyter/base-notebook image on mybinder.org](https://mybinder.org/v2/gh/martinclaus/base-notebook/master?filepath=README.ipynb)
by simply clicking the preceding link. Otherwise, the two examples below may help you get started if
you [have Docker installed](https://docs.docker.com/install/) and want to launch a single Jupyter server in a container.
More information on the startup options are available in the [documentation](https://jupyter-docker-stacks.readthedocs.io/en/latest/using/common.html#docker-options)
of the [Jupyter docker stacks](https://github.com/jupyter/docker-stacks) project.

## Resources

- [Jupyter docker-stacks Documentation on ReadTheDocs](http://jupyter-docker-stacks.readthedocs.io/)
- [Jupyter Discourse Q&A](https://discourse.jupyter.org/c/questions)
- [Jupyter Website](https://jupyter.org)
- [Images on DockerHub](https://hub.docker.com/u/martinclaus)
