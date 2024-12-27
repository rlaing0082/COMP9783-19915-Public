# Final-Project: Grocery List App

The React Grocery List App is a lightweight and simple tool that allows multiple family members to collaborate in tracking and listing items that need regular replenishment.

## Table of Contents

- Features
- Installation
- Usage
- Screenshtos
- Contrubution
- License
- Contact

## Features

- **Feature 1:** The register and login pages enable new users to sign up and returning users to log in with ease.

  ![Screenshot of the register page.](/assets/images/register.png)
  ![Screenshot of the login page.](/assets/images/login.png)

- **Feature 2:** A clean and intuitive interface makes adding items quick and simple.

  ![Screenshot of the add items page.](/assets/images/addItems.png)

- **Feature 3:** Users can seamlessly switch between dark mode and light mode for a personalized experience.

  ![Screenshot of the dark theme example.](/assets/images/dark.png)
  ![Screenshot of the light theme example.](/assets/images/light.png)

- **Feature 4:** Features pagination and sortable table headers for easy data navigation and organization.

  ![Screenshot of the sortable table headings and pagination.](/assets/images/pagination.png)

- **Feature 5:** Mobile-friendly design with a sticky table column for an improved browsing experience when viewing numerous items.

![Screenshot of the sticky table column via mobile view.](/assets/images/table.png)

## Installation

The grocery store application consists of two components: the front end and the back end.

Back End: Handles user authentication, data storage, and provides CRUD functionalities.
Front End: Delivers the user interface for interacting with the application.

**Installation Steps**

Download the required files for both the front-end and back-end components.
Update the .env file for the front-end component, specifying the API URL and port.
Update the .env file for the back-end component, ensuring the correct port number is defined.

**Starting the Application**

**For the back end:** _Run npm run start_

**For the front end:** _Run npm run dev_

Make sure the API URL and ports are correctly configured for seamless communication between the components.

## Usage

Grocery items are logged into the system as they are purchased, including details such as the item name, category, sub-category, unit, status, purchase date, and notes.

- As items are consumed, their status can be updated (e.g., "Out of Stock," "25%", etc.).
- When it's time to shop, users can sort the table to quickly identify items that are out of stock.
- To improve usability, items with an "Out of Stock" status are highlighted in red, while those at "25%" are highlighted in yellow.
- Items can be edited or deleted as needed to keep the list accurate and up to date.

## License

MIT License

Copyright (c) [2024] [Robert Laing]

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

## Contact

Robert Laing : rlaing0082@gmail.com
