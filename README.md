# Debugging Middleware

>> Q1: Basic version of debugging middleware that will print out basic request info: HTTP method, url, and time-stamps.
```
2019-5-17 18:51:12 | GET from /
```

>> Q2: Advanced version which keeps basic info and add further information, time duration of request-response cycle.
```
2019-5-17 18:51:12 | GET from / | total time: 8ms
```

## Installation
The following instructions will get you a copy of the project and all the setting needed to run it on your local machine.


### Prerequisites

- [npm](https://www.npmjs.com/get-npm)
- [Node.js](https://nodejs.org/en/download/)


### Clone

Clone this repository to your local machine

### Setup

**1. Enter the project folder**

```
$ cd middleware-debugs
```

**2. Install npm packages**

```
$ npm install
```

**3. Activate the server**

```
$ npm run dev
```

**4. Find the message for successful activation**

```
> App running on port 3000
```
You may visit the application on browser with the URL: http://localhost:3000

### References
[Time requests in NodeJS/Express](https://stackoverflow.com/questions/18538537/time-requests-in-nodejs-express)


___

## Authors
[Vivian Lo](https://github.com/YunYuLo)
