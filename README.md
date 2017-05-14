# README

## Getting Started

This is a [Ruby on Rails](http://rubyonrails.org/) app. You can run it using [Docker](https://www.docker.com/), or you can set up the environment yourself.

You'll need the source code first. [Fork this repository](https://github.com/local-first-boston/local-first/fork) and then hit the big green "Clone or download" button for instructions to clone the repository.

After cloning, run `cd local-first` to enter the cloned repository.

### With Docker

Once you have Docker installed and running, run `docker-compose build` to build the images necessary to run the app. Once this is complete, run `docker-compose up` to start the app.

If you need to run commands (e.g., Rake tasks) in the containers, you can run them like `docker-compose run web rake db:create`.

### Without Docker

You'll need Ruby 2.3.3. [RVM](https://rvm.io/) is useful for managing multiple Ruby installations. You'll also need [PostgreSQL](https://www.postgresql.org/).

Run `gem install bundler` to get the [Bundler](http://bundler.io/) gem, then run `bundle install` to get all the gems this app depends on.

Now run `bundle exec rails s -p 3000 -b '0.0.0.0'` to start the app. You'll need to start up Postgres as well.

## Testing

TODO

## Deploying

TODO
