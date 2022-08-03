```sh
# create a new gem
bundler gem ruby-cli

# build
gem build ruby-cli.gemspec

# install
gem install --user-install  ruby-cli-0.1.0.gem

# check
gem info ruby-cli 

# run
ruby-cli
```