# vanilla-node-mongo

This is a very simple nodejs server connected to mongodb.

## Installation istruction:
1. download all files in a new directory
2. open shell or command prompt
3. execute `npm install mongodb`
4. execute `npm init`
5. launch the server: `node app.js`

## How to use:
GET /api/todos (retrieves all todo items)  
POST /api/todos (add new todo item)  

GET /api/todos/:id (retrieves todo item with id)  
PUT /api/todos/:id (update todo item with id)  
DELETE /api/todos/:id (remove todo item with id)  

*POST* and *PUT* require also data in JSON format.

## Example of todo item:
{  
    id: 1,  
    title: "example of title",  
    description: "example of description",  
    completed: false,  
    \_id: "ObjectId('...')"  
}  
