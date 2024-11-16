# BookStore - Online Book Store Project

Welcome to the BookStore project, a fully functional online bookstore built using the MERN (MongoDB, Express.js, React.js, Node.js) stack. This project allows users to browse, add, edit, and delete book entries, providing an intuitive and efficient way to manage your book collection.

## Team Members

T Mohith Shakthi
Mohanarangam
Manojh Pa
Manisha 

## Table of Contents
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Folder Structure](#folder-structure)
- [Getting Started](#How-to-run-this-project)
- [Contributing](#contributing)
- [License](#license)
- [Demo](#Demo)

## Features

### Browse Books
- Users can easily browse through the list of books, either in table format or by specific card view, providing flexibility in how they view their collection.


### Add New Books
- Add new entries for books to keep your collection up to date. Fill in the details, such as title, author, genre, and more, to maintain an organized library.


### Edit Book Details
- Users have the ability to edit the details of existing books, ensuring that the information in the collection is accurate and up-to-date.


### Delete Books
- Remove books from the list when they are no longer in your collection or for any other reason, ensuring that your library stays well-maintained.

### Show Single Book
- To see single book information.

## Tech Stack

This project is built using the following technologies:

- **MongoDB**: A NoSQL database for storing book information.
- **Express.js**: A Node.js web application framework for building the server-side API.
- **React.js**: A JavaScript library for building the user interface and frontend components.
- **Node.js**: A JavaScript runtime environment for running server-side code.
- **Tailwind CSS**: A utility-first CSS framework for styling the frontend.
- **Axios**: A promise-based HTTP client for making API requests.

## Folder Structure

The project has the following folder structure:

```
bookStore/
├── backend/
├── frontend/
├── README.md
```

- `frontend/`: Contains all the frontend code.
  - `frontend/src/`: Includes all frontend components and page routes.
- `backend/`: Houses all the database models and backend logic.
  - `backend/routes/`: Contains all the route handlers.
 
## How to run this project:

- ### For Frontend 
 Follow the below steps to run the project: 
- First clone or unzip the project folder.
* Go to the frontend directory by using the following command ``` cd frontend ```.
```
>>> Stepup firebase app and configure the environment
>>> 
VITE_API_KEY="AIzaSyB-6Mt2LZrRaPgXeNei15BoGBdRmSworD8"
VITE_Auth_Domain="book-store-d59c4.firebaseapp.com"
VITE_PROJECT_ID="book-store-d59c4"
VITE_STORAGE_BUCKET="book-store-d59c4.firebasestorage.app"
VITE_MESSAGING_SENDERID= "1003381657538"
VITE_APPID="1:1003381657538:web:03cb93ffbbe9e1553b905b"

```
+ Then run `` npm install `` commend to install node dependencies.
- Finally, to run the project, use ``npm run dev`` command.

- ### For Backend
Follow the below steps to run the project: 
- First clone or unzip the project folder.
* Go to the backend directory by using the following command ``` cd backend```.
```
DB_URL = "mongodb+srv://mohith:mohith@book-store.ikkkt.mongodb.net/ebooks-collection?retryWrites=true&w=majority&appName=Book-Store"

JWT_SECRET_KEY = 'bc992a20cb6706f741433686be814e3df45e57ea1c2fc85f9dbb0ef7df12308a669bfa7c976368ff32e32f6541480ce9ec1b122242f9b1257ab669026aeaf16'

```
+ Then run `` npm install `` commend to install node dependencies.
- Finally, to run the project, use ``npm run start:dev`` command.


## Contributing

We welcome contributions from the community! If you'd like to contribute to the project, please follow our [Contribution Guidelines](CONTRIBUTING.md).

## Demo
![Screenshot (421)](https://github.com/user-attachments/assets/125126ca-cfb5-4816-a8a5-68d9a928ec71)

