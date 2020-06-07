# Header Stamp

[![Build Status](https://travis-ci.com/PrestaShopCorp/header-stamp.svg?branch=master)](https://travis-ci.com/PrestaShopCorp/header-stamp)

Update the headers of the current folder. This tools extracts the command originally available in the PrestaShop Core.

## Installation

This projet is downloadable via Composer, the PHP Package Manager. We recommend having it in the `require-dev` section of your dependancies as it is not needed on production environments.

```
composer require --dev prestashop/header-stamp
```

## Usage

If installed via Composer, the application is available in its binaries folder

```
php vendor/bin/header-stamp
```

The default behavior is to apply the OSL license in every compatible file found in the current folder.

Available options:

```
--license=LICENSE        License file to apply [default: "assets/osl3.txt"]
--exclude=EXCLUDE        Comma-separated list of folders and files to exclude from the update [default: ""]
--extensions=EXTENSIONS  Comma-separated list of file extensions to update [default: "php,js,css,tpl,html.twig,json,vue"]
```
