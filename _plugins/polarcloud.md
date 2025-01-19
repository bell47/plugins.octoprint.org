---
layout: plugin

id: polarcloud
title: Polar Cloud
description: Connects OctoPrint to the Polar Cloud so you can easily monitor and control OctoPrint outside of your local network
author: Mark Walker
license: AGPLv3

date: 2017-07-14

homepage: https://github.com/markwal/OctoPrint-PolarCloud/blob/master/README.md
source: https://github.com/markwal/OctoPrint-PolarCloud
archive: https://github.com/markwal/OctoPrint-PolarCloud/archive/master.zip

# Set this to true if your plugin uses the dependency_links setup parameter to include
# library versions not yet published on PyPi. SHOULD ONLY BE USED IF THERE IS NO OTHER OPTION!
follow_dependency_links: false

tags:
- cloud
- remote access
- polarcloud

screenshots:
- url: /assets/img/plugins/polarcloud/polarcloud.png
  alt: Screenshot of Polar Cloud monitoring a printer
  caption: Screenshot of Polar Cloud monitoring a printer
- url: /assets/img/plugins/polarcloud/multipleprinters.png
  alt: Screenshot of Polar Cloud monitoring multiple printers
  caption: Screenshot of Polar Cloud monitoring a printer

featuredimage: /assets/img/plugins/polarcloud/polarcloud.png

compatibility:
  python: ">=2.7,<4"
  octoprint:
  - 1.3.4

attributes:
- cloud
- commercial
- free-tier

---
## Easily Monitor Your Prints from Anywhere

The Polar Cloud at [polar3d.com](https://polar3d.com) is accessible from
anywhere, inside or outside of the printer's local network.

### Print Queue

You can prepare multiple prints, queue them up and send them one by one to your
printer

### Manage Multiple Printers

You can connect more than one printer to your Polar Cloud account and manage
them all from one place.

### Object Library

You can upload your objects to Polar Cloud, share them with other cloud
members, and send them to your printer.

### README - Getting Started

There's a few extra command line steps to support timelapses in the Polar
Cloud. You can get started without them though. Please read the additional info
in the [README](https://github.com/markwal/OctoPrint-PolarCloud/blob/master/README.md)
