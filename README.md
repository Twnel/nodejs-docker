# nodejs-docker

Nodejs docker container used for microservices deployment using CircleCI to GCP/AWS. This repository 
contains the  sources for the following [docker](https://docker.io) base images:

- [`gcr.io/google_appengine/nodejs`](/base)

## Getting Started

```
git clone git@github.com:Twnel/nodejs-docker.git
git fetch -a
git checkout lts
```

### Prerequisites

- Docker

### Installing

```
cd base/
docker build -t twnel/nodejs-docker:lts .
```

## Deployment

Read Twnel microservices Dockerfiles

## Built With

* [Docker](https://www.docker.com/) - Container Engine

## Contributing

You are always welcome to share your commits and features!

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see project tags.

## Authors

Jonathan Valencia

## License

Twnel License

## Acknowledgments

* For the good days in Cambridge, MA
