# The Requirements
# Functional requirements
## CRUD operations (automatic)
| Operation  | Purpose  | HTTP Method | Parameters | Return |
|------------|------------|------------|------------|------------|
| Create | Upload new file | POST | New file | Status, 4 URLs (Master, Read, Update, Delete) |
| Read | Read existing file | GET | Read URL | Status, file |
| Update | Update existing file | PUT | Update URL, new file | Status |
| Delete | Delete existing file | DELETE | Delete URL | Status |
| Master | All URLs of file | GET | Master URL | Status, 4 URLs (Master, Read, Update, Delete) |

## CRUD operations (human)
| Operation  | Purpose  | GUI | Parameters | Return GUI |
|------------|------------|------------|------------|------------|
| Create | Upload new file | Upload button | New file | Status, Master GUI |
| Read | Read existing file | Downloads or displays file in browser | Read URL | Status, File |
| Update | Update existing file | Link to current file, Upload button | New file | Status, Update GUI, status |
| Delete | Delete existing file | DELETE | Delete command | Status |
| Master | All URLs of file | GET | Master URL | 4 URLs (Master, Read, Update, Delete) |


