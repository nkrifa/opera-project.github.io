# Documentation for opera project

Opéra project is a simple cms that use symfony4 and community bundles to help u build beautiful pages based on contents and blocks layout

## The core bundles

- OperaCoreBundle : The main bundle to build pages mechanism
- OperaAdminBundle : The admin based on easy admin
- OperaTextBlockBundle : The first block

## How to setup

TODO for the moment u can clone the sample https://github.com/opera-project/opera-cms

## How to create a new kind of block

Run the symfony command : `bin/console make:block sample` (write name of block in lower case)

This will generate the service block
And the twig template sample 
