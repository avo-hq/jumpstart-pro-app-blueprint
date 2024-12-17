# Avo 3 to Jumpstart Pro template

See more at: [avohq.io/blueprints](https://avohq.io/blueprints)

## Happening

1. Add to the `Gemfile`. Possibly to show a choice for `avo`, `pro` or `advanced`. `gem "avo", ">= 3.1"`
1. Run `bundle install`
1. Add the route `mount Avo::Engine, at: Avo.configuration.root_path`
1. Copy the `template` files

Related PR to JSP that contains a few more changes that JSP apps need to accomodate Avo.

https://github.com/jumpstart-pro/jumpstart-pro-rails/pull/749/files
