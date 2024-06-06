# Security / Safety
* How to limit spam?
  * Check operations per IP
  * Limit overall operations
  * Limit disk usage (POSTs)
 * Consider Cloudflare https://www.cloudflare.com/plans/free/

# Functional
## File name or no file name
* The user might want to see the file names in his owerview in order to know what the files contain
* The user might want to download a file with the initial upload name of the file
* But it's oftentimes interesting to display the file automatically in the browser (which seems not to happen, if the server returns the file name -> see explanation below)
* -> Test different option, deepen research and decide

### How to pass the file name
The HTTP response itself does not inherently include the filename of the JPEG or any file being sent. However, a server can optionally include the filename in the headers using the Content-Disposition header, which is often used to suggest how the content is to be handled by the client.

Here's how the Content-Disposition header can be used to specify the filename:

Content-Disposition: attachment; filename="example.jpg"
This header suggests that the content should be treated as an attachment (implying it should be downloaded rather than displayed) and provides a filename for the file when it is saved. If the server includes this header, the client (such as a web browser) typically uses the specified filename when saving the file to disk. If this header is not present, the client might use the last part of the URL or generate a new, arbitrary filename based on other factors.

Therefore, while the filename can be included in the HTTP response headers, it is not a default part of the response and is entirely up to the server's implementation to provide it.
