[![CI/CD Pipeline](https://github.com/ValenMR/Laboratorio_2_Arquisoft/actions/workflows/build.yml/badge.svg)](https://github.com/ValenMR/Laboratorio_2_Arquisoft/actions/workflows/build.yml)

[![Quality Gate Status](https://sonarcloud.io/api/project_badges/measure?project=ValenMR_Laboratorio_2_Arquisoft&metric=alert_status)](https://sonarcloud.io/summary/new_code?id=ValenMR_Laboratorio_2_Arquisoft)

[![Bugs](https://sonarcloud.io/api/project_badges/measure?project=ValenMR_Laboratorio_2_Arquisoft&metric=bugs)](https://sonarcloud.io/summary/new_code?id=ValenMR_Laboratorio_2_Arquisoft)

[![Coverage](https://sonarcloud.io/api/project_badges/measure?project=ValenMR_Laboratorio_2_Arquisoft&metric=coverage)](https://sonarcloud.io/summary/new_code?id=ValenMR_Laboratorio_2_Arquisoft)

[![Lines of Code](https://sonarcloud.io/api/project_badges/measure?project=ValenMR_Laboratorio_2_Arquisoft&metric=ncloc)](https://sonarcloud.io/summary/new_code?id=ValenMR_Laboratorio_2_Arquisoft)


Implementation of a Simple App with the next operations:



* Get random nations
* Get random currencies
* Get random aviation
* Get application version
* health check

Including integration with GitHub Actions, Sonarqube (SonarCloud), Coveralls and Snyk


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

```