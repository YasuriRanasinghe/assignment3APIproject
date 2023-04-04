# assignment3APIproject

About My Project

My task is to create a Node.js application using Express.js and MongoDB and implement 5 APIs that perform distinct CRUD operations on a collection of data.

I selected as my project about various types of products. They are soap, shampoo, say cauce, toothpaste and facewash. 
firstly, I created package.json and packagelock.json files. Then installed exprees, mongoose and nodemon. created server.js file. 
I did type codes on that. In that folder, include many neccessary code for my project. such as get product, post product, 
upadate a product, delete a product any any other special codes. 

I created Mongodb atles account and connect my appliacation to database. created productModel file under the Model folder. That 
included product details structure.

name: {
            type: String,
            required: [true, "Please enter a product name"]
        },
        quantity: {
            type: Number,
            required: true,
            default: 0
        },
        price: {
            type: Number,
            required: true,
        },
        image: {
            type: String,
            required: false,

        }
        
        
        
How to run my project

we can use run project using Postman, Insomnia. created Node API folder and created 
  
  POST /api/data - This API should create a new piece of data. 
  Post (API) - Save a Product (File name)
    http://localhost:3000/product
    
  GET /api/data - This API should return a list of all the data in my collection.
  Get (API) - Fetch Product (File name)
    http://localhost:3000/product
  
  GET /api/data/:id - This API should return a single piece of data based on the ID.
  Get (API) - Fetch a Product from ID (File name)
    http://localhost:3000/product/642c14c4de0c08b5c5c01ddd
    
  PUT /api/data/:id - This API should update a piece of data based on the ID.
  Put (API) - Update a Product from ID (File name)
    http://localhost:3000/product/642c14c4de0c08b5c5c01ddd
  
  DELETE /api/data/:id - This API should delete a piece of data based on the ID. 
  Del (API) - New Request (File name)
    http://localhost:3000/product/642c1442de0c08b5c5c01ddb
