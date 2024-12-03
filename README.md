# GenoRing Template

Defines composer scaffold to install GenoRing Drupal distribution.


## Table of contents

- Description
- Installation
- Authors and acknowledgment
- License


## Description

This is a composer based installer for the GenoRing Drupal distribution. It is
used by the GenoRing platform to install itself. It should not be used to
install the GenoRing platform and is reserved to experts with special needs.
To install GenoRing platform, use a GenoRing platform release instead available
on [genoring.net](http://www.genoring.net).


## Installation

To install GenoRing Drupal distribution into the directory "PROJECT_DIRECTORY",
use the following command:
  ```
  composer create-project --no-interaction --no-install "guignonv/genoring_template" PROJECT_DIRECTORY
  ```
Note: this is not required to install GenoRing platform as the platform handles
this template by itself.


## Authors and acknowledgment

* Valentin GUIGNON, The Alliance Bioveristy - CIAT (CGIAR), v.guignon@cgiar.org

### Contributing

SouthGreen Platform
  * CIRAD
  * IRD
  * INRAE
  * The Alliance Bioversity - CIAT


## License

This project is licensed under the MIT License. See LICENSE file for details.
