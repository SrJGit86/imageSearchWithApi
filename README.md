
# Image Search Web App

The Image Search App is a web application that allows users to search for images using keywords. It fetches images from the Unsplash API and displays them in a visually appealing format.

## Table of Contents

- [Demo](#demo)
- [Features](#features)
- [Prerequisites](#prerequisites)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Contributing](#contributing)

## Demo

Test the button in action here: [Live Demo](https://srjgit86.github.io/imageSearchWithApi/index.html)

## Features

- Search for images using keywords.
- Display search results with image thumbnails and links to the original images on Unsplash.
- Load more images as you scroll or by clicking the "Show More" button.
- Responsive design for various screen sizes.

## Prerequisites

Before you begin, ensure you have the following installed or configured:

- A code editor (e.g., Visual Studio Code, Sublime Text).
- A modern web browser (e.g., Chrome, Firefox).
- An internet connection to fetch images from the Unsplash API.
- An Unsplash API access key. You can obtain one by signing up for a developer account on [Unsplash](https://unsplash.com/developers).

## Getting Started

1. Clone this repository to your local machine:

   ```shell
   git clone https://github.com/SrJGit86/imageSearchWithApi.git
   ```

2. Navigate to the project directory:

   ```shell
   cd imageSearchWithApi
   ```

3. Create a `config.js` file in the project root and add your Unsplash API access key:

   ```javascript
   // index.js
   const accessKey = 'RZEIOVfPhS7vMLkFdd2TSKGFBS4o9_FmcV1Nje3FSjw';
   ```

4. Open the `index.html` file in your web browser or set up a local development server.

## Usage

1. Open the web application in your web browser.

2. Enter a keyword in the search input field and click the "Search" button.

3. The search results will be displayed as a grid of image thumbnails.

4. To view the original image on Unsplash, click on the image or the provided link.

5. To load more images, either scroll down to trigger automatic loading or click the "Show More" button.

## Contributing

Contributions to this project are welcome. To contribute:

1. Fork the repository.

2. Create a new branch for your feature or bug fix:

   ```shell
   git checkout -b feature/my-feature
   ```

3. Make your changes and commit them:

   ```shell
   git commit -m "Add my feature"
   ```

4. Push your changes to your fork:

   ```shell
   git push origin feature/my-feature
   ```

5. Create a pull request on the original repository.

6. Wait for review and approval.

---
