# Standard Blog Website
This is a simple personal Blog Site where the user can add and store articles.  

## Requirements
- Node (version 14.0+)
- npm (version 6.0+)
- MongoDB
- A Web Browser
- Git

### Dependencies
This project relies heavily on the following ```npm``` packages:
- express
- body-parser
- mongoose
- ejs

## Download/Install
To run this project, clone the repository by either of the two methods:
- Go to Code → Download ZIP, and extract the ZIP file.
- Go to Terminal, and run the following command: <br>
```git clone https://github.com/abhinrustagi/Standard-Blog-Site.git```

Then,
- Run the following command: <br> ```node app.js```

**Make sure you have node installed on your system.**

**If in case the ```node_modules``` folder is not available in your downloaded directory, go to Terminal, navigate to the folder containing the project and run ```npm install```.**

### Setting up the database
Start a mongod process by running the following command in the terminal. A mongod process is usually started at 27017 port.

### Running the application
Make sure you have completed all the steps in the Initialization section. Navigate to the project directory, run the following command in Terminal, it should return some output.
```Server started on port 8888.```

This means the application is up and running successfully. Now, to open the application, go to the browser and type the following address:
```localhost:8888/```

## Home Page
Home Page contains all the stored articles in order.

## Adding Articles
To add an articles, go to ```localhost:8888/compose``` and you can post a new article which will be added to the database. 


## Screenshots
**Home Screen**
![Home Screen](screens/Screen1.png)

**Adding a new post**
![Adding new item](screens/Screen2.png)

**New Post Added**
![New Item Added](screens/Screen3.png)


## References
- [Node Documentation](https://nodejs.org/en/docs/)
- [Express Documentation](https://expressjs.com/)
- [EJS Documentation](https://ejs.co/#docs)
- [Body Parser Documentation](https://www.npmjs.com/package/body-parser)
