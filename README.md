<a name="readme-top"></a>
<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->


<!-- PROJECT LOGO -->
<br />
<div align="center">
  <h3 align="center">Endless Health Web App</h3>

  <p align="center">
    <br />
    <a href="https://web.endless.health/" target="_blank" >View Demo</a>
    ·
    <a href="https://github.com/endlesshealthinc/eh-web-portal/issues" target="_blank" >Report Bug</a>
    ·
    <a href="https://github.com/endlesshealthinc/eh-web-portal/issues" target="_blank" >Request Feature</a>
  </p>
</div>



<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
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
        <li><a href="#deployment">Deployment</a></li>
      </ul>
    </li>
    <li><a href="#AppFlow">AppFlow</a></li>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project
<a href="https://web.endless.health" target="_blank">Product link</a>

Endless Health Web App is a tool which shows beautiful visual representation of biomarkers based on test results.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

### Built With

* [![React][React.js]][React-url]

<p align="right">(<a href="#readme-top">back to top</a>)</p>

### Prerequisites
Please install latest Nodejs on your machine with version above 18.15.0. <a href="https://nodejs.org/en/download" target="_blank">Click here</a> to download Nodejs 


### Installation

To install and setup the app, please follow the steps mentioned below

1. Clone the repo
   ```sh
   git clone https://github.com/your_username_/Project-Name.git
   ```
2. Install NPM packages
   ```sh
   npm install
   ```
3. Run the development server using the following command:
   ```sh
   npm start
   ```

### Deployment
1. To create a production-ready build, use the following command:
   ```sh
   npm run build
   ```  
2. Now, navigate to the build directory and use serve to run a local server:
   ```sh
   serve -s
   ```  

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- App Flow -->
## AppFlow

### 1. Initial Email Verification

- Navigate to the root URL of the app.
- Submit your email address.
- Email address will be verified with the backend.
- Based on the email status, you will be redirected to:
   #### A. If the account exists 
    - You will be sent to the login page at "/login".
   #### B. If the account does not exist:
    - You will be sent to the signup page at "/signup".

### 2. Existing Account (Redirected to /login)

- If your account already exists, you will be redirected to the "/login" page.
- Enter your password on the login page.
- After successful authentication, you will be redirected to the "/dashboard" page.
- Access your health reports on the dashboard.

### 3. New Account (Redirected to /signup)

- If your account does not exist:
  - You will be redirected to the "/signup" page.
  - Provide your first name, last name, and password.
  - Submit the details.
  - A verification email will be sent to your inbox.
  - Check your email and verify your account.
  - After successful email verification, log in using the credentials from step 2 above.

### 4. Forgot Password

- On the "/login" page, click on the "Forgot Password" link.
- You will be directed to the "/forgot-password" page.
- Enter your email and submit.
- An email with a link to reset the password will be sent to your email.
- Reset your password using the provided link.
- Once the password is reset, log in using the new password.


<!-- CONTACT -->
## Contact

Alok Pathak ( alok.pathak.sg@gmail.com )

Project Link: [https://github.com/endlesshealthinc/eh-web-portal](https://github.com/endlesshealthinc/eh-web-portal)

<p align="right">(<a href="#readme-top">back to top</a>)</p>


<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->

[React.js]: https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB
[React-url]: https://reactjs.org/
