#RESTful ROuting

##Introduction
* Define REST and explain WHY it matters
* List all 7 RESTful routes
 - Index - /dogs - GET - List all dogs
 - New - dogs/new - GET - Show new dog form
 - Create - /dogs - POST - Create a new dog, then redirect somewhere
 - Show - /dogs/:id - GET - Show info about one specific dog
 - Edit - /dogs/:id/edit - GET - Show edit form for one dog
 - Update - dogs/:id - PUT - Update a particular dog, then redirect somewhere
 - Destroy - /dogs/:id - DELETE - Delete a particular dog, then redirect somewhere


* Show example of RESTful routing in practice


REST - Representational State Transfer - a mapping between HTTP routes and CRUD
    - a pattern for defining our routes, its a way of mapping HTTP routes and CRUD together
    - a pattern of routes that we can follow
    
    
Example a blog    
    
CREATE - /Blogs
READ - /allBlogs
UPDATE -/updateBlog/:id
DELETE - /destroyBlog/:id
