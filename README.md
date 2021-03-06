Ludus Bootstrap Theme
========================

![dependency overview](https://david-dm.org/antjanus/ludus-bootstrap-theme.png)

![logo](https://raw.github.com/AntJanus/ludus-bootstrap-theme/master/images/logo-black.png)

Installation
===================

Install the dependencies for running the various tasks to prebuild the environment:

* bower
* grunt / grunt-cli (thus Node)
* jekyll

Run `bower install`, `npm install`, and run `grunt build` to install bootstrap and compile your less files.

To start working on a project and enjoying live reload or other similar tasks, run `grunt work`.

Structure
====================

* _includes - files for Jekyll (documentation)
* _layouts - layouts for Jekyll (documentation)
* dist - distribution, final files
* docs-assets - assets for documentation
* images - images
* js - js that gets compiled into dist
* less - less files that get compiled into dist
* templates - templates for bootstrap theme
* \_gh\_pages (part of build process) - Jekyll compiled docs
* bower_components (part of install process) - installed components
* node_modules (part of install process) - grunt + other npm modules meant to build/install everything

The project features two types of bootstrap theme previews. One of them is via the docs.

Basically, the bootstrap docs include ALL of the elements and how they look and how they are to be used. This is a great place to preview separate elements and how they interact. From buttons to tables. Note that extra styles are applied to properly "sandbox" the bootstrap theme in the docs. It's what prevents navigation previews from overlapping the docs navigation and from other elements doing all kinds of weird things.

The templates folder includes specific templates you want the bootstrap theme to use and thus you can preview locally (and via github.io if you use github) how your theme will look outside of docs.

Log
==================
