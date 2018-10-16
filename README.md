# sandgourd

Central asset server with dynamic image resize capability. A custom-built NGINX server.

### Dependencies

* PCRE Library
* LibGD

```sh
# Linux
$ sudo yum install pcre-devel.x86_64
$ sudo yum install gd-devel.x86_64

# OS X
$ brew install pcre
$ brew install gd
```

### Build package

```sh
$ ./configure
$ make build
```

### Deploy package

```sh
$ ./configure
$ make deploy
```

