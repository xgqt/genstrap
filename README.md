# Genstrap

<p align="center">
    <a href="https://gitlab.com/xgqt/genstrap/pipelines">
        <img src="https://gitlab.com/xgqt/genstrap/badges/master/pipeline.svg">
    </a>
    <a href="https://gitlab.com/xgqt/genstrap/commits/master.atom">
        <img src="https://img.shields.io/badge/feed-atom-orange.svg">
    </a>
    <a href="./LICENSE">
        <img src="https://img.shields.io/badge/license-GPLv3-blue.svg">
    </a>
</p>

Bootstrap a basic gentoo tarball.


# Installation

# Git

As user:

```sh
git clone --recursive --verbose https://gitlab.com/xgqt/genstrap
cd genstrap
sudo make install
```


# Gentoo

As root:

```sh
emerge -1nv app-eselect/eselect-repository
eselect repository enable myov
emaint sync -r myov
emerge -av --autounmask dev-util/genstrap
```
