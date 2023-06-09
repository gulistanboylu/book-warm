# main branch title same file edit change 30

Test the changes&#x20;

## Run via Mavenbbbb

You will need to have `mvn` (version 3.5 or later), `npm`, and `node` (version 14.x) installed.

```test
mvn spring-boot:run
```

You will be able to access the UI via [localhost:8080](#) as well as view the Swagger API documentation via <http://localhost:8080/swagger-ui.html>

## Run via Docker

Use the Dockerfile in this repository that will build an image with the app, or use the `docker-compose.yml` file which does it automatically for you:

```bash
docker-compose up
```

## Roles

| Role               | Name                  | GitHub Username |
| ------------------ | --------------------- | --------------- |
| Product Manager    | Alan Parkinson        | @aparkinson     |
| Software Developer | George McCreadie      | @isitgeorge     |
| Software Developer | Matt Cooper           | @mc00905        |
| Software Developer | Gulistan 'Rose' Boylu | @gulistanboylu  |

### example for multi line code

````javascript
let mix = require('laravel-mix');
let tailwindcss = require('tailwindcss');


mix.postCss('dev/styles.css', 'prod/css', [
  tailwindcss('./tailwind.config.js'),
])```
````
