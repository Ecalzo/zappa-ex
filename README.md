# Zappa Example
## Getting Started
requires pipenv and that you have a `~/.aws/credentials` file

`pipenv install flask zappa`

`zappa deploy dev`

## Automating Deployment
This repo now includes a handy circleci config file used for automatically deploying pushes to the master branch of this repo.
