# Rails Server Template

## Overview

This is a template chef structure for deploying Rails applications. The example template and Vagrantfile provide a single VM configuration which works out of the box and can be used to deploy any Rails 3.x or 4.x application. It's most suitable as a drop in Heroku replacement for low traffic apps.

The configuration is also flexible enough to be adapted to multi machine setups.

## Documentation

ssh-copy-id -i ~/.ssh/gordonKey root@45.56.99.200
bundle exec knife solo prepare root@45.56.99.200
bundle exec knife solo cook root@45.56.99.200