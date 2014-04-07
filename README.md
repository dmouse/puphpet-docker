puphpet-docker
==============

Run puphpet.com configuration file in docker

```bash
$ git clone https://github.com/dmouse/puphpet-docker.git
$ cd puphpet-docker
$ # put your puphpet.com config files in puphpet folder
$ tree . -L 2
.
|-- Dockerfile
|-- puphpet
|   |-- config.yaml
|   |-- files
|   |-- puppet
|   |-- README.md
|   `-- shell
`-- www
    |-- php.dev
    `-- README.md

$ docker build -t puppet .
$ docker run -i -t puppet /bin/bash

```
