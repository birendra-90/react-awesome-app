# React awesome app

Full stack app example with redis, docker, node.js, YEPS, react, redux, rxjs with redux-observable.

Quality tools: eslint, mocha, chai, sinon, enzyme.

## How to install

    git clone https://github.com/evheniy/react-awesome-app.git
    cd react-awesome-app
    npm i
    
## How to run databases with docker

Start (redis:6379):
    
    npm run db:start
    
Stop:

    npm run db:stop
    
## How to run server 

### Node.js

Start ([http://localhost:3000/](http://localhost:3000/)):

    npm run server:start
    
Stop:

    npm run server:stop
    
### Docker

Build:

    npm run docker:build
    
Run ([http://localhost/](http://localhost/)):

    npm run docker:run

Stop:

    npm run docker:stop
    
### Docker Compose

Run ([https://localhost/](https://localhost/)):

    npm run compose:up
    
Stop:

    npm run compose:down

Clear:

    npm run compose:clear
    
### URLs to test

| Method | Action     | URL                                              |
|--------|------------|--------------------------------------------------|
|  GET   | Index page | [http://localhost/](http://localhost/)           |
|  GET   | Get data   | [http://localhost/data](http://localhost/data)   |
|  POST  | Set data   | [http://localhost/data](http://localhost/data)   |
|  GET   | 500 error  | [http://localhost/error](http://localhost/error) |
|  GET   | 404 error  | [http://localhost/404](http://localhost/404)     |


## How to test

    npm t
