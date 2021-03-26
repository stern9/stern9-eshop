<!-- PROJECT LOGO -->
<br />
<p align="center">
  <a href="https://stern9-anime-app.netlify.app/">
    <img src="https://emojipedia-us.s3.dualstack.us-west-1.amazonaws.com/thumbs/240/apple/271/shopping-bags_1f6cd-fe0f.png" alt="Logo" width="80" height="80">
  </a>

  <h3 align="center">MERN eShop</h3>

  <p align="center">
    Full Stack ecommerce MERN App. Built with React, NodeJS and Express. Data is handled using MongoDB. Payments managed through PayPal.
    <br />
    <br />
    <a href="https://stern-eshop.herokuapp.com/" target="_blank">View Demo »</a>
  </p>
</p>

<details open="open">
  <summary><h2 style="display: inline-block">Table of Contents</h2></summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#license">License</a></li>
  </ol>
</details>

## About The Project

### Built With

- [MongoDB](https://www.mongodb.com/3)
- [Mongoose](https://mongoosejs.com/docs/guide.html)
- [ExpressJS](https://expressjs.com/)
- [ReactJS](https://reactjs.org/docs/)
- [NodeJS](https://nodejs.org/en/)
- [React-bootstrap](https://react-bootstrap.github.io/getting-started/introduction)
- [Redux](https://redux.js.org/)
- [JWT](https://jwt.io/)
- [PayPal](https://developer.paypal.com/docs/checkout/)
- [Heroku](https://www.heroku.com/)

## Getting Started

### Testing the UI with dummy data

#### Admin can add items, process purchases, edit users

| Admin                     |           User           |
| ------------------------- | :----------------------: |
| user: Test Admin          |     user: Test User      |
| email: testAdmin@mail.com | email: testUser@mail.com |
| pass: admin               |        pass: user        |

To get a local copy up and running follow these simple steps.

### Installation

1. Clone the repo
   ```sh
   git clone https://github.com/stern9/stern9-eshop.git  or
   git clone git@github.com:stern9/stern9-eshop.git
   ```
2. Install NPM packages
   ```sh
   npm install / yarn
   ```
3. Connect DB and data needs to be imported from server/seeder. Will need to set up API in .env file

4. Run both client and server
   ```sh
   npm run dev / yarn dev
   ```

## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## Acknowledgements

- [nodemon](https://github.com/remy/nodemon)
- [concurrently](https://github.com/kimmobrunfeldt/concurrently#readme)
- [dotenv](https://www.npmjs.com/package/dotenv)
- [colors-js](https://www.npmjs.com/package/colors.js)
- [express-async-handler](https://www.npmjs.com/package/express-async-handler)
- [font-awesome](https://cdnjs.com/libraries/font-awesome)
- [morgan](https://github.com/expressjs/morgan#readme)
- [multer](https://github.com/expressjs/multer#readme)
