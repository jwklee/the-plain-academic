# The Plain Academic

WORK IN PROGRESS!

[![LICENSE](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE) ![GENERATOR](https://img.shields.io/badge/made_with-jekyll-blue.svg)

- **Demo:** https://brenov.github.io/the-plain-academic/

![SCREENSHOT](img/screenshot.png)

### On GitHub

GitHub - for your user account pages or repository gh-pages - only supports a limited set of themes.

Therefore, you need to use the 'remote\_theme:' setting instead of 'theme:', which is supported by [a 3rd party plugin](https://github.com/benbalter/jekyll-remote-theme).

Put this in your *Gemfile*:

	gem 'jekyll-remote-theme'

and run `bundle install` to install the plugin.

Add the following to your site's *_config.yml* to activate the plugin and to select this theme:

	plugins:
	  - jekyll-remote-theme

	remote_theme: heiswayi/the-plain

This will grab the theme directly from the GitHub repo.

Now copy some of the settings from this repo's *_config.yml* file to your own, and modify them.

## Authors

- [**Heiswayi Nrird**](https://heiswayi.nrird.com)

See also the list of [contributors](https://github.com/heiswayi/the-plain/graphs/contributors) who participated in this project.

## License

[MIT](LICENSE)
