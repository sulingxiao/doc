---
title: 
sidebar: ont_doc_en
permalink: ontology_install_en.html
folder: doc_en
---

English / [中文](./ontology_install_zh.html)

<h1 align="center">Build development environment</h1>
<p align="center" class="version">Version 0.7.0 </p>


The requirements to build Ontology are:

- Golang version 1.9 or later
- Glide (a third party package management tool)
- Properly configured Go language environment
- Golang supported operating system

## Deployment and test
### Get Ontology
#### Get from source code

Clone the Ontology repository into the appropriate $GOPATH/src/github.com/ontio directory.

```
$ git clone https://github.com/ontio/ontology.git
```
or
```
$ go get github.com/ontio/ontology
```
Fetch the dependent third party packages with glide.

```
$ cd $GOPATH/src/github.com/ontio/ontology
$ glide install
```

Build the source code with make.

```
$ make
```

After building the source code sucessfully, you should see two executable programs:

- `ontology`: the node program/command line program for node control

#### get from release
You can download at [release page](https://github.com/ontio/ontology/releases).