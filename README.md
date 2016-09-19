# jekyll-simple-theme

custom jekyll theme for [my blog](https://whybe.github.io).

## Installation

Add this line to your Jekyll site's Gemfile:

```ruby
gem "jekyll-simple-theme"
```

And add this line to your Jekyll site:

```yaml
theme: jekyll-simple-theme
```

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install jekyll-simple-theme

## Usage

You might define variables of `site` or `page` to use includes below.

### disqus
 * `page.comments = true`
 * `jekyll.environment = "production"`
 * `site.url or site.github.url`
 * `site.disqus.shortname`

### footer
 * `site.title`, `site.author`, `site.email`, `site.description`
 * `site.github_username`, `site.twitter_username`
 
### google-analytics
 * `site.google_analytics`

### head
 * `site.baseurl`

## Preview

clone this repository:

    $ git clone [THIS REPOSITORY]
    
and then execute:

    $ bundle
    
and then build:

    $ jekyll build -s example -d example/_site
    
and then server:

    $ jekyll serve -s example -d example/_site
    
## License

The theme is available as open source under the terms of the [MIT License](http://opensource.org/licenses/MIT).

