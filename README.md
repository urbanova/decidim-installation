# Decidim Installation Guide for AWS (WIP)

## Implementation Architecture Overview

## Environment Setup

### AWS

#### User Accounts & Programmatic Access
#### Elastic Beanstalk (EBS)
#### AWS CodeCommit

### Local DEV Environment

```
brew update
brew install rbenv ruby-build

# Add rbenv to bash so that it loads every time you open a terminal
echo 'if which rbenv > /dev/null; then eval "$(rbenv init -)"; fi' >> ~/.bash_profile
source ~/.bash_profile

# Install Ruby
rbenv install 2.6.3
rbenv global 2.6.3
ruby -v
```

## Configuration
