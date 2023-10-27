# assesment5_jubelio (Comparison)

Ruby (Make sure you already installed ruby. To check installed ruby you can using this command $rvm list)
Cucumber (Make sure you already installed cucumber. To check you can using this command $cucumber --version)
Add this to Gemfile

source 'https://rubygems.org'

gem 'capybara'
gem 'cucumber'
gem 'pry'
gem 'rspec'
gem 'webdrivers'

Run this command to install gem bundle install
Add env file like this features/support/env.rb
Run this command to install cucumber --init
Editor (Visual Studio Code)
Install Cucumber extension in text editor

How to run this automation scenarios in local
Clone this repo using this command:
$ git clone https://github.com/iqbalridwan/assesment5_jubelio.git

Open this repo in your editor
Open terminal in your editor
To run all scenario can using this command:
$ cucumber

To run specific/several scenario can using run with tags like this:
$ bundle exec cucumber -t @login
