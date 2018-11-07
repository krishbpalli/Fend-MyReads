# Fend-MyReads
In this project you'll create a bookshelf app that allows you to select and categorize books you have read, are currently reading, or want to read. The project emphasizes using React to build the application. This project demonstrates the understanding of props, states and Components.

## Installation
1. Download the contents of this repository by clicking "Clone or download." From here, you may clone the repo using           SSH/HTTPS or download the files in a .zip folder.
2. Navigate to the project folder and install its dependencies by running npm install in your command line interface.
3. Once the dependencies have been installed, run npm start.
4. You can also use yarn. Run yarn install. Then run yarn start.
5. Your default browser should now open the app at http://localhost:3000, but if it doesn't, feel free to navigate there yourself.

## What You're Getting
```bash
├── CONTRIBUTING.md
├── README.md - This file.
├── SEARCH_TERMS.md # The whitelisted short collection of available search terms for you to use with your app.
├── package.json # npm package manager file. It's unlikely that you'll need to modify this.
├── public
│   ├── favicon.ico # React Icon, You may change if you wish.
│   └── index.html # DO NOT MODIFY
└── src
    ├── App.css # Styles for your app. Feel free to customize this as you desire.
    ├── App.js # This is the root of your app. Contains static HTML right now.
    ├── App.test.js # Used for testing. Provided with Create React App. Testing is encouraged, but not required.
    ├── BooksAPI.js # A JavaScript API for the provided Udacity backend. Instructions for the methods are below.
    ├── icons # Helpful images for your app. Use at your discretion.
    │   ├── add.svg
    │   ├── arrow-back.svg
    │   └── arrow-drop-down.svg
    ├── index.css # Global styles. You probably won't need to change anything here.
    └── index.js # You should not need to modify this file. It is used for DOM rendering only.
```

Remember that good React design practice is to create new JS files for each component and use import/require statements to include them where they are needed.

## Instructions

* In the mainpage, one will see three distinct bookshelves with books. You may move them from shelf to shelf by clicking a book's associated arrow and selecting the shelf you would like to place the book.
* On the bottom right of the home page, there is a + button that will take a user to a search page; on the search page, one can search for a book by title or author.

## Contributing

This repository is the starter code for _all_ Udacity students. Therefore, we most likely will not accept pull requests.

For details, check out [CONTRIBUTING.md](CONTRIBUTING.md).
