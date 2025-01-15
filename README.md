# Laravel-hub

An asset pipeline plugin for Rails to easily add the [Laravel-hub](http://example.com/)
icon font faces and an initial set of icon classes.

## Laravel-hub Credits

The Laravel-hub pictograms by data are provided in `vendor`. 
These are licensed under CC BY 3.0 and SIL Open Font License.

## Installation

Add this line to your application's Gemfile:

    gem 'laravel-hub'

And then execute:

    $ bundle

Then start your server and open

    http://localhost:3000/laravel-hub/charmap

## Usage

Either use the provided mappings:

```scss
// application.css
//= require laravel-hub
@charset "UTF-8";
```

```html
<!-- template.html -->
This is cool <i class="icon-thumbs-up"></i>.
Fork it on <i class="icon-dispatchers"></i>.
```

## Options

#### Change the `icon` prefix

Create `config/initializers/laravel-hub.rb`:

```ruby
Laravel-hub.css_prefix = "my-icon"
```

## Troubleshooting

**Fonts not loading in production?**

Ensure correct RAILS_ENV when compiling:

```bash
RAILS_ENV=production rake assets:precompile
```

## Contributing

1. Fork it
2. Create feature branch
3. Commit changes
4. Push to branch
5. Create Pull Request


# PR Merge: 2025-10-29 13:21:10
