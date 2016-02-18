# Jekyll/Travis/gh-pages [![Build Status](https://travis-ci.org/timwis/jekyll-travis-gh-pages.svg?branch=master)](https://travis-ci.org/timwis/jekyll-travis-gh-pages)
Deploy jekyll sites to gh-pages with plugins, etc. using Travis CI

## Usage
- Make sure your external plugins are included in the Gemfile/Gemfile.lock
- Make sure `vendor` is in the `exclude` section of your [`_config.yml`](_config.yml) 
- Add the [`.travis.yml`](.travis.yml) file and [`deploy.sh`](deploy.sh) files included in this repo
- Add a `GITHUB_URL` environment variable to this repo from your travis-ci.org dashboard

Get your token from [github account settings](https://github.com/settings/tokens).
`https://<personal-access-token>@github.com/username/repo.git`
