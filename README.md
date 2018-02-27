 [![GitHub release](https://img.shields.io/github/release/gnu-mcu-eclipse/eclipse-plugins.svg)](https://github.com/gnu-mcu-eclipse/eclipse-plugins/releases/latest) [![Github Releases](https://img.shields.io/github/downloads/gnu-mcu-eclipse/eclipse-plugins/latest/total.svg)](https://github.com/gnu-mcu-eclipse/eclipse-plugins/releases/latest) [![Github Releases](https://img.shields.io/github/downloads/gnu-mcu-eclipse/eclipse-plugins/total.svg)](https://github.com/gnu-mcu-eclipse/eclipse-plugins/releases/latest) [![SourceForge](https://img.shields.io/sourceforge/dt/gnuarmeclipse.svg?label=SF%20downloads)](https://sourceforge.net/projects/gnuarmeclipse/files/) [![Build Status](https://travis-ci.org/gnu-mcu-eclipse/eclipse-plugins.svg?branch=develop)](https://travis-ci.org/gnu-mcu-eclipse/eclipse-plugins) [![Backers on Open Collective](https://opencollective.com/eclipse-plugins/backers/badge.svg)](#backers) [![Sponsors on Open Collective](https://opencollective.com/eclipse-plugins/sponsors/badge.svg)](#sponsors)

# The GNU MCU Eclipse plug-ins

These are the Eclipse projects used to build the [GNU MCU Eclipse](http://gnu-mcu-eclipse.github.io) plug-ins.

## How to install

The recommended install method is via Eclipse Marketplace.

For manual installs, the stable version update site is:

* http://gnu-mcu-eclipse.netlify.com/v4-neon-updates

## How to build

### Prerequisites

* JavaSE-1.8
* Maven 3

### Command line

```bash
$ git clone --branch=master --recurse-submodules https://github.com/gnu-mcu-eclipse/eclipse-plugins.git eclipse-plugins.git
$ cd eclipse-plugins.git
$ mvn clean verify
```

The result are two p2 repositories:

* `repositories/ilg.gnumcueclipse.repository/target/repository`
* `repositories/ilg.gnumcueclipse.riscv.repository/target/repository`

Note: in some older versions, maven complained something about local artifacts; in case this happens, add `-Dtycho.localArtifacts=ignore` when invoking maven.

### Eclipse

The Eclipse build is described in the [project web](http://gnu-mcu-eclipse.github.io/developer/build-procedure/).

## Run-time dependencies

The minimum requirements for running the GNU MCU Eclipse plug-ins are:

* JavaSE-1.8-111 or later
* CDT 9.2.1 (Neon.3)

Recommended:

* JavaSE-1.8-111 or later
* Eclipse Neon.3

## Developer

https://www.eclipse.org/cdt/developers.php

### Formatting

https://wiki.eclipse.org/CDT/policy

* use tabs, at 4
* code line size: 120 chars
* comments line size: 80 chars

Currently these settings are provided by the default Eclipse Java formatter.


## Contributors

This project exists thanks to all the people who contribute. [[Contribute](CONTRIBUTING.md)].
<a href="graphs/contributors"><img src="https://opencollective.com/eclipse-plugins/contributors.svg?width=890&button=false" /></a>


## Backers

Thank you to all our backers! 🙏 [[Become a backer](https://opencollective.com/eclipse-plugins#backer)]

<a href="https://opencollective.com/eclipse-plugins#backers" target="_blank"><img src="https://opencollective.com/eclipse-plugins/backers.svg?width=890"></a>


## Sponsors

Support this project by becoming a sponsor. Your logo will show up here with a link to your website. [[Become a sponsor](https://opencollective.com/eclipse-plugins#sponsor)]

<a href="https://opencollective.com/eclipse-plugins/sponsor/0/website" target="_blank"><img src="https://opencollective.com/eclipse-plugins/sponsor/0/avatar.svg"></a>
<a href="https://opencollective.com/eclipse-plugins/sponsor/1/website" target="_blank"><img src="https://opencollective.com/eclipse-plugins/sponsor/1/avatar.svg"></a>
<a href="https://opencollective.com/eclipse-plugins/sponsor/2/website" target="_blank"><img src="https://opencollective.com/eclipse-plugins/sponsor/2/avatar.svg"></a>
<a href="https://opencollective.com/eclipse-plugins/sponsor/3/website" target="_blank"><img src="https://opencollective.com/eclipse-plugins/sponsor/3/avatar.svg"></a>
<a href="https://opencollective.com/eclipse-plugins/sponsor/4/website" target="_blank"><img src="https://opencollective.com/eclipse-plugins/sponsor/4/avatar.svg"></a>
<a href="https://opencollective.com/eclipse-plugins/sponsor/5/website" target="_blank"><img src="https://opencollective.com/eclipse-plugins/sponsor/5/avatar.svg"></a>
<a href="https://opencollective.com/eclipse-plugins/sponsor/6/website" target="_blank"><img src="https://opencollective.com/eclipse-plugins/sponsor/6/avatar.svg"></a>
<a href="https://opencollective.com/eclipse-plugins/sponsor/7/website" target="_blank"><img src="https://opencollective.com/eclipse-plugins/sponsor/7/avatar.svg"></a>
<a href="https://opencollective.com/eclipse-plugins/sponsor/8/website" target="_blank"><img src="https://opencollective.com/eclipse-plugins/sponsor/8/avatar.svg"></a>
<a href="https://opencollective.com/eclipse-plugins/sponsor/9/website" target="_blank"><img src="https://opencollective.com/eclipse-plugins/sponsor/9/avatar.svg"></a>


