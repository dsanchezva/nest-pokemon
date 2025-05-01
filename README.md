<p align="center">
  <a href="http://nestjs.com/" target="blank"><img src="https://nestjs.com/img/logo-small.svg" width="120" alt="Nest Logo" /></a>
</p>

[circleci-image]: https://img.shields.io/circleci/build/github/nestjs/nest/master?token=abc123def456
[circleci-url]: https://circleci.com/gh/nestjs/nest

  <!--[![Backers on Open Collective](https://opencollective.com/nest/backers/badge.svg)](https://opencollective.com/nest#backer)
  [![Sponsors on Open Collective](https://opencollective.com/nest/sponsors/badge.svg)](https://opencollective.com/nest#sponsor) -->

## Ejecutar en desarollo

1. Clonar repositorio
2. Ejecutar

```
yarn install
```

3. Tener CLI instalado

```
npm i -g @nestjs/cli
```

4. levantar la base de datos

```
 docker-compose up -d
```

5. Clonar el archivo **.env.template** y renombrar la copia a **.env**

6. Llenar las variables de entonrno en el ```.env````

7. Ejecutar la aplicacion en dev:

````
yarn start:dev
```

8. Reconstruir la base de datos con la semilla añade 650 a la base de datos

```
http://localhost:3000/api/v2/seed
```

## Stack usado

- MongoDB
- Nesjs
````
