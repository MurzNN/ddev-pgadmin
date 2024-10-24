[![tests](https://github.com/MurzNN/ddev-pgadmin/actions/workflows/tests.yml/badge.svg)](https://github.com/MurzNN/ddev-pgadmin/actions/workflows/tests.yml) ![project is maintained](https://img.shields.io/maintenance/yes/2024.svg)

# ddev-pgadmin <!-- omit in toc -->

* [What is ddev-pgadmin?](#what-is-ddev-pgadmin)

## What is ddev-pgadmin?

This add-on provides a pgAdmin service for [DDEV](https://github.com/ddev/ddev/).

Installation:

For DDEV v1.23.5 or above run

```sh
ddev add-on get MurzNN/ddev-pgadmin
```

For earlier versions of DDEV run

```sh
ddev get MurzNN/ddev-pgadmin
```

Then restart your project

```sh
ddev restart
```

You can run pgAdmin easily with the command after installing this add-on:

```sh
ddev pgadmin
```

Also, it will be available on the url `https://pgadmin.yourprojectname.ddev.site`. If it asks for the database password, enter `db` there.

> [!TIP]
> For Gitpod: The `ddev pgadmin` command can open a blank page in preview mode, open the link in a new browser tab/window to make it work.

**Contributed and maintained by [@MurzNN](https://github.com/MurzNN)**
