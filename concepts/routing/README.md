# Routes

## Introduction
A route is the functionality that implement the possibility to distinguish on URL from an another.<br>
Like all web frameworks, Trails route provide the mechanism that map route to controllers.

## About routing mechanics
When someone trying to access to a specific url that is pointing on your app, the request is handled by the routing component.
The routing component parse the request, extract the path and method ,check if this path exist or not and pass the relay to the Controller.

## Configuration

### The common way

```JavaScript
// config/routes.js
module.exports = [
  {
    method: [ 'GET' ],
    path: '/example/test',
    handler: 'ExampleController.test'
  }
]
```
