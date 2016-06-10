PlotPDX Front-end App
================

The front-end for the PlotPDX App is a simple jQuery application built using Grunt, a Javascript task runner that uses NodeJS. 

Grunt is configured using a Yeoman configuration called [Generator Web App](https://github.com/yeoman/generator-webapp). Make sure to read the documentation to see how everything works.

## Required installs

* NodeJS (and npm)

* Grunt (run `npm install -g grunt-cli`)

* Bower (run `npm install -g bower`)


## Getting Started

    # Install libraries and dependencies (only need to do this once)
    npm install && bower install

    # Create a BLANK AWS credentials file in the root directory
    echo '{"key": "","secret": "","bucket": ""}' >> aws.json

    # Run app on local web server for development
    grunt serve

    # Build app and deploy to S3 (requires aws.json file with proper credentials)
    grunt build


## Getting Started

...