# node-red-contrib-ssafy-sotaeji

This module provides two sets of nodes of node-RED that have improved convenience in users' cloud interworking and Chart.js creation.

This module helps users  process data using various statistical functions and create charts regardless of the data source.

Users who are not familiar with Chart.js can also be customized easily, but only for some options.

In addition to open APIs and local directories, data sources in the cloud are available.

We wrote the code in the form of a GUI so that any user of Node-RED can easily create a chart.

These nodes require Node.js version 14.17.0 and Node-RED 2.0.6.



## Node

- data-formatter: A node that converts various data sources into json data for using Chart.js.
- Chart Config: A node capable of setting various options of Chart.js.
- FileCloud: A node with file read, upload, and download functions by linking the cloud.



## Pre-requisites

The Motion-Pose-Node requires [Node-RED](https://nodered.org/) to be installed.



## Install

To install the stable version use the `Menu - Manage palette` option and search for `node-red-contrib-ssafy-sotaeji`, or run the following command in your Node-RED user directory - typically `~/.node-red`:

```bash
npm i node-red-contrib-ssafy-sotaeji
```



## Authors

[sotaeji in SSAFY(Samsung Software Academy for Youth)](https://github.com/SOTAEJI)



## Copyright and license

Copyright Samsung Automation Studio Team under [the Apache 2.0 license](https://www.apache.org/licenses/LICENSE-2.0).

