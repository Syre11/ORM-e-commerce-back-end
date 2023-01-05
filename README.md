# ORM e-Commerce Back End

## Description

This project was built to practice working on the back end of a website. The majority of the project was focused on working with sequelize and express routers. I also wanted to work on making commits to GitHub more frequently.

## Table of Contents (Optional)

- [Installation](#installation)
- [Usage](#usage)
- [Walkthrough](#walkthrough)
- [Credits](#credits)
- [License](#license)

## Installation

First, you will need to clone the respository to your local machine using:

    git clone

Once the repository is on your machine, run the following to install the needed dependencies:

    npm i

To install each dependency individually, the following can be used:

    npm i express
    npm i mysql2
    npm i sequelize

## Usage

To begin the application you will need to run the following to set up the database:

    mysql -u [user] -p

Enter your password and then run:

    source db/schema.sql;
    exit

Once you've exited mysql, run the following to seed the database:

    npm run seed

You are now ready to start your server, do so using:

    npm start

## Walkthrough

[![alt text](/assets/example.png)](https://example.com)


## Credits

- Starter Code: https://github.com/coding-boot-camp/fantastic-umbrella
- NodeJS: https://nodejs.org/en/
- Express.js: https://www.npmjs.com/package/express
- MySQL: https://www.mysql.com/
- Sequelize: https://sequelize.org/
- Insomnia: https://insomnia.rest/

## License

See license [here](./LICENSE)

    MIT License

    Copyright (c) 2023 Syre11

    Permission is hereby granted, free of charge, to any person obtaining a copy
    of this software and associated documentation files (the "Software"), to deal
    in the Software without restriction, including without limitation the rights
    to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
    copies of the Software, and to permit persons to whom the Software is
    furnished to do so, subject to the following conditions:

    The above copyright notice and this permission notice shall be included in all
    copies or substantial portions of the Software.

    THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
    IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
    FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
    AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
    LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
    OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
    SOFTWARE.