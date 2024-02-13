# file-essence

`file-essence` is a File Metadata Microservice built with Nodejs, Express framework and `multer`. `multer` is a node.js middleware for handling multipart/form-data, which is primarily used for uploading files.

## ⚙️ Installation

- Open CMD
  
- Change directory to desktop

  `cd desktop`
   
- Clone this repository

  `git clone git@github.com:backendkolawole/file-essence.git`

- Change the current directory

  `cd file-essence`
  
- Install packages

  `npm install`

- Run the server

  `npm start`

 

> [!IMPORTANT]
> To avoid port collisions, in the source code, the port value is `3000`

## Usage
You can submit a form that includes a file upload.

When you submit a file, you receive the file name, type, and size in bytes within the JSON response.
