# Check Out Your Favourite Movies!

Featurs Of This App:
  - View Currently Showing movies.
  - Check IMDB rates.
  - Seach Your Favourite Movies.
  - Seach movies of your favourite actors.

### Tech

Dillinger uses a number of open source projects to work properly:

* [Node.js]
* [Jade Template]
* [Express] - Markdown parser done right. Fast and easy to extend.
* [npm] - great UI boilerplate for modern web apps
* [request] - evented I/O for the backend
* [Express] - fast node.js network app framework [@tjholowaychuk]

### Installation

First Grab an api key from 

```sh
https://www.themoviedb.org/documentation/api?language=en-US
```
and replace here 
<img src="https://github.com/lakith/movie-viewer/blob/master/public/images/Capture6.PNG?raw=true" alt ="home page" />

<br/>
API Docs
```sh
https://developers.themoviedb.org/3/getting-started/introduction
```

This requires [Node.js](https://nodejs.org/) v4+ to run.

Install the dependencies and devDependencies and start the server.

```sh
$ cd movie-viewer
$ npm install 
$ npm run start
```

### Docker
Dillinger is very easy to install and deploy in a Docker container.

By default, the Docker will expose port 3000, .

```sh
cd movie-viewer
docker-compose up -d
```

Verify the deployment by navigating to your server address in your preferred browser.

```sh
127.0.0.1:3000
```

### Sample Images 

Home Page
<img src="https://github.com/lakith/movie-viewer/blob/master/public/images/Capture.PNG?raw=true" alt ="home page" />
<br/>

Home Page - Bottom
<img src="https://github.com/lakith/movie-viewer/blob/master/public/images/Capture2.PNG?raw=true" alt ="home page" />
<br/>

View Movie Details
<img src="https://github.com/lakith/movie-viewer/blob/master/public/images/Capture3.PNG?raw=true" alt ="home page" />
<br/>

Search Movies - [Search Term - "Lord Of The Rings"]
<img src="https://github.com/lakith/movie-viewer/blob/master/public/images/Capture4.PNG?raw=true" alt ="home page" />
<br/>

Search Movies Of Actors - [Search Term - "Will Smith"]
<img src="https://github.com/lakith/movie-viewer/blob/master/public/images/Capture5.PNG?raw=true" alt ="home page" />
<br/>

### Todos

 - Write Test Cases

License
----

MIT

**Free Software, Hell Yeah!**
