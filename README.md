# Rest api testing with codeception
Sample project that shows how to test rest api with codeception

# setup codeception

    docker run -it -v $PWD:/app -w /app composer:1.7 require "codeception/codeception" --dev
    docker run -it -v $PWD:/app -w /app php:7.2-alpine ./vendor/bin/codecept init api
    > Let's prepare Codeception for REST API testing
    >
    > ? Where tests will be stored? (tests) tests/api
    > ? Start url for tests (http://localhost/api) http://localhost


      