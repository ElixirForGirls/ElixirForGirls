# elixirforgirls.github.io
Static Site for [ElixirGirls Stockholm](https://elixirforgirls.github.io)

## Running the app in development

### install
This site is built using GitHub pages
- requires [Ruby 2.x and bundler](https://help.github.com/articles/setting-up-your-github-pages-site-locally-with-jekyll/#requirements)
- Clone this repo from GitHub
- Ensure you have the `jekyll` gem available to you.
- Inside the `elixirforgirls.github.io` directory:

    `bundle install`

### Running the site locally
- `bundle exec jekyll serve`

### Publish website

First you need to update the `GITHUB_REPONAME` variable in the `/Rakefile`
file. If you have a project GH Page you need to define the `baseurl` as
your project name and set `url` as empty in `_config.yml`.

- Organization/User GH Page
  - `rake org:publish`

- Project GH Page
  - `rake project:publish`
