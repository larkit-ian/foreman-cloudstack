# Foreman Cloudstack Plugin

This plugin enables provisioning and managing a Cloudstack Server in Foreman.

## Installation

Please see the Foreman manual for appropriate instructions:

* [Foreman: How to Install a Plugin](http://theforeman.org/manuals/latest/index.html#6.1InstallaPlugin)

The gem name is "foreman_cloudstack".

You can also use the Vagrantfile included.

## Compatibility

| Foreman Version | Plugin Version |
| ---------------:| --------------:|
| >=  1.5         | 0.0.1          |

## Latest code

You can get the develop branch of the plugin by specifying your Gemfile in this way:

    gem 'foreman_cloudstack', :git => "https://github.com/citrix/foreman-cloudstack.git"

## Limitations

Only advanced networking is supported

Zone selection is not supported

All user data is gzipped

# Copyright

Copyright (c) 2014 Citrix

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program.  If not, see <http://www.gnu.org/licenses/>.