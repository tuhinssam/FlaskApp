### This is an interactive micro blogging application written using Flask Framework. Following are the functionalities, I have incorporated in the project:
### Already Implemented
1. Registration with password hashing
2. Login after registration, by verifying hashed password
3. User can write a Blog in RichTextFormat and update, delete the blog
4. User can change the password and basic information
5. User can view all blogs writen by others
6. User can see other blogger information

### Other Details:
1. MySQL is used for database
2. Flask_bootstrap is used for frontend design
3. flask_ckeditor module used for rich text formatting experiance
4. workzeug.security used for password hasing and de-hashing
5. used python logging for logging module for logging purpose

### How to use:
1. Create a Virtual env using command 'virtualenv {venvname}'. Move into the virtual env using '{venvname}\Scripts\Activate'
2. install all the requirements using "pip install -r 'requirements.txt'"
3. run the project using 'python app.py'
4. Modify the database related information in db.yaml
5. I will share db dump shortly

### Whats Next:
Next is to Build API to access the information:
1. Basic authentication using API
2. Read (GET) user Blogs after authentication
3. Create (POST) User Blogs after authentication
4. Update (PUT) User Blogs after authentication
5. Delete (DELETE) User Blogs after authentication
6. Get(GET) user details


### development is in progress...
