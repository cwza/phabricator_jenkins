``` sh
cd phabricator
docker build -t phabricator .
cd jenkins
docker build -t meepshop_jenkins .
cd uberalls
docker build -t uberalls .
cd phabricator_jenkins
docker-compose up
```