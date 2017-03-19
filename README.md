# calvin and hobbes

downloader of garfield comics

## Installation

    $ pip install garfield-get

## Requirements

* bs4
* grequests

## Usage

    $ # Downloads all garfield comics to ~/Downloads/garfield
    $ garfield-get

    $ # Downloads garfield comics [1999-01-03..2012-10-20] to /tmp/garfield
    $ garfield-get --start=1999-01-03 --end=2012-10-20 --output-dir=/tmp/garfield
