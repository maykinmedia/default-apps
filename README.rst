============
Default apps
============

This repository contains boilerplate apps that are often re-used between
projects (with little tweaking).

After initializing a project with the ``default-project`` template, you can
download an archive of this repository (or check it out locally with git) and
take out the apps to bootstrap a new project.

Description of the included apps
================================

accounts
--------

Essentially the same as the ``AbstractUser`` from
``django.contrib.auth.models``, but ready to modify/extend to your needs.

Includes a couple of basic tests for the ``UserManager``, Django admin
registration and ``AppConfig`` definition.

Non-app-related bits
====================

templates
---------

Currently empty, but will soon include a default, BEM-ready ``django-sniplates``
form widgets library.
