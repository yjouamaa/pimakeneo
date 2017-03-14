Akeneo PIM Community Standard Edition
=====================================

Welcome to Akeneo PIM Product.

This repository is used to create a new PIM project based on Akeneo PIM.

If you want to contribute to the Akeneo PIM (and we will be pleased if you do!), you can fork the repository http://www.github.com/akeneo/pim-community-dev and submit a pull request.

| [Master][Master] | [1.6][1.6] | [1.5][1.5] | [1.4][1.4] |
|:----------------:|:----------:|:----------:|:----------:|
| [![Build status][Master image]][Master] | [![Build status][1.6 image]][1.6] | [![Build status][1.5 image]][1.5] | [![Build status][1.4 image]][1.4] |

  [Master image]: https://travis-ci.org/akeneo/pim-community-dev.svg
  [Master]: https://travis-ci.org/akeneo/pim-community-dev/tree/master
  [1.6 image]: https://travis-ci.org/akeneo/pim-community-dev.svg?branch=1.6
  [1.6]: https://github.com/akeneo/pim-community-dev/tree/1.6
  [1.5 image]: https://travis-ci.org/akeneo/pim-community-dev.svg?branch=1.5
  [1.5]: https://github.com/akeneo/pim-community-dev/tree/1.5
  [1.4 image]: https://travis-ci.org/akeneo/pim-community-dev.svg?branch=1.4
  [1.4]: https://github.com/akeneo/pim-community-dev/tree/1.4

[![Scrutinizer Quality Score](https://scrutinizer-ci.com/g/akeneo/pim-community-dev/badges/quality-score.png?s=05ef3d5d2bbfae2f9a659060b21711d275f0c1ff)](https://scrutinizer-ci.com/g/akeneo/pim-community-dev/)

Application Technical Information
---------------------------------

The following documentation is designed for both clients and partners and provides all technical information required to define required server(s) to run Akeneo PIM application and check that end users workstation is compatible with Akeneo PIM application:
http://docs.akeneo.com/1.6/reference/technical_information/index.html

Installation instructions
-------------------------

### Recommended installation

To install Akeneo PIM for a PIM project or for evaluation, please follow: https://docs.akeneo.com/1.6/developer_guide/installation/system_requirements/system_requirements.html

### Using Composer to create the project

Alternatively, you can install Akeneo PIM with Composer, but please make sure that all requirements are fulfilled.

If you don't have Composer yet, download it following the instructions on http://getcomposer.org/ or just run the following command:

```
    $ curl -s https://getcomposer.org/installer | php
```

Please note that you will certainly need to provide your GitHub credentials with this method.
A lot of our dependencies are coming from GitHub and this reaches the max limit of 50 API calls from anonymous users.

```
    $ php composer.phar create-project --prefer-dist akeneo/pim-community-standard ./pim-project "1.6.*@stable"
```

After that, follow the instructions here: https://docs.akeneo.com/1.6/developer_guide/installation/index.html

Upgrade instructions
--------------------

To upgrade Akeneo PIM to a newer version, please follow:
http://docs.akeneo.com/1.6/developer_guide/migration/index.html

