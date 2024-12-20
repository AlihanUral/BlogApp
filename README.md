# BlogApp

Description

“My Blog” is a web-based blogging platform built with Python, Flask, and Bootstrap. It allows users to create, read, update, and delete blog posts. The application includes user authentication, allowing users to register, login, and manage their posts. It is a simple blogging system with a user-friendly interface.

Features
	•	User authentication (Login and Registration)
	•	CRUD (Create, Read, Update, Delete) operations for blog posts
	•	User-specific post management (edit and delete own posts)
	•	Responsive design using Bootstrap
	•	Flash messages for feedback on user actions

Technologies Used
	•	Python: The backend of the project is built with Python and Flask.
	•	Flask: Web framework used to create the backend API.
	•	Bootstrap: Frontend framework for responsive design and UI components.
	•	SQLite: Database for storing user information and posts.
	•	CSS: Custom styles for enhanced visual appeal.

 How It Works
	•	Home Page (index.html): Displays a list of blog posts. If a user is logged in, they can create new posts or log out.
	•	Post Page (post.html): Displays a single blog post with content and metadata such as author and date posted.
	•	Login and Register Pages (login.html, register.html): Allow users to log in or register for an account.
	•	Create Post Page (create_post.html): Users can create new blog posts.
	•	Edit Post Page (edit_post.html): Users can edit their own posts.
	•	Database: Stores user and post information. Users can only edit or delete their own posts.

CSS Styles

The custom CSS file (styles.css) is used for enhancing the appearance of the application. It includes styles for the navigation bar, forms, buttons, and layout adjustments for mobile responsiveness.

Flash Messages
	•	Login: Displays success or error messages based on login attempts.
	•	Register: Shows messages for successful registration or errors (e.g., if the username is already taken).
