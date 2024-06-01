# The Requirements


# Functional requirements
## CRUD for automatic interaction
This allows applications to interact with the service to execute CRUD operations on files.
### Create (POST)
* Allows to upload a new file
* Returns
  * 

### Read (GET)


### Update (PATCH)


### Delete (DELETE)


POST
Creates a note (CREATE operator)
POST GET www.example.com/notes + JSON object creates a new task and returns its id
GET
Returns notes (READ operator)
GET www.example.com/notes returns all notes
GET www.example.com/notes/page/1 returns first page of all notes ("pagination")
GET www.example.com/notes/1 returns note with id "1"
DELETE
Deletes note (DELETE operator)
DELETE www.example.com/notes/1 deletes note with id "1"
PUT / PATCH
Updates note (UPDATE operator)
PUT / PATCH www.example.com/notes/1 updates + JSON object task with id "1"
Difference between PUT and PATCH:
PATCH is used to update an existing entity with new information. You can’t patch an entity that doesn’t exist.
PUT is used to set an entity’s information completely. PUTting is similar to POSTing, except that it will overwrite the entity if already exists or create it otherwise.


## CRUD for human interaction
This allows a user to interact with the service through a web UI to execute CRUD operations on files.
