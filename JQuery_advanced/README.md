# Project Setup

## Summary
The article provides instructions for setting up a development environment using `json-server`, creating an HTML file to display posts, and using jQuery to interact with the server.

## Key Points
- **Install `json-server`**: Use npm to install `json-server` and run it with a provided `db.json` file.
- **Create HTML File**: Set up an HTML file (`10-index.html`) that imports jQuery via CDN.
- **Define Functions**: Implement `addPostRow` to append post details to the body and `listPosts` to fetch posts from the server and handle errors.
- **Use jQuery**: Utilize jQuery's `get` function to make AJAX calls and call `listPosts` when the page loads.