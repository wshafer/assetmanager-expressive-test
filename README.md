# Asset Manager Zend Expressive Sandbox

## Introduction

This is a skeleton application using the Zend Expressive module
system. It's designed to be a quick test bed for the 
Zend Expressive integration.

## Installation


```bash
$ git clone git@github.com:wshafer/assetmanager-expressive-test.git expressive-test
$ cd expressive-test
$ vagrant up
$ vagrant ssh -c 'composer install'
```

Once installed, you can test it out immediately using vagrants
web server and test that you can get the test files pre-configured
in the modules/Application:

```bash
http://localhost:8080/modules/application/earthafr.jpeg
http://localhost:8080/modules/application/require-jquery.js
```
