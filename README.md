# Note: 

The reason for this fork is upgrading the qpdf version to 8.x.x that has fixed a lot of issues of previous version


# Heroku Buildpack QPDF

This is a Heroku buildpack for using `qpdf` in your project.

The binaries for this pack are fetched from Amazon's Ubuntu packages mirror.

## Usage

Add the buildpack to your application.

```bash
heroku buildpacks:add https://github.com/jamesdphillips/heroku-buildpack-qpdf.git -a my_app
```

You can verify installation by running the following.

```bash
hk run "qpdf --help" -a my_app
```
