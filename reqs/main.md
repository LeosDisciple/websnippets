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

### Differentiation to automatic interaction
After creation of a file, the URLs are created. 
If a user enters them in a browser, the browser executes a GET request. 
for GET requests on the 3 ULRs the following happens:
* Read URL -> Returns the file
* Update URL -> Shows Update GUI
* Delete URL -> Shows Delete GUI

### Create
* Uploads a new file
* Provides GUI with the following:
    * Instructions
    * Upload button
* Return GUI
    * Status of operation
    * 3 URLs
        * Read URL
        * Update URL
        * Delete URL

### Read (same as automatic process)
* Returns file
* Returns
    * Returns file
    * HTTP status code
        
### Update
* Updates file
* Provides GUI with the following:
    * Instructions
    * Link to current file
    * Upload new file button
* Return GUI
    * Returns to update GUI
    * Displays status of operation

### Delete
* Deletes file
* Provides GUI with the following:
    * Instructions
    * Link to current file
    * Delete file button
* Return GUI
    * Displays status of operation

