## Sensu-Plugins-ponymailer

[ ![Build Status](https://travis-ci.org/sensu-plugins/sensu-plugins-ponymailer.svg?branch=master)](https://travis-ci.org/sensu-plugins/sensu-plugins-ponymailer)
[![Gem Version](https://badge.fury.io/rb/sensu-plugins-ponymailer.svg)](http://badge.fury.io/rb/sensu-plugins-ponymailer)
[![Code Climate](https://codeclimate.com/github/sensu-plugins/sensu-plugins-ponymailer/badges/gpa.svg)](https://codeclimate.com/github/sensu-plugins/sensu-plugins-ponymailer)
[![Test Coverage](https://codeclimate.com/github/sensu-plugins/sensu-plugins-ponymailer/badges/coverage.svg)](https://codeclimate.com/github/sensu-plugins/sensu-plugins-ponymailer)
[![Dependency Status](https://gemnasium.com/sensu-plugins/sensu-plugins-ponymailer.svg)](https://gemnasium.com/sensu-plugins/sensu-plugins-ponymailer)

## Functionality

## Files
 * handler-ponymailer.rb

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

[Installation and Setup](http://sensu-plugins.io/docs/installation_instructions.html)


## Notes
