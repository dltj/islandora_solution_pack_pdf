# PDF Solution Pack [![Build Status](https://travis-ci.org/Islandora/islandora_solution_pack_pdf.png?branch=7.x)](https://travis-ci.org/Islandora/islandora_solution_pack_pdf)

## Introduction

Loads all required Fedora Objects, and creates an empty collection object to accept PDFs.

## Requirements

This module requires the following modules/libraries:

* [Islandora](https://github.com/islandora/islandora)
* [Tuque](https://github.com/islandora/tuque)
* [ImageMagick](http://www.imagemagick.org/script/index.php) - Debian/Ubuntu `sudo apt-get install imagemagick`
* [pdftotext](http://poppler.freedesktop.org) -  Debian/Ubuntu `sudo apt-get install poppler-utils`
* [ghostscript](http://www.ghostscript.com) - Debian/Ubuntu `sudo apt-get install gs`

## Installation

Install as usual, see [this](https://drupal.org/documentation/install/modules-themes/modules-7) for further information.

## Configuration

Configure thumbnail and preview image sizes, and set the path for `pdftotext` and `gs` if extract text stream and create PDFA derivative are selected, respectively, in Administration » Islandora »  Solution pack configuration »  PDF Solution Pack (admin/islandora/solution_pack_config/pdf).

![Configuration](https://raw.githubusercontent.com/dmoses/islandora_screenshots/master/pdf_sp_config.jpg)

## Troubleshooting/Issues

Having problems or solved a problem? Check out the Islandora google groups for a solution.

* [Islandora Group](https://groups.google.com/forum/?hl=en&fromgroups#!forum/islandora)
* [Islandora Dev Group](https://groups.google.com/forum/?hl=en&fromgroups#!forum/islandora-dev)

## Maintainers/Sponsors

Current maintainers:

* [Nick Ruest](https://github.com/ruebot)

## Development

If you would like to contribute to this module, please check out our helpful [Documentation for Developers](https://github.com/Islandora/islandora/wiki#wiki-documentation-for-developers) info, as well as our [Developers](http://islandora.ca/developers) section on the Islandora.ca site.

## License

[GPLv3](http://www.gnu.org/licenses/gpl-3.0.txt)
