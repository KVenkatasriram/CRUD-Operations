# React CRUD API Client App
A simple React App for C.R.U.D. operations on data from an external REST API.
## Setup

Node.js and Node Package Manager (NPM) are required to run and build this project.
To setup the app, while inside the project folder, execute the following commands:

```Shell
  npm install
  npm start
```

This will install all the dependencies and run a server in development mode on [http://localhost:3000](http://localhost:3000).
## API Endpoints

In this case the value used are an example and fetch the data to a localhost Django web-server that serves an API with the following endpoints.

### **{base_url}/elements**

- GET: list of elements is returned
- POST: a new element is added

### **{base_url}/elements/{element_id}**

- PUT: modifies the element data, selecting it by his element_id
- DELETE: deletes the element with id of element_id
## Improvements to Make

- [x] Reduce props passed for urls
- [ ] Add code comments and improve documentation
- [ ] Use better React patterns to reduce passed props and reduce written code
- [ ] Edit Form.jsx to generalize fetched JSON data from the API (avoid hardcoding)
- [ ] Add a way to setting up the form validation more easily
- [ ] Add visual feedbacks when editing/adding/deleting data  
- [ ] Improve app navigation and layout
