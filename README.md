# Webpage

## Development

This tutorial will get you running the web app from inside a container. Running code from inside a container, rather than just from your computer, will ensure that if the code works on your computer, it will work anywhere (as long as it's run inside the same container). When it comes to developing, you'll still be writing code inside some place on your computer, so nothing else will change.

### Prerequisites

* Git
* Docker

### Instructions

1. Clone the repo onto your local computer. 

``` shell
$ git clone https://github.com/JayZ2398/webpage.git
```

2. `cd` into the project directory.

3. Build the container.

``` shell
$ docker-compose build
```

4. Run the container.

``` shell
$ docker-compose up
```

5. Wait a minute, and the shell should spit out some stuff including:

``` shell
react-ui    | You can now view app in the browser.
react-ui    |
react-ui    |   Local: http://localhost:3000
```

6. In your browser, open http://localhost:3000. You should see your running React app.
