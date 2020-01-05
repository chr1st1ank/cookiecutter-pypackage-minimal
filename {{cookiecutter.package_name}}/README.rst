{{ cookiecutter.package_name }}
{{ cookiecutter.package_name|count * "~" }}

{% if cookiecutter.readme_pypi_badge -%}
.. image:: https://img.shields.io/pypi/v/{{ cookiecutter.package_name }}.svg
    :target: https://pypi.python.org/pypi/{{ cookiecutter.package_name }}
    :alt: Latest PyPI version
{%- endif %}

{{ cookiecutter.package_description }}

Features
========

Usage
=====

Installation
============

Licence
=======

Contributing
============
Interested in particular changes? Found a bug?
Please read {{ cookiecutter.package_url }}/CONTRIBUTING.md for instructions on how to participate.

Authors
=======

`{{ cookiecutter.package_name }}` was written by {{ cookiecutter.author_name }}.
