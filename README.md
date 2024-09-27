"# blogging-website"
# Overview
This is a simple blogging platform where users can write, edit, and publish their blogs. The project is built using HTML, CSS, and JavaScript, with Firebase as the backend to store blog data.
# Features
- Create and Publish Blogs: Write and publish your blog posts.
- Image Upload: Upload images to include in your blog posts.
- Dynamic Blog Display: View all published blogs on the homepage.
# Technology Used
- HTML: Structure of the website
- CSS: Styling the website
- JavaScript: Adding interactivity
- Firebase: Storing blog data
# File Structure
Here’s what the project looks like:
```
/blogging-website
|-- /css           # Stylesheets for the site
|   |-- home.css
|   |-- editor.css
|   |-- blog.css
|
|-- /js            # JavaScript files
|   |-- home.js
|   |-- editor.js
|   |-- blog.js
|   |-- firebase.js
|
|-- /img           # Images used in the site
|   |-- logo.png
|   |-- header.png
|   |-- upload.png
|
|-- blog.html      # Blog editor page
|-- editor.html    # Homepage to view blogs
|-- home.html      # Page to write a new blog
```
# How to Run the Project
1. Clone the Repository:
   - Open your terminal and run:
     ```bash
     git clone https://github.com/yourusername/blogging-website.git
     cd blogging-website
     ```
2. Set Up Firebase:
   - Create a Firebase project at [Firebase Console](https://console.firebase.google.com/).
   - Add a Web App and copy the Firebase configuration.
   - Paste your Firebase configuration into `firebase.js`.
3. Open the Website:
   - Open `home.html` in your browser to start using the blogging platform.
