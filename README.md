[![CI/CD Pipeline](https://github.com/saraduque1/laboratorio2-arqui-soft/actions/workflows/build.yml/badge.svg)](https://github.com/saraduque1/laboratorio2-arqui-soft/actions/workflows/build.yml)

[![Quality Gate Status](https://sonarcloud.io/api/project_badges/measure?project=saraduque1_laboratorio2-arqui-soft&metric=alert_status)](https://sonarcloud.io/summary/new_code?id=saraduque1_laboratorio2-arqui-soft)

[![Bugs](https://sonarcloud.io/api/project_badges/measure?project=saraduque1_laboratorio2-arqui-soft&metric=bugs)](https://sonarcloud.io/summary/new_code?id=saraduque1_laboratorio2-arqui-soft)

[![Coverage](https://sonarcloud.io/api/project_badges/measure?project=saraduque1_laboratorio2-arqui-soft&metric=coverage)](https://sonarcloud.io/summary/new_code?id=saraduque1_laboratorio2-arqui-soft)

[![Lines of Code](https://sonarcloud.io/api/project_badges/measure?project=saraduque1_laboratorio2-arqui-soft&metric=ncloc)](https://sonarcloud.io/summary/new_code?id=saraduque1_laboratorio2-arqui-soft)

[![Technical Debt](https://sonarcloud.io/api/project_badges/measure?project=saraduque1_laboratorio2-arqui-soft&metric=sqale_index)](https://sonarcloud.io/summary/new_code?id=saraduque1_laboratorio2-arqui-soft)

[![Vulnerabilities](https://sonarcloud.io/api/project_badges/measure?project=saraduque1_laboratorio2-arqui-soft&metric=vulnerabilities)](https://sonarcloud.io/summary/new_code?id=saraduque1_laboratorio2-arqui-soft)

Implementation of a Simple App with the next operations:

* Get random nations
* Get random currencies
* Get random Aircraft
* Get application version
* health check
  Including integration with GitHub Actions, Sonarqube (SonarCloud), Coveralls and
  Snyk
### Folders Structure
In the folder `src` is located the main code of the app
In the folder `test` is located the unit tests
### How to install it
Execute:
```shell
$ mvnw spring-boot:run
```
to download the node dependencies
### How to test it
Execute:
```shell
$ mvnw clean install
```
### How to get coverage test
Execute:
```shell
$ mvwn -B package -DskipTests --file pom.xml