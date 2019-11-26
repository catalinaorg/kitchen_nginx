This repo creates a vagrant virtualbox box (ubuntu 16.04. 06 server), installs nginx and tests if nginx is installed.

# Pre-req

* rbenv install 2.3.1
* rbenv local 2.3.1
* rbenv versions
* gem install bundler
* bundle install

# To create the virtual box:

`packer build template.json`

 # To test if nginx is installed

`bundle exec kitchen converge`

`bundle exec kitchen verify`

