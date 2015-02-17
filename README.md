## Sensu-Plugins-ponymailer

[![Build Status](https://travis-ci.org/sensu-plugins/sensu-plugins-ponymailer.svg?branch=master)](https://travis-ci.org/sensu-plugins/sensu-plugins-ponymailer)
[![Gem Version](https://badge.fury.io/rb/sensu-plugins-ponymailer.svg)](http://badge.fury.io/rb/sensu-plugins-ponymailer)
[![Code Climate](https://codeclimate.com/github/sensu-plugins/sensu-plugins-ponymailer/badges/gpa.svg)](https://codeclimate.com/github/sensu-plugins/sensu-plugins-ponymailer)
[![Test Coverage](https://codeclimate.com/github/sensu-plugins/sensu-plugins-ponymailer/badges/coverage.svg)](https://codeclimate.com/github/sensu-plugins/sensu-plugins-ponymailer)
[![Dependency Status](https://gemnasium.com/sensu-plugins/sensu-plugins-ponymailer.svg)](https://gemnasium.com/sensu-plugins/sensu-plugins-ponymailer)

## Functionality

## Files
 *
 *
 *
 *

## Usage

**handler-ponymailer**
```
{
  "ponymailer": {
    "authenticate":true,
    "username":"ops@example.com",
    "tls":true,
    "port":"587",
    "fromname":"Operations",
    "hostname":"mail.example.com",
    "password":"example",
    "from":"ops@example.com",
    "recipients":[
      "sysadmin@example.com"
    ]
  }
}
```
## Installation

Add the public key (if you haven’t already) as a trusted certificate

```
gem cert --add <(curl -Ls https://raw.githubusercontent.com/sensu-plugins/sensu-plugins.github.io/master/certs/sensu-plugins.pem)
gem install sensu-plugins-ponymailer -P MediumSecurity
```

You can also download the key from /certs/ within each repository.

#### Rubygems

`gem install sensu-plugins-ponymailer`

#### Bundler

Add *sensu-plugins-disk-checks* to your Gemfile and run `bundle install` or `bundle update`

#### Chef

Using the Sensu **sensu_gem** LWRP
```
sensu_gem 'sensu-plugins-ponymailer' do
  options('--prerelease')
  version '0.0.1'
end
```

Using the Chef **gem_package** resource
```
gem_package 'sensu-plugins-ponymailer' do
  options('--prerelease')
  version '0.0.1'
end
```

## Notes
