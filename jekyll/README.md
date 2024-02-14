# Apache Website Template

This project contains a template web site that aims to follow all the various required
Apache Website Policies.

This template was generated using [Jekyll](https://jekyllrb.com/).

To use it, copy this directory into your project.  You must also
include licensing information from the `LICENSE` and `NOTICE` files in
your own project.

# How to deploy your project's web site

(In the following instructions we assume that your project is called
'Apache Foo'; search and replace with your actual project name.)

## Setup

```shell
cd site
svn co https://svn.apache.org/repos/asf/foo/site target
sudo apt-get install rubygems ruby2.1-dev zlib1g-dev
sudo gem install bundler github-pages jekyll
bundle install
```

## Add javadoc

If your project supports javadoc, you can copy the generated javadoc
into svn each time you need to re-generate.

```shell
cd ..
mvn -DskipTests site
mv target/site/apidocs site/target
```

## Running locally

Before opening a pull request, you can preview your contributions by
running from within the directory:

```shell
bundle exec jekyll serve
```

You can view the site on http://localhost:4000.

## Pushing to site

```shell
cd site/target
svn status
# You'll need to `svn add` any new files
svn ci
```

Within a few minutes, svnpubsub should kick in and you'll be able to
see the results at [foo.apache.org](https://foo.apache.org/).

## Adding contributors

To add a contributor to the project, or to modify existing contributors,
edit `./_data/contributors.yml`.

The project members (http://localhost:4000/community.html#project-members)
list will re-generate.
