## Laravel Sail Command

Documentation Laravel Sail Terminal

## Configuration alias in shell

`alias sail='[ -f sail ] && sh sail || sh vendor/bin/sail'`


## Running Sail

`sail up`


## Running Sail in Background

`sail up -d`

## Shutdown Sail

`sail down`


## Build Project

`sail build`

explain sail running dockerfile on docker

## Laravel Command, when sail running in background

`sail [COMMAND]`

example `sail npm run dev` or `sail artisan migrate`, dont running `sail artisan serve` because **sail** has provided the command


## Step installation sail

- sail exist in your project
- configuration alias shell terminal
- running docker daemon
- build project sail
- runninng sail in background
- shutdown sail, if you want stop server
