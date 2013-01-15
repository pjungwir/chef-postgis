# Description

Installs [PostGIS](http://postgis.refractions.net/).

## Platforms:

Tested on:

* Ubuntu 12.04

## Recipes:

* `default.rb` - Downloads, builds, and installs PostGIS from source.

## Attributes

* `node['postgis']['version']` - the version of PostGIS to use (default: "2.0.2").
* `node['postgis']['sql_folder']` - the version of GEOS to use (default: "postgis-2.0").
* `node['postgis']['template_name']` - the name of the PostGIS template database to create (default: "template\_postgis").


Author
======

Author:: Paul A. Jungwirth (<pj@illuminatedcomputing.com>)

Some code taken from [Osiloke Harold Emoekpere](https://github.com/osiloke/chef-postgis).


License
=======

Copyright:: 2013, Illuminated Computing Inc.

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
