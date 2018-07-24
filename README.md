# Vue on Django Site

[Go to the Site.](https://vue-on-django.com)

This site is a collection of different articles about Vue, Django, and how they connect and interact.

## Contributing

I'm open to contributions!  Open up a pull request or an issue and share what you'd like to contribute.

## Local Development

This project is built on top of Jekyll because I love Jekyll and am really productive in it.  Would it have been slick to make the site with Vue and Django?  Probably.  But it's a side project and I wanted to have a little friction as possible to writing.  So there we are.

1. First, clone the repo.

    git clone https://github.com/rpalo/vue-on-django-site.git

2. Move into the root directory.

    cd vue-on-django-site

3. Install the dependencies.  This step requires that you have Ruby, Rubygems, and Bundler installed.

    bundle install

4. Start the local dev site.

    bundle exec jekyll serve

The site source is located in the `src` directory.  All of the configuration is in [_config.yml](./_config.yml).  Individual tutorials live in the [tutorials directory](./src/_tutorials/).

## Code of Conduct

This project has a Code of Conduct, because we're not barbarians.  See the [Code of Conduct](./CODE_OF_CONDUCT.md).