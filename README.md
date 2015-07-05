# Parrot IP
A lightweight Express app that echoes back the request IP.

## Format Options
### JSON (/)
[http://ip.quotaguard.com](http://ip.quotaguard.com)

    $ curl http://ip.quotaguard.com
    {"ip":"82.13.87.243"}

### Text (/plain)
[http://ip.quotaguard.com/plain](http://ip.quotaguard.com/plain)

    $ curl http://ip.quotaguard.com/plain
    82.13.87.243

## Running Locally

Make sure you have [Node.js](http://nodejs.org/) installed.

```sh
$ git clone git@github.com:teachmatic/parrotip.git # or clone your own fork
$ cd parrotip
$ npm install
$ npm start
```

Your app should now be running on [localhost:5000](http://localhost:5000/).