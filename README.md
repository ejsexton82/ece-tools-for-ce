Magento Cloud Deployment Tools for Community Edition
====================================================

[![magento](http://img.shields.io/:magento->=2.1.4-orange.svg)](link-magento)
[![semver](http://img.shields.io/:semver-1.0.0-brightgreen.svg)](http://semver.org)
[![license](https://img.shields.io/badge/license-OSL 3.0-green.svg)][link-license]

This package provides configuration files that are required to use
[ECE-Tools](link-ece-tools) with [Magento Community Edition](link-magento).

It does not modify the functionality of [ECE-Tools](link-ece-tools) in any way.

Installation
------------

Install the composer package.

```sh
composer require ejsexton/ece-tools-for-ce
```

These configuration files will be mapped to the base directory:

* .magento.app.yaml
* .magento/routes.yaml
* .magento/services.yaml

License
-------

This project is licensed under the terms of the [Open Software License v. 3.0 (OSL-3.0)][link-license].

[link-magento]: https://github.com/magento/magento2
[link-license]: https://github.com/ejsexton82/ece-tools-for-ce/blob/master/LICENSE.txt
[link-ece-tools]: https://github.com/magento/ece-tools
