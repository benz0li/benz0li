# Activity

I dedicate about 20% of my time to open-source software maintaining dev
containers, docker images and deployment templates for Data Scientists.

* [(GPU accelerated) Multi-arch Data Science Dev Containers](https://github.com/b-data/data-science-devcontainers)[^1]
* [(GPU accelerated) Multi-arch docker images](https://gitlab.b-data.ch/explore?name=Multi-arch+Docker+Image+CUDA&sort=latest_activity_desc)[^1]:
  * [(CUDA-enabled) JupyterLab QGIS docker stack](https://github.com/b-data/jupyterlab-qgis-docker-stack)
  * [(CUDA-enabled) JupyterLab Python docker stack](https://github.com/b-data/jupyterlab-python-docker-stack)
  * [(CUDA-enabled) JupyterLab Julia docker stack](https://github.com/b-data/jupyterlab-julia-docker-stack)
  * [(CUDA-enabled) JupyterLab R docker stack](https://github.com/b-data/jupyterlab-r-docker-stack)  
    *All JupyterLab images include*
    * [code-server](https://github.com/cdr/code-server)  
      → [VS Code](https://github.com/microsoft/vscode) in the browser
    * [Git](https://git-scm.com)
    * [Git LFS](https://git-lfs.github.com)
    * [Pandoc](https://pandoc.org)
    * [Zsh](http://zsh.sourceforge.net)  
    *GPU accelerated images include*
    * CUDA runtime,
      [CUDA math libraries](https://developer.nvidia.com/gpu-accelerated-libraries),
      [NCCL](https://developer.nvidia.com/nccl) and
      [cuDNN](https://developer.nvidia.com/cudnn)
      * including development libraries and headers
    * TensortRT and TensorRT plugin libraries
      * including development libraries and headers
  * [(CUDA-enabled) Python docker stack](https://github.com/b-data/python-docker-stack)
  * [(CUDA-enabled) Julia docker stack](https://github.com/b-data/julia-docker-stack)
  * [(CUDA-enabled) R docker stack](https://github.com/b-data/r-docker-stack)  
    *Siblings[^2] of the JupyterLab images **without***
    * code-server
    * IRKernel/IPython/IJulia
    * JupyterHub/JupyterLab
    * Jupyter Notebook
    * LSP Servers
    * Oh My Zsh
    * Widgets  
    *GPU accelerated images include*
    * CUDA runtime,
      [CUDA math libraries](https://developer.nvidia.com/gpu-accelerated-libraries),
      [NCCL](https://developer.nvidia.com/nccl) and
      [cuDNN](https://developer.nvidia.com/cudnn)
      * **without** development libraries and headers
    * TensortRT and TensorRT plugin libraries
      * **without** development libraries and headers
* Customised Docker Hub images[^1]:
  * [Node.js](https://gitlab.b-data.ch/nodejs/nsi/container_registry)
    * Node releases: current, active LTS, latest maintenance LTS[^3]
  * [Python](https://gitlab.b-data.ch/python/psi/container_registry)
    * Python versions: latest, the last two older[^3]
  * [Julia](https://gitlab.b-data.ch/julia/jsi/container_registry)
    * Julia releases: stable, LTS[^3]
  * [JupyterHub](https://gitlab.b-data.ch/jupyterhub/jupyterhub/container_registry)
    * [JupyterHub onbuild](https://gitlab.b-data.ch/jupyterhub/jupyterhub-onbuild/container_registry)
* *Containerised* source installations[^1]:
  * [Orfeo Toolbox](https://github.com/b-data/otbsi)
  * [QGIS](https://github.com/b-data/qgissi)
  * [Git](https://github.com/b-data/gsi)
  * [R](https://github.com/b-data/rsi)
* *Containerised* installations[^1]:
  * [Git LFS](https://github.com/b-data/glfsi)
* Docker deployment templates:
  * [Jupyter](https://github.com/b-data/docker-deployment-jupyter)
  * [GitLab CE](https://github.com/b-data/docker-deployment-gitlab-ce)
  * [Træfik](https://github.com/b-data/docker-deployment-traefik)

---

I follow the development of

1. <https://gitlab.haskell.org/ghc/ghc>  
   and
1. <https://gitlab.alpinelinux.org/alpine/aports>

in order to maintain [GHC musl](https://github.com/benz0li/ghc-musl).

The multi-arch (`linux/amd64`, `linux/arm64/v8`) docker image used to build the
*statically linked* Linux amd64 and arm64 binary releases of

* [Pandoc](https://github.com/jgm/pandoc)
* [Stack](https://github.com/commercialhaskell/stack)
* [Juvix](https://github.com/anoma/juvix)

Images available at

* [Quay](https://quay.io/repository/benz0li/ghc-musl):
  `quay.io/benz0li/ghc-musl`
* [Docker Hub](https://hub.docker.com/r/benz0li/ghc-musl):
  `docker.io/benz0li/ghc-musl`
* [GitLab (b-data GmbH)](https://gitlab.b-data.ch/ghc/ghc-musl/container_registry/381):
  `glcr.b-data.ch/ghc/ghc-musl`

## Linked accounts

* <https://gitlab.b-data.ch/benz0li>
* <https://gitlab.com/benz0li>

[^1]: Current `os/arch`'s: `linux/amd64`, `linux/arm64/v8`  
[^2]: Use cases (not exhaustive): Parent image, Dev Container, CI pipeline  
[^3]: Base images: Debian (slim): stable, oldstable; Ubuntu: current LTS, former LTS
