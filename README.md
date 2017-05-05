# README

[ ![Codeship Status for betogrun/currency_converter](https://app.codeship.com/projects/3db7b8f0-11dd-0135-994f-22e72ba4c995/status?branch=master)](https://app.codeship.com/projects/216828)

Simple and easy to use app to performs currency conversions.

![Screenshot](http://res.cloudinary.com/betogrun/image/upload/v1493958057/currency_converter2_mxm6d7.png)

## Ruby version

Running on 2.3.3. But it is probably that it runs on >= 1.9

## System dependencies

Any *nix platform.

## Setup

Run
```
docker-compose build
docker-compose up
```

## How to run the test suite
```
docker-compose run --rm website rspec spec/
```
