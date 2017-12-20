Gitchain
========
Decentralized P2P Git Network

To quote from git's own description:

> Git is a free and open source distributed version control system designed to handle everything
> from small to very large projects with speed and efficiency.

Gitchain is an application of ideas behind Bitcoin, Namecoin and DHT applied to Git hosting. Once you install it, it acts as a local proxy to the entire Gitchain P2P network.

Build Instructions
------------------

Make sure you have go1.2.2 installed and your GOPATH variable is pointing to
a user-writeable directory (like $USER/go)


```shell
$ make prepare # (only first time or whenever Godeps file is updated)
$ make
```
