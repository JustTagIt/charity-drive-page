# charity-drive-page

## Project setup
You will need node.js for development. The recommended version is the latest 10.x release. A `.nvmrc` file has been included for use with [nvm] (https://github .com/creationix/nvm)
```
npm install
npm install -g @vue/cli # for vue cli - note that this is NOT the same as vue-cli, it is a newer version

# You may also need some packages, the installation of which will vary
# for different systems. The lines below got me up on WSL Ubuntu.
sudo apt-get install libglu1
sudo apt-get install libxi6 libgconf-2-4
ldconfig
```

### Vue cli
This project uses vue cli. To launch a web front end:
```
vue ui
```

### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### Run your tests
```
npm run test
```

### Lints and fixes files
```
npm run lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).
