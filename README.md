aport
==========

<!---
This file is generated by ape-tmpl. Do not update manually.
--->

<!-- Badge Start -->
<a name="badges"></a>

[![Build Status][bd_travis_shield_url]][bd_travis_url]
[![npm Version][bd_npm_shield_url]][bd_npm_url]
[![JS Standard][bd_standard_shield_url]][bd_standard_url]

[bd_repo_url]: https://github.com/okunishinishi/node-aport
[bd_travis_url]: http://travis-ci.org/okunishinishi/node-aport
[bd_travis_shield_url]: http://img.shields.io/travis/okunishinishi/node-aport.svg?style=flat
[bd_travis_com_url]: http://travis-ci.com/okunishinishi/node-aport
[bd_travis_com_shield_url]: https://api.travis-ci.com/okunishinishi/node-aport.svg?token=
[bd_license_url]: https://github.com/okunishinishi/node-aport/blob/master/LICENSE
[bd_codeclimate_url]: http://codeclimate.com/github/okunishinishi/node-aport
[bd_codeclimate_shield_url]: http://img.shields.io/codeclimate/github/okunishinishi/node-aport.svg?style=flat
[bd_codeclimate_coverage_shield_url]: http://img.shields.io/codeclimate/coverage/github/okunishinishi/node-aport.svg?style=flat
[bd_gemnasium_url]: https://gemnasium.com/okunishinishi/node-aport
[bd_gemnasium_shield_url]: https://gemnasium.com/okunishinishi/node-aport.svg
[bd_npm_url]: http://www.npmjs.org/package/aport
[bd_npm_shield_url]: http://img.shields.io/npm/v/aport.svg?style=flat
[bd_standard_url]: http://standardjs.com/
[bd_standard_shield_url]: https://img.shields.io/badge/code%20style-standard-brightgreen.svg

<!-- Badge End -->


<!-- Description Start -->
<a name="description"></a>

Find freeport with promise

<!-- Description End -->


<!-- Overview Start -->
<a name="overview"></a>



<!-- Overview End -->


<!-- Sections Start -->
<a name="sections"></a>

<!-- Section from "doc/guides/01.Installation.md.hbs" Start -->

<a name="section-doc-guides-01-installation-md"></a>

Installation
-----

```bash
$ npm install aport --save
```


<!-- Section from "doc/guides/01.Installation.md.hbs" End -->

<!-- Section from "doc/guides/02.Usage.md.hbs" Start -->

<a name="section-doc-guides-02-usage-md"></a>

Usage
---------

```javascript
'use strict'

const aport = require('aport')

;(async () => {
  // Find free port
  let port = await aport()
  console.log('Free port :', port)
}).catch((err) => console.error(err))

```


<!-- Section from "doc/guides/02.Usage.md.hbs" End -->


<!-- Sections Start -->


<!-- LICENSE Start -->
<a name="license"></a>

License
-------
This software is released under the [MIT License](https://github.com/okunishinishi/node-aport/blob/master/LICENSE).

<!-- LICENSE End -->


<!-- Links Start -->
<a name="links"></a>

Links
------



<!-- Links End -->
