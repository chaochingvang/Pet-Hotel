![License](https://img.shields.io/github/license/chaochingvang/Pet-Hotel-Backend.svg?style=for-the-badge) ![Repo Size](https://img.shields.io/github/languages/code-size/chaochingvang/Pet-Hotel-Backend.svg?style=for-the-badge) ![TOP_LANGUAGE](https://img.shields.io/github/languages/top/chaochingvang/Pet-Hotel-Backend.svg?style=for-the-badge) ![FORKS](https://img.shields.io/github/forks/chaochingvang/Pet-Hotel-Backend.svg?style=for-the-badge&social) ![Stars](https://img.shields.io/github/stars/chaochingvang/Pet-Hotel-Backend.svg?style=for-the-badge)
    
# Pet Hotel

## Table of Contents

- [Pet Hotel](#pet-hotel)
  - [Table of Contents](#table-of-contents)
  - [Description](#description)
  - [Screenshots](#screenshots)
  - [Built With](#built-with)
  - [Getting Started](#getting-started)
    - [Prerequisites](#prerequisites)
    - [Installation](#installation)
  - [Usage](#usage)
  - [License](#license)
  - [Acknowledgements](#acknowledgements)
  - [Contacts](#contacts)

## Description

Pet Hotel was a group project utilizing React.js as a front-end framework and C# and .NET as the back-end framework. The application is built to allow for the creation of pet owners, pets, and allow the pet to check-in and check-out of the Pet-Hotel. 

## Screenshots

![Pet Hotel Logo](./README_images/pethotel-logo.png)
![Pet Hotel App](./README_images/pethotel.png)

## Built With

<a href="https://docs.microsoft.com/en-us/dotnet/csharp/"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/csharp/csharp-original.svg" height="40px" width="40px" /></a><a href="https://developer.mozilla.org/en-US/docs/Web/CSS"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original.svg" height="40px" width="40px" /></a><a href="https://developer.mozilla.org/en-US/docs/Web/HTML"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original.svg" height="40px" width="40px" /></a><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" height="40px" width="40px" /></a><a href="https://nodejs.org/en/"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-original.svg" height="40px" width="40px" /></a><a href="https://www.postgresql.org/"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/postgresql/postgresql-original.svg" height="40px" width="40px" /></a><a href="https://reactjs.org/"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original-wordmark.svg" height="40px" width="40px" /></a><a href="https://redux.js.org/"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/redux/redux-original.svg" height="40px" width="40px" /></a>

## Getting Started

To observe the functionalities of this application, the user will also need to fork, clone and install the front-end framework of this application. This repository only consist of the back-end framework. The front-end framework repository can be found at [Pet Hotel Frontend](https://github.com/chaochingvang/Pet-Hotel-Frontend/).

### Prerequisites

Softwares used in creating this application includes:

- [Visual Studio Code](https://code.visualstudio.com/)
- [PostgreSQL](https://www.postgresql.org/)
- [Postico](https://eggerapps.at/postico/)
- [Node.js](https://nodejs.org/en/)
- [Nodemon](https://nodemon.io/)
- [.NET](https://dotnet.microsoft.com/en-us/)

The application's repository may require alterations to lines of codes if used with other softwares that are not listed above.

### Installation

1. To run this application, the user should fork the repository onto their own GitHub account. In the user's repository, the user should copy the link and clone the repository onto their local system. Navigate to the repository folder using the terminal and run command line `npm install`
   - `$ cd ../Pet-Hotel-Backend`
   - `$ npm install`

2. Create a local postgreSQL database called `pet_hotel` with Postico using the command lines from the database.sql file. Using different database systems may require the user to alter or add additional command lines to reflect the example database provided.

3. To start up the application, enter in the terminal the command lines of:

   - `dotnet run` in the `Pet-Hotel-Backend` terminal to start the server
   - `npm start` in the `Pet-Hotel-Frontend` terminal to start the client

   The server should be running on `http://localhost:5000` whereas the client should be on `http://localhost:3000`. Both the server and the client is required to be up and running for the application to run successfully.

## Usage

Once the application is up and running, the user should be redirected to the browser with the application loaded. If not, open up a browser and enter in the url:

- `http://localhost:3000`

On the application, the user can create an Owner using the interface on the browser. Upon creating a pet owner, the user can now create a pet using the different types of selections in the dropdown menu and the owner it belongs to. The user can delete the pet. Multiple owners and pet can be created. 

Clicking 'Check In' will check in the pet to the Pet Hotel and show the time that it was checked in. Once the user want to 'Check Out' the pet, the user can click the button and it will check out the pet from the Pet Hotel. 


## License

<a href="https://choosealicense.com/licenses/unlicense/"><img src="https://raw.githubusercontent.com/johnturner4004/readme-generator/master/src/components/assets/images/unlicense.svg" height=40 />The Unlicense</a>

## Acknowledgements

I would like to extend a thanks to our instructors, Dane Smith and Liz Kerber, the Solinas Cohort, and the whole greater community at Prime Digital Academy, for providing me with the necessary tools and skills to succeed.

I also would like to thank our friends and families for continuing to support me as I've continued to grow into becoming a software developer.

## Contacts

Chaoching Vang<br />
<a href="https://www.linkedin.com/in/chaochingvang"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" /></a>  <a href="mailto:chaoching.vang@gmail.com"><img src=https://raw.githubusercontent.com/johnturner4004/readme-generator/master/src/components/assets/images/email_me_button_icon_151852.svg /></a>