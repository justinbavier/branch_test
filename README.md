# Heroku-MEAN-App

This repository is mean to quick start development and deployment using Heroku and the MEAN stack.
It is based on the mean-contactlist from Heroku's tutorial.

## Getting Started



### Prerequisites
```
install node,
install mongodb,
install heroku cli,
install git cli
```

```
$ npm install
```

### Development


```
$ heroku login
$ mongod
$ heroku local web
```
App running at localhost://5000

### Windows Development


Run mongod.exe
```
@echo off
"C:\Program Files\MongoDB\Server\3.4\bin\mongod.exe" --dbpath "C:\Users\userName\app-directory\data\db"
```
Open a new Command Line
```
$ heroku login
$ heroku local web
```
App running at localhost://5000

### Deployment

```
$ heroku create
$ heroku addons:create mongolab
$ git add --all
$ git commit -m"initial commit"
$ git push heroku master
$ heroku open
```

## Running the tests

Explain how to run the automated tests for this system

### Break down into end to end tests

Explain what these tests test and why

```
Give an example
```

### And coding style tests

Explain what these tests test and why

```
Give an example
```

### api example

localhost:5000/api/contacts

## Built With

* node.js
* heroku
* npm
* MEAN stack

## Contributing

For details on our code of conduct, and the process for submitting pull requests to us.

## Versioning


## Authors


## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* based on this mean app tutorial from heroku https://devcenter.heroku.com/articles/mean-apps-restful-api
*
*
