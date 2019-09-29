# normalsalt.github.io

https://normalsalt.github.io/

### Gemfile

```
source 'https://rubygems.org'
gem 'github-pages', group: :jekyll_plugins
```

### Template

    $ bundle install
    $ bundle exec jekyll new jekyll-template
    $ cd jekyll-template/
    $ bundle exec jekyll serve

Now browse to http://localhost:4000.

### GitHub Pages

Edit your Gemfile and remove the following line:

```
gem "jekyll", "~> 3.8.5"
```

In the Gemfile, delete the `#` at the beginning of this line:

```
gem "github-pages", group: :jekyll_plugins
```
