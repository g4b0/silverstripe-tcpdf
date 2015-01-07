# TCPDF Module

## Maintainer Contact

* Michael Parkhill <mike@silverstripe.com>

## Requirements

* SilverStripe >= 3.0

## Installation

```
composer require mparkhill/silverstripe-tcpdf *
```

## Documentation

Generate PDF files on-the-fly with php.

This module provides a SilverStripe service wrapper around [TCPDF](http://tcpdf.org),
a php class for generating PDF documents.

The idea here is to provide pdf generation without the use of third party
libraries that rely on command line execution. There are other silverstripe
pdf modules that depend on a third party Java app that is executed via a
command line call to do the actual PDF conversion.

## Usage Overview

See docs/en for more information about configuring the module.
