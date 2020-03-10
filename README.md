# sam-typescript-template

## Project setup
```
cd hello-world
npm install
```

### Local compile
```
sh ./build.sh
```

### SAM Build
```
./build.sh && sam build
```

### Invoke function locally
```
sam local invoke "HelloWorldFunction" -e events/event.json
```

### Start API
```
sam local start-api
```
