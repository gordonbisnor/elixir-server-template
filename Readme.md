# Elixir Server Template

## Overview

This is a template chef structure for deploying Elixir applications based off of TalkingQuickly/rails-server-template. 

## Requirements

Should work on Ubuntu 14.04

## Usage

```bash
cd data_bags/users && cp deploy.json.example deploy.json
ssh-copy-id -i ~/.ssh/yourKey root@xx.xx.xx.xxx
bundle exec knife solo prepare root@xx.xx.xx.xxx
bundle exec knife solo cook root@xx.xx.xx.xxx
```