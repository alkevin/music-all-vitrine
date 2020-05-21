# music-all-vitrine

Front End web site vitrine for Project Music'All - projet annuel IPSSI 2020

The application is about creating a landing page only for customers to wait for the social network dedicated to musicians Music'All which provided social space service to offert them the possibility to increase visibility and help them to manage an hobbie or professionnal carrier and organize event and meet people who maybe are searching for other people to work on or play a song.

This project was generated with [Spring Initializr](https://start.spring.io/)

------
>Please note that this project is released with a Contributor [Code of Conduct](https://github.com/alkevin/music-all-vitrine/blob/master/CODE_OF_CONDUCT.md). By participating in this project you agree to abide by its terms.
------

## Badges

[![Contributor Covenant](https://img.shields.io/badge/Contributor%20Covenant-v2.0%20adopted-ff69b4.svg)](https://github.com/alkevin/music-all-vitrine/blob/master/CODE_OF_CONDUCT.md)
![GitHub](https://img.shields.io/github/license/alkevin/music-all-vitrine?style=plastic)

## [![SonarCloud](https://sonarcloud.io/images/project_badges/sonarcloud-black.svg)](https://sonarcloud.io/dashboard?id=alkevin_music-all-vitrine)

------

[![Quality Gate Status](https://sonarcloud.io/api/project_badges/measure?project=alkevin_music-all-vitrine&metric=alert_status)](https://sonarcloud.io/dashboard?id=alkevin_music-all-vitrine)
[![Code Smells](https://sonarcloud.io/api/project_badges/measure?project=alkevin_music-all-vitrine&metric=code_smells)](https://sonarcloud.io/dashboard?id=alkevin_music-all-vitrine)
[![Coverage](https://sonarcloud.io/api/project_badges/measure?project=alkevin_music-all-vitrine&metric=coverage)](https://sonarcloud.io/dashboard?id=alkevin_music-all-vitrine)
[![Security Rating](https://sonarcloud.io/api/project_badges/measure?project=alkevin_music-all-vitrine&metric=security_rating)](https://sonarcloud.io/dashboard?id=alkevin_music-all-vitrine)

------

[![Maintainability Rating](https://sonarcloud.io/api/project_badges/measure?project=alkevin_music-all-vitrine&metric=sqale_rating)](https://sonarcloud.io/dashboard?id=alkevin_music-all-vitrine)
[![Reliability Rating](https://sonarcloud.io/api/project_badges/measure?project=alkevin_music-all-vitrine&metric=reliability_rating)](https://sonarcloud.io/dashboard?id=alkevin_music-all-vitrine)

## Workflows

------

![GitHub Workflow Status](https://img.shields.io/github/workflow/status/alkevin/music-all-vitrine/Test%20Maven%20Projects?label=Test%20Maven%20Projects&logo=github%20actions&style=plastic)
![GitHub Workflow Status](https://img.shields.io/github/workflow/status/alkevin/music-all-vitrine/Build%20Maven%20Projects?label=Build%20Maven%20Projects&logo=github%20actions&style=plastic)
![GitHub Workflow Status](https://img.shields.io/github/workflow/status/alkevin/music-all-vitrine/Compile%20Maven%20Projects?label=Compile%20Maven%20Projects&logo=github%20actions&style=plastic)
![GitHub Workflow Status](https://img.shields.io/github/workflow/status/alkevin/music-all-vitrine/Release%20Maven%20Projects?label=Release%20Maven%20Projects&logo=github%20actions&style=plastic)
![GitHub Workflow Status](https://img.shields.io/github/workflow/status/alkevin/music-all-vitrine/Deploy%20Maven%20Projects?label=Deploy%20Maven%20Projects&logo=github%20actions&style=plastic)
![GitHub Workflow Status](https://img.shields.io/github/workflow/status/alkevin/music-all-vitrine/Quality%20gate%20-%20Sonar?label=Quality%20gate%20-%20Sonar&logo=github%20actions&style=plastic)
</p>

------

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy this project.

## Usage

## You will need

- [X] [Git](https://www.atlassian.com/fr/git/tutorials/install-git)
- install on ubuntu dist:
  
    ```bash
    sudo apt-get install git
    ```

- [X] [Docker](https://docs.docker.com/install/)
- install on ubuntu dist:
  
    ```bash
    curl -ssL https://get.docker.com | sh
    ```

- [X] git clone <https://github.com/alkevin/music-all-vitrine.git>

- [X] in the root project
  
    ```bash
    docker build -t music-all-vitrine .
    ```

- [X] launch the app
  
    ```bash
    docker run -p 8081:8080 --name <IMAGE_NAME> music-all-vitrine
    ```

- [X] go to [localhost](http://localhost:8081)

## Install if you don't use docker

- [X] git clone <https://github.com/alkevin/music-all-vitrine.git>

## Running The tests

- [X] unit tests
- [X] functionnal tests
- [X] integration tests

## Coding style tests

- [X] [hadolint](https://github.com/hadolint/hadolint)

## Deployment

We use [github actions](https://github.com/features/actions) to perform the CI/CD of this project with testing, analyse, packaging and deployment.

- [X] [heroku](https://music-all-vitrine.herokuapp.com/)

## Contributing

Please read [CONTRIBUTING.md](https://github.com/alkevin/music-all-vitrine/blob/master/CONTRIBUTING.md) for details on our code of conduct, and the process for submitting pull requests to us.

## Versioning

For the versions available, see the [tags on this repository](https://github.com/alkevin/music-all-vitrine/releases)

## Packaging

See all [package](https://github.com/alkevin/music-all-vitrine/packages) available.

## Authors

> Alves Kévin - Initial work - [alkevin](https://github.com/alkevin)

See also the list of [contributors](https://github.com/alkevin/music-all-vitrine/graphs/contributors) who participated in this project.

## License

music-all-vitrine is MIT licensed, as found in the [LICENSE][0] file.

[0]: https://github.com/alkevin/music-all-vitrine/blob/master/LICENSE.md
