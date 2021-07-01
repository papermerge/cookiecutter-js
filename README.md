# Cookiecutter for Papermerge's NPM packages

Papermerge frontend is split into many [npm](https://www.npmjs.com/) packages
(for example [commander-js]
(https://www.npmjs.com/package/@papermerge/commander)).

Each of those packages is an independent reusable project with its own test
suite, playgroun and documentation. Even though each of those packages is a
standard nodejs package, they have some papermerge specific structure - like
use of webpack, symposium dependency, flask based playground.

At the time of writing this README file, there are already 6 packages and
number is growing - which means it is right time speed up the time spent
creating new npm package.

[Cookiecutter](https://cookiecutter.readthedocs.io/) template is used to
bootstrap creation of new papermerge npm packages (again - all of which share
same structure).

## Usage

First of all make sure you have python interpreter installed. Once you are
sure you have python up and running, install [cookiecutter]
(https://cookiecutter.readthedocs.io/) package.

Create npm package from template hosted on github::

    $ cookiecutter https://github.com/papermerge/cookiecutter-js

Above command will ask you for project name, initial version, author etc
and then in a fraction of second - voila! - you are ready rock!