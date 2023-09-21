<br />
<p align="center">
  <div align="center">
    <img height="150" src="https://discord.com/channels/@me/1115709719168946187/1154518948826578976" alt="RecipeList" border="0"/>
  </div>
  <h3 align="center">Recipe List</h3>
  <p align="center">
    <a href="https://github.com/AnandaFPP/RecipeList-BE.git"><strong>Explore the docs »</strong></a>
    <br />
    ·
    <a href="https://food-recipe-be.onrender.com/recipes">Api Demo</a>
  </p>
</p>

## Table of Contents

- [Table of Contents](#table-of-contents)
- [About The Project](#about-the-project)
  - [Built With](#built-with)
- [Installation](#installation)
  - [Documentation](#documentation)
  - [Related Project](#related-project)

# About The Project

RecipeList is a food recipe website project that aims to inspire users to cook and share their favorite recipes. On this website, users can search for recipes, share their own recipes, and connect with other food enthusiasts.

One of RecipeList's main features is its user-friendly search function. Users can search for recipes by food name. The website also provides detailed recipe instructions, ingredient lists, and video tutorials to assist users in the cooking process.

Another unique feature of RecipeList is that users can create their own profiles, connect with other users, and share their favorite recipes. This allows users to learn from each other and explore new culinary ideas.

To use the RecipeList website, users simply need to create an account and start searching or sharing recipes. The site is designed to be easy to use and accessible to all levels of culinary expertise

## Built With

These are the libraries and service used for building this backend API

- [Node.js](https://nodejs.org)
- [Express](https://expressjs.com)
- [PostgreSQL](https://postgresql.com/)
- [Json Web Token](https://jwt.io)
- [Multer](https://github.com/expressjs/multer)
- [Cloudinary](https://cloudinary.com/)

# Installation

Follow this steps to run the server locally :

1. Clone this repository

```sh
git clone https://github.com/AnandaFPP/RecipeList-BE.git
```

2. Change directory to RecipeList-BE

```sh
cd RecipeList-BE
```

3. Install all of the required modules

```sh
npm install
```

4. Create PostgreSQL database

5. Create and configure `.env` file in the root directory, example credentials are provided in [.env.example](./.env.example)

```txt
- Please note that this server requires Google Drive API credentials and Gmail service account
- Otherwise API endpoint with image upload and account register won't work properly
```

6. Run this command to run the server

```sh
npm run server
```

- Or run this command for running in development environment

```sh
npm run dev
```

- Run this command for debugging and finding errors

```sh
npm run lint
```

## Documentation

Documentation files are provided in the [docs](./docs) folder

- [Postman API colletion]()
- [PostgreSQL database query](./query.sql)

API endpoint list are also available as published postman documentation

[![Run in Postman](https://run.pstmn.io/button.svg)](https://documenter.getpostman.com/view/28616224/2s9YBz2aXD)

## Related Project

:rocket: [`Backend FoodRecipe`](https://github.com/AnandaFPP/RecipeList-BE.git)

:rocket: [`Frontend FoodRecipe`](https://github.com/AnandaFPP/RecipeList-FE.git)

:rocket: [`Demo FoodRecipe`](https://github.com/AnandaFPP/RecipeList-BE.git)


Project link : [https://github.com/AnandaFPP/RecipeList-BE.git](https://github.com/AnandaFPP/RecipeList-BE.git)