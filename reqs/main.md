# The Requirements


# Functional requirements
## CRUD for automatic interaction
This allows applications to interact with the service to execute CRUD operations on files.
### Create (POST)
* Uploads a new file
* Parameters
    * File
* Returns
    * HTTP status code
    * 3 URLs
        * Read URL
        * Update URL
        * Delete URL

### Read (GET)
* Reads file
* Returns
    * Returns file
    * HTTP status code

### Update (PATCH)
* Updates file
* Parameters
    * Valid Update URL
    * New file
* Returns
    * HTTP status code

### Delete (DELETE)
* Deletes file
* Parameters
    * Valid Delete URL
* Returns
    * HTTP status code

## CRUD for human interaction
This allows a user to interact with the service through a web UI to execute CRUD operations on files.
