# vue-selenium-docker
test vue into docker container

## Unit Test

    $ docker-compose -f docker/test/js/docker-compose-js-unit.yml build
    $ docker-compose -f docker/test/js/docker-compose-js-e2e.yml up --exit-code-from unit

## E2E Test (WIP) 

    $ docker-compose -f docker/test/js/docker-compose-js-e2e.yml build
    $ docker-compose -f docker/test/js/docker-compose-js-e2e.yml up  --exit-code-from e2e

