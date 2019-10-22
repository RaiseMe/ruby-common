# RaiseMe::Common

This gem holds common configurations for Ruby projects at RaiseMe.

## Installation

Add this line to your application's Gemfile:

```ruby
gem 'ruby-common', git: 'git@github.com:RaiseMe/ruby-common.git', branch: 'master'
```

And then execute:

    $ bundle install

## Usage

Include this gem in `.rubocop.yml` to inherit the common configuration:

```yml
inherit_gem:
  ruby-common: .rubocop-hound.yml
```
