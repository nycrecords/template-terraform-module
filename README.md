Cookiecutter - Terraform Module
===============================

This is a cookiecutter template for creating Terraform modules for use at the NYC Department of Records.

Usage
-----

Install [Cookiecutter](https://cookiecutter.readthedocs.io/en/1.7.2/) using [pipx](https://pipxproject.github.io/pipx/)

```shell
    pipx install cookiecutter
```

Create a new project directly from the template on:

```shell
    cookiecutter gh:nycrecords/template-terraform-module
```

Parameters
----------

- **author_name** The name of the author (Default is `NYCRecords AppDev`)
- **author_email** The name of the author (Default is `appdev@records.nyc.gov`)
- **author_url** The url to your Github account (Default is `https://github.com/nycrecords`)
- **module_name** The name of your module.
- **provider** The Terraform provider this module is for (Default is `azurerm`)
