d7-drupal-runner-example
=====

Minimal vanilla Drupal 7 build set-up for use with Drupal Runner and Robo.

This repository is used in the example file `d7.example.drupal.build.yml`.


## Usage

    cd /path/to/your/webroot/d7.drupal.dev
    git clone git@github.com:pfaocle/d7-drupal-runner-example.git sites/d7
    cd sites/d7/make
    composer install

    # Can use a relative path to the docroot:
    vendor/bin/robo drupal:magic ../../..

    # Or, more sensibly, an absolute path:
    vendor/bin/robo drupal:magic /path/to/your/webroot/d7.drupal.dev
