# Production Replay Demo App

![](public/demo.png)

## Instructions
 - Run this app using `node index.js 8000`
 - Run another instance of the app on a different port using `node index.js 8001`
 - Install GoReplay locally by following [these simple Instructions](https://github.com/buger/goreplay/wiki/Getting-Started#installing-gor)
 - Replay traffic from the first instance of the app to the second one using GoReplay: `sudo ./gor --input-raw :8000 --output-http http://localhost:8001`
