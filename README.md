# Bunto Tutorial
> You want to use Bunto? Try the Bunto lessons for developers and hosters.

Feedback and suggestions are _greatly_ welcome!


### Markdown Flavor

Since this is intended to be a tutorial for new users of Bunto, I decided to just
focus on the original specifics.


### Running Locally

After cloning the project, you need to run:
```shell
# Grabs the dependencies
bundle install

# Builds and serves the site with Bunto...
bunto serve

# ... or builds and serves the site with Jekyll
jekyll serve
```

Download only the gems without installing:
```shell
# Enter vendor/cache folder
cd vendor/cache

# Download only the gems without installing
gem fetch bunto -v 1.0.0
```

Et voilà!


### Tech Stack

* [Bunto](https://bunto.github.io) for templating the site and compiling assets
* [Bootstrap](http://twitter.github.io/bootstrap/) for the design
* [Font Awesome](https://github.com/FortAwesome/Font-Awesome) for the awesome fonts
