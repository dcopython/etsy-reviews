# Etsy Reviews Component - Hack Reactor Front End Project

> This is my attempt at learning and understanding how review components work under the hood.
> I wanted to recreate one as a full stack application using Etsy's review component as a reference.

> The page was created with React for the front-end and served from an ExpressJS back-end, where it's pulling faker generated reviews
> from a MongoDB database in a Docker container and pictures hosted in a S3 bucket.
> It was combined with a teammate's gallery component through the use of a proxy server to recreate the entire product page.

> It was a great learning opportunity for me as I was my first chance to get hands on with using React Hooks over Class components,
> using Faker to generate data, integrating CircleCI into my GitHub workflow to ensure that any code I was pushed up was not faulty, and
> learning to quickly package and deploy the app to AWS with Docker.

## Related Projects

  - https://github.com/teamchupacabramcthundercats/etsy-gallery
  - https://github.com/teamchupacabramcthundercats/etsy-gallery-proxy
  - https://github.com/teamchupacabramcthundercats/etsy-reviews-proxy

## Table of Contents

1. [Usage](#Usage)
1. [Requirements](#requirements)
1. [Development](#development)

## Usage

> Run 'npm install' to install all necessary dependencies.
> Install mongoDB
> Run 'npm seed-db' to seed mongo database with products and reviews.
> Run 'npm run server' to start up the server

## Requirements

An `nvmrc` file is included if using [nvm](https://github.com/creationix/nvm).

- Node v12.18.3
- Axios v0.19.2
- Express v4.1.0
- Faker v4.1.0
- Moment v2.27.0
- Mongo v4.2.8
- Mongoose v5.9.27
- React v16.13.1
- React-DOM v4.44.1

## Development

### Installing Dependencies

From within the root directory:
- npm install

