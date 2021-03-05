AR Coding Style
===============

A set of coding style used by Adriano Rosa.

EditorConfig
============

The default styles is located within the file `.editorconfig` that should be copied into the project root.


PHP
===

## CodeStyle using PHP_CodeSniffer the `phpcs`


First install CodeSniffer globally using composer:

    composer global require "squizlabs/php_codesniffer=*"

> Note: composer should be within your $PATH.

Check the version of installed script:

		phpcs --version
		phpcbf --version

Place the `phpcs.xml` within the project root directory.

To check a possible code style issue:
 
    phpcs 

To fix a possible code style issue:

    phpcbf


## Author

**Adriano Rosa** (https://adrianorosa.com)  

## Licence

Copyright © 2021, Adriano Rosa  <info@adrianorosa.com>
All rights reserved.

For the full copyright and license information, please view the LICENSE 
file that was distributed within the source root of this project.
