# Note_Taker

## Description

    This app was an excercise in setting up an App to be both installable as well as have the ability to add information while offline that is later pushed to the server (once connection is restored). 

    The app is currently deployed at:

    https://budget-tracker3123.herokuapp.com/

  
## Table of Contents
      - [Installation](#installation)
      - [Usage](#usage)
      - [Contributing](#contributions)
      - [License](#license)
      - [Tests] (#test)
      - [Questions](#questions)
  ## Installation
          If you are attempting to run this locally, you will need to use the following commands after cloning the repo:

          -npm i
          -node server.js

          This should then show in your command line a link to your localhost with a port of 3001 (default)

          Once running, you should be able to use Chrome Tools or other Dev Tools to disconnect the webpage from connected, but still allows you to enter transactions. Which will be updated to the server upon refresh of page. It accomplishes this by using IndexedDB to store the items that are listed in the service worker file.
  ## Usage
          Application usage is simply to enter a transaction name as well as an amount, and then choose whther it was added to your budget or subtracted.
  ## Contributions
          Not much to contribute but if you would like to send a pull request, please feel free, basic considerations of form and format please.
  ## License
        Not licensed as it is part of learning materials.
  ## Tests
          This application has no tests attributed to it
  ## Questions
      If you have any questions, please feel free to reach out to me here.