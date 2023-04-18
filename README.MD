## Laravel Sail Command

Documentation Laravel Sail Terminal

### Configuration alias in shell

`alias sail='[ -f sail ] && sh sail || sh vendor/bin/sail'`


### Running Sail

`sail up`


### Running Sail in Background

`sail up -d`

### Shutdown Sail

`sail down`

### Shutdown sail and remove volume

 `sail down -v`


### Build Project

`sail build` or `sail build --no-cache` 

explain sail running dockerfile on docker

### Laravel Command, when sail running in background

`sail [COMMAND]`

example `sail npm run dev` or `sail artisan migrate`, dont running `sail artisan serve` because **sail** has provided the command


### Step installation sail

- sail exist in your project
- configuration alias shell terminal
- running docker daemon
- build project sail
- runninng sail in background
- shutdown sail, if you want stop server

### Ubuntu 18 Save environtment Permanent
`nano ~/bashrc` 

then add text `alias sail='[ -f sail ] && bash sail || bash vendor/bin/sail'`, then save

run environment command `source ~/bashrc`
