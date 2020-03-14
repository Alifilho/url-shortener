# URL Shortener

Simple backend url shortener made in nodeJS

## Getting Started

Clone the repository in git with

```
git clone https://github.com/Alifilho/url-shortener.git
```

Change the **server.js** file with your cluster informations

```
mongoose.connect('mongodb+srv://<username>:<password>@<cluster>', {
    useNewUrlParser: true,
    useUnifiedTopology: true
});
```

### Prerequisites

to install dependencies like mongoose, express, ... use

```
npm install -i
```

create an account and a free cluster for testing on [MongoDB Atlas](https://www.mongodb.com/cloud/atlas) or use local MongoDB

## Built With

* [NodeJS](https://nodejs.org/en/) - JavaScript runtime environment
* [NPM](https://www.npmjs.com/) - Dependency Management
* [Express](https://expressjs.com) - The Backend Framework
* [Mongoose](https://mongoosejs.com/) - MongoDB object modeling tool
* [Ejs](https://ejs.co/) - Embedded JavaScript templating
* [Shortid](https://www.npmjs.com/package/shortid) - Url-friendly generator

## Authors

* **Kyle Cook** - *Initial work* - [WebDevSimplified](https://github.com/WebDevSimplified)
* **Alisson Oliveira** - *Redid and sent here* - [Alifilho](https://github.com/Alifilho)
