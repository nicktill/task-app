## Simple task-app utilizing json backend 
We are essentially using the json as a backend infrastructure similar to ways that node, django, or other frameworks so that we can make API
requests to it using post,get,delete etc

https://www.npmjs.com/package/json-server 
# How to Build?


### Install dependencies

```
npm install
```

### Run the JSON server (http://localhost:3001) 
## NOTE: We initially ran our dev container on http://localhost:5000 (THIS DOES NOT WORK ON MAC AS THAT PORT IS RESERVED FOR MAC OS)
Therefore simply run the database using our localhost:3001 address

```
npm run server
```

## Now that the json server is built we can now run our dev container 

```
npm start 
```

Navigate to http://localhost:3000 and should be fully funcitoning if NPM packages were correctly installed
