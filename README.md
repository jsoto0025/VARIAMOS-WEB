# variamos-web

## Project setup
```
npm install
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
npm run test:unit
```

### Lints and fixes files
```
npm run lint
```
### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).
## Using Variamos-Web with Docker
### Create Variamos-Web image from Dockerfile
```
    docker build -t variamos-web .
```
### Run Variamos-Web container locally
```
    docker run -p 8081:80  --name variamos-web01 variamos-web
```
### Stop container
```
    docker stop variamos-web01
```
### Remove container
```
    docker rm variamos-web01
```
### Start container
```
    docker start variamos-web01
```

