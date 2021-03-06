<p align="center">
  <h3 align="center">jQuery.Timeline V2</h3>

  <table border="0">
    <tr>
    <td width="50%" align="center"><img src="https://ka215.github.io/jquery.timeline/imgs/jquery.timeline_v2a1_bar.png" width="99%" /></td>
    <td width="50%" align="center"><img src="https://ka215.github.io/jquery.timeline/imgs/jquery.timeline_v2a1_point.png" width="99%" /></td>
    </tr>
  </table>

  <p align="center">
    You are able to easily create two types of horizontal timeline with this jQuery plugin.
    <br>
    <br>
    <a href="https://github.com/ka215/jquery.timeline/issues/new?template=bug_report.md">Report bug</a>
    ·
    <a href="https://github.com/ka215/jquery.timeline/issues/new?template=feature_request.md">Request feature</a>
    ·
    <a href="https://ka2.org/">Blog</a>
  </p>
</p>

<br>

## Table of Contents

- [Quick start](#quick-start)
- [Status](#status)
- [What's included](#whats-included)
- [Usage](#usage)
- [Supported browsers](#supported-browsers)
- [Documentation](#documentation)
- [Example as demonstration](#example-as-demonstration)
- [Creators](#creators)
- [Copyright and license](#copyright-and-license)

## Quick start

Several quick start options are available:

- [Download the latest release.](https://github.com/ka215/jquery.timeline/archive/v2.0.0a2.zip)
- Clone the repository: `git clone https://github.com/ka215/jquery.timeline.git`


## Status

[![Packagist](https://img.shields.io/packagist/l/doctrine/orm.svg)](https://raw.githubusercontent.com/ka215/jquery.timeline/master/LICENSE)


## What's included

Within the download you'll find the following directories and files, logically grouping common assets and providing compiled and minified variations. You'll see something like this:

```
jquery.timeline/
└── dist/
    ├── jquery.timeline.min.css
    ├── jquery.timeline.min.css.map
    ├── jquery.timeline.min.js
    └── jquery.timeline.min.js.map
```

We provide compiled and minified CSS and JS (`jquery.timeline.min.*`). source maps (`jquery.timeline.*.map`) are available for use with certain browsers' developer tools.


## Usage

Include the installed files into your html:

```HTML
<link rel="stylesheet" src="./jquery.timeline/dist/jquery.timeline.min.css">

<script src="./jquery.timeline/dist/jquery.timeline.min.js"></script>
```

Bind this plugin in the scope had imported the jQuery:

```JavaScript
$('#myTimeline').Timeline()
```


## Supported browsers

jQuery.Timeline version 2.x supports the following browsers:

<table>
<thead>
<tr>
<th colspan="6">PC</th>
<th colspan="2">Mobile</th>
</tr>
<tr>
<th width="12.5%" align="center"><img src="https://github.com/ka215/jquery.timeline/blob/develop/docs/imgs/chrome-brands.svg" width="32" alt="Chrome" /></th>
<th width="12.5%" align="center"><img src="https://github.com/ka215/jquery.timeline/blob/develop/docs/imgs/firefox-brands.svg" width="32" alt="Firefox" /></th>
<th width="12.5%" align="center"><img src="https://github.com/ka215/jquery.timeline/blob/develop/docs/imgs/safari-brands.svg" width="32" alt="Safari" /></th>
<th width="12.5%" align="center"><img src="https://github.com/ka215/jquery.timeline/blob/develop/docs/imgs/internet-explorer-brands.svg" width="32" alt="IE" /></th>
<th width="12.5%" align="center"><img src="https://github.com/ka215/jquery.timeline/blob/develop/docs/imgs/edge-brands.svg" width="32" alt="Edge" /></th>
<th width="12.5%" align="center"><img src="https://github.com/ka215/jquery.timeline/blob/develop/docs/imgs/opera-brands.svg" width="32" alt="Opera" /></th>
<th width="12.5%" align="center"><img src="https://github.com/ka215/jquery.timeline/blob/develop/docs/imgs/android-brands.svg" width="32" alt="Android" /></th>
<th width="12.5%" align="center"><img src="https://github.com/ka215/jquery.timeline/blob/develop/docs/imgs/safari-brands.svg" width="32" alt="iOS Safari" /></th>
</tr>
</thead>
<tbody>
<tr>
<td name="PC:Chrome" align="center"><b style="color:green">Ok</b></td>
<td name="PC:Firefox" align="center"><b style="color:green">Ok</b></td>
<td name="PC:Safari" align="center"><b style="color:#CCC">?</b></td>
<td name="PC:IE" align="center"><b style="color:red">NG</b></td>
<td name="PC:Edge" align="center"><b style="color:green">Ok</b></td>
<td name="PC:Opera" align="center"><b style="color:#CCC">?</b></td>
<td name="MP:Android" align="center"><b style="color:#CCC">?</b></td>
<td name="MP:iOS Safari" align="center"><b style="color:#CCC">?</b></td>
</tr>
</tbody>
</table>

Unfortunately as for the Internet Explorer etc., several methods of this plugin does not work because JavaScript implementation of browser is too immature. Please note that we are not go to support for these legacy browsers in the future.


## Documentation

jQuery.Timeline's documentation, included in this repository in the root directory, is built with [ESDoc](https://esdoc.org/) and publicly hosted on GitHub Pages at <https://ka2.org/>. The docs may also be run locally.


### Documentation for previous releases

- For v2.0.x: (WIP)
- For v1.0.x: <https://raw.githubusercontent.com/ka215/jquery.timeline/v1/README.md>
- For v1.0.x (Japanese): <https://ka2.org/released-jquery-timeline-for-easily-generating-two-type-horizontal-timeline/>

## Example as demonstration

(WIP)

## Creators

**ka2 (Katsuhiko Maeno)**

- <https://ka2.org/>

## Copyright and license

Code and documentation copyright 2011-2018 the [ka2](https://ka2.org/). Code released under the [MIT License](https://raw.githubusercontent.com/ka215/jquery.timeline/master/LICENSE).

