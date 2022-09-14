# Activity

Dedicating about 20% of my time to open-source software and maintaining docker
images as well as deployment templates for Data Science.

*  [Multi-arch docker images](https://gitlab.b-data.ch/explore?sort=latest_activity_desc&name=Multi-arch%20Docker%20Image&sort=latest_activity_desc)[^1]:
    *  [JupyterLab R docker stack](https://github.com/b-data/jupyterlab-r-docker-stack)
    *  [JupyterLab Python docker stack](https://github.com/b-data/jupyterlab-python-docker-stack)
    *  [JupyterLab Julia docker stack](https://github.com/b-data/jupyterlab-julia-docker-stack)  
       All JupyterLab images include
        *  [code-server](https://github.com/cdr/code-server)  
            → VS Code in the browser
        *  [Git](https://git-scm.com)
        *  [Git LFS](https://git-lfs.github.com)
        *  [Pandoc](https://pandoc.org)
        *  [Zsh](http://zsh.sourceforge.net)
    *  [R docker stack](https://github.com/b-data/r-docker-stack)
    *  [Python docker stack](https://github.com/b-data/python-docker-stack)
    *  [Julia docker stack](https://github.com/b-data/julia-docker-stack)  
       Counterparts[^2] to the JupyterLab images but **without**
        *  code-server
        *  IRKernel/IPython/IJulia
        *  JupyterHub/JupyterLab
        *  Jupyter Notebook
        *  LSP Servers
        *  Oh My Zsh
        *  Widgets
*  Docker deployment templates:
    *  [Træfik](https://github.com/b-data/docker-deployment-traefik)
    *  [GitLab CE](https://github.com/b-data/docker-deployment-gitlab-ce)
    *  [Jupyter](https://github.com/b-data/docker-deployment-jupyter)
*  _Containerised_ source-installations:
    *  [R](https://github.com/b-data/rsi)
    *  [Git](https://github.com/b-data/gsi)
*  _Containerised_ installations:
    *  [Git LFS](https://github.com/b-data/glfsi)

---

Following the development of

1.  https://gitlab.haskell.org/ghc/ghc  
    and
1.  https://gitlab.alpinelinux.org/alpine/aports

in order to maintain [GHC for pandoc](https://github.com/benz0li/ghc4pandoc)
([`registry.gitlab.b-data.ch/ghc/ghc4pandoc`](https://gitlab.b-data.ch/ghc/ghc4pandoc/container_registry)).

# Linked accounts

*  https://gitlab.b-data.ch/benz0li
*  https://gitlab.com/benz0li

[^1]: Current `os/arch`'s: `linux/amd64`, `linux/arm64/v8`  
[^2]: Use cases: Base image, CI pipelines, headless analyses
