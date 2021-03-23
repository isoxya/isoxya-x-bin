# Isoxya Scripts

[Isoxya Scripts](https://github.com/isoxya/isoxya-x-bin) is an open-source (BSD 3-Clause) collection of scripts for [Isoxya](https://www.isoxya.com/) web crawler. With these, it's possible to crawl sites and perform other operations using the Isoxya API. These are useful not only in development, but also as a demo of Isoxya's main capabilities, a quick way of performing actions even in production, and also in providing a functional reference for those wishing to develop their own programs on top of Isoxya.

Also see [Isoxya web crawler Community Edition](https://github.com/isoxya/isoxya-ce) (Isoxya CE), a free and open-source (BSD 3-Clause) mini crawler, suitable for small crawls on a single computer.

Also see the [Tigrosa Scripts](https://github.com/tiredpixel/tigrosa-x-bin), a collection of scripts for [Tigrosa](https://docs.tigrosa.tiredpixel.com/#tigrosa) auth proxy, on top of which these scripts build.


## Dependencies

- [jq](https://stedolan.github.io/jq/)
- [Tigrosa Scripts](https://github.com/tiredpixel/tigrosa-x-bin)


## Installation

These scripts are provided by way of example, but are also suitable for controlling the API via a CLI even in production. The repository can be cloned somewhere, and included in your PATH when required (or permanently in your `$HOME/.bash_profile`).

```sh
cd $HOME
git clone git@github.com:tiredpixel/isoxya-x-bin.git

PATH=$PATH:$HOME/isoxya-x-bin/bin
```


## Contact

[en@isoxya.com](mailto:en@isoxya.com) · [isoxya.com](https://www.isoxya.com/)

[tp@tiredpixel.com](mailto:tp@tiredpixel.com) · [tiredpixel.com](https://www.tiredpixel.com/)

LinkedIn: [in/nic-williams](https://www.linkedin.com/in/nic-williams/) · GitHub: [tiredpixel](https://github.com/tiredpixel)


## Licence

Copyright © 2020-2021 [Nic Williams](https://www.tiredpixel.com/). It is free software, released under the BSD 3-Clause licence, and may be redistributed under the terms specified in `LICENSE`.
