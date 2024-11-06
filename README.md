# Meme Generator



## About

This is a web application that allows users to create memes by adding text to images.
The application is built with web technologies such as HTML, CSS, and JavaScript.
It uses the [Canvas API](https://developer.mozilla.org/docs/Web/API/Canvas_API) to draw the meme text on the image. 
Processing the image and text is done client-side, so no data is sent to any server.


## Features

Some of the key features of the application include creating memes by:
- Selecting an image from your device
- Selecting an image from the web (by URL)
- Selecting an image from the gallery
- Taking a photo with your device's web camera
- Using a solid color as background


## Development

Below are the instructions for setting up the development environment.

### Prerequisites

- Node.js (v20.x.x)
- npm (v10.x.x)

### Installation

Clone the repository to your local machine:


Navigate to the project's directory and install the dependencies:

```sh
npm install
```

### Running the application

To run the application in development mode, run the following command:

```sh
npm start -- --open
```

This will start the development server and open the application in your default web browser.

### Building the application for production

To build the application for production, run the following command:

```sh
npm run build
```

This will create a `dist` directory containing the production build of the application.

### Deployment

To deploy the application, run the following command:

```sh
npm run deploy
```

