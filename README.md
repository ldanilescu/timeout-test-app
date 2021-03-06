
This project is an AngularJS web application. 


## Getting Started

To get you started you can simply download the source code or clone the `timeout-test-app` repository and then install the dependencies :

### Prerequisites

We also use a number of Node.js tools to initialize and start `timeout-test-app`. You must have Node.js
and its package manager (npm) installed. You can get them from [here](https://nodejs.org/en/).

### Install Dependencies

We have two kinds of dependencies in this project: tools and Angular framework code. The tools help
us manage the application.

* We get the tools we depend upon via `npm`, the [Node package manager](https://www.npmjs.com/).
* We get the Angular code via `bower`, a [client-side code package manager](https://bower.io/).

`npm` is preconfigured to automatically run `bower` so you can simply do:

```
cd timeout-test-app
npm install
```

Behind the scenes this will also call `bower install`. After that, you should find out that you have
two new folders in your project.

* `node_modules` - contains the npm packages for the tools we need
* `app/bower_components` - contains the Angular framework files

*Note that the `bower_components` folder would normally be installed in the root folder but
`timeout-app` changes this location through the `.bowerrc` file. Putting it in the `app` folder
makes it easier to serve the files by a web server.*

### Run the Application

The project is preconfigured with a simple development web server. The simplest way to start
this server is:

```
npm start
```

Now browse to the app at `localhost:8000`.





