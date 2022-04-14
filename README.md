# Udagram

The udagram application is a fairly simple application that includes all the major components of a Full-Stack web application.

This web application is hosted on (this link)[http://udacitytestbucket.s3-website-us-east-1.amazonaws.com]

## Getting Started

1. Clone this repo locally into the location of your choice.
2. Move the content of the udagram folder at the root of the repository as this will become the main content of the project.
3. Open a terminal and navigate to the root of the repo
4. run `npm install` to install the dependencies and `npm run start` to start your application.

### Dependencies

```
- Node v14.15.1 (LTS) or more recent. While older versions can work it is advisable to keep node to latest LTS version

- npm 6.14.8 (LTS) or more recent, Yarn can work but was not tested for this project

- AWS CLI v2, v1 can work but was not tested for this project

- A RDS database running Postgres.

- A S3 bucket for hosting uploaded pictures.

```

## Testing

This project contains two different test suite: unit tests and End-To-End tests(e2e). Follow these steps to run the tests.

1. `cd starter/udagram-frontend`
1. `npm run test`
1. `npm run e2e`

There are no Unit test on the back-end

### Unit Tests:

Unit tests are using the Jasmine Framework.

### End to End Tests:

The e2e tests are using Protractor and Jasmine.

## Built With

-   [Angular](https://angular.io/) - Single Page Application Framework
-   [Node](https://nodejs.org) - Javascript Runtime
-   [Express](https://expressjs.com/) - Javascript API Framework

## License

[License](LICENSE.txt)
