# Creator
Week-10 Challange SVG Logo Maker

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Description
The purpose of this application is to enable independent web developers to generate basic logos for their projects and clients. With the use of inquirer, the user is prompted in the command line to specify the desired appearance of their logo, including the text to be displayed (up to three characters), the color of the text, the logo's shape (triangle, square, or circle), and the color of the shape. After the user completes all prompts, a logo is created using their selections in an SVG file.

## Live Screen Recording of Application

https://drive.google.com/file/d/1YLrWikl2v7HxQ_ZjT-hd2AT_PXech0gR/view 

## Screenshot

![Screenshot1](/img/logoQ.png)

## Set up

1. Clone the repo:
   git clone 

2. Open in VS Code. If you do not have VS code you must install it.

3. Using the terminal, install node.js v16. If you have homebrew, the command should look like the following (brew install node@16), however this may vary and the documentation should be consulted.

4. Once node.js v16 is installed, in the terminal, utilize the command npm init -y to initialize and create a package.json where project files will be stored.

5. Next, use the terminal to run the command npm i to install the dependencies associated with this application (developers may need to install inquirer and jest directly from the command line, to do so the command for inquirer will be npm i inquirer@8.2.4 to install v8.2.4 of the inquirer, and npm i jest to install the latest version of jest).

6. To run the application, within the terminal, type the command node index.js.