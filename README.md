# owenniles.github.io

## Local development

**Prerequisites:** [rbenv](https://github.com/rbenv/rbenv) and [ruby-build](https://github.com/rbenv/ruby-build)

```bash
# Install the pinned Ruby version
rbenv install

# Install dependencies
gem install bundler
bundle install

# Serve the site locally at http://localhost:4000
bundle exec jekyll serve
```
