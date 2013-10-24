# RSpec & Capybara demo

This demo shows how to use RSpec & Capybara to test a standalone website (Google.co.uk in this case).

## Prerequisites

You need Ruby 2.0, rubygems and the bundler gem installed. It's recommended to use RVM. Installation instructions for RVM can be googled.

Once you've got RVM, install ruby like so:

```bash
rvm install 2.0.0
```

Now switch your system to use Ruby 2.0.0:

```bash
rvm use 2.0.0 --default
```

Now install bundler gem:

```bash
gem install bundler
```

## Setup

Then download this code from github:

```bash
git clone https://github.com/originalpete/rspec-capybara-demo.git
```

Install the bundle:

```bash
bundle install --path=vendor
```

## Run the tests

To run the test suite, all you need to do is:
```bash
bundle exec rspec
```
