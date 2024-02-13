# file-essence

`file-essence` is a File Metadata Microservice built with Nodejs, Express framework and `multer`. `multer` is a node.js middleware for handling multipart/form-data, which is primarily used for uploading files.

## Usage
You can submit a form that includes a file upload.

When you submit a file, you receive the file name, type, and size in bytes within the JSON response.

## ⚙️ Installation

- Open CMD
  
- Change directory to desktop

  `cd desktop`
   
- Clone this repository

  `git clone git@github.com:backendkolawole/file-essence.git`

- Install packages

  `npm install`

- Create a .env file in the root directory

  - Set up the `MONGO_URI` variable equal to the DB connection string
  - Set up the `PORT` variable
 

> [!IMPORTANT]
> To avoid port collisions, in the source code, the port value is `3000`

## Contact

