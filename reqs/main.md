# The Requirements


# Functional requirements
## CRUD for automatic interaction
This allows applications to interact with the service to execute CRUD operations on files.
### Create (POST)
* Allows to upload a new file
* Paramaters
    * File
* Returns
    * Status
    * 3 URLs
        * Read URL
        * Update URL
        * Delete URL

### Read (GET)
* Returns
    * Returns file
    * HTTP status code

### Update (PATCH)
* Allows to uodate file
* Paramters
    * Valid Update URL
    * New file


### Delete (DELETE)


## CRUD for human interaction
This allows a user to interact with the service through a web UI to execute CRUD operations on files.
