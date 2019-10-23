# Enforcing Coding Standards with PHP_CodeSniffer - Code Examples



Code examples to go along with Sal Ferrarello's [Enforcing Coding Standards with PHP_CodeSniffer](https://salferrarello.com/slides/php-code-sniffing/) talk.

## Running PHPCS

### Install PHPCS

From the command line in the root of this project, run

```
composer install
```

If you don't have Composer installed, see [instructions on downloading Composer](https://getcomposer.org/download/).

### Run PHPCS

From the command line in the root of this project, run

```
./vendor/bin/phpcs
```

**Note** All PHPCS configuration is done via the `.phpcs.xml.dist` file in the root of this project.


## .editorconfig

This file also makes use of an `.editorconfig`, see [editorconfig.org](https://editorconfig.org/) for more information and editor plugins to install for functionality.
