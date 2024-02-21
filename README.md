# Microblog using Flask and Python

Welcome to Microblog, a feature-rich microblogging application built with Flask and Python.

## Overview

The Microblog application includes a range of features for a seamless and engaging user experience:

1. **User Authentication:**

   - User registration and login.
   - Password recovery options.

2. **Profile Management:**

   - User profiles with details and follower information.
   - Profile editing functionality.

3. **Blog Posts:**

   - Create, edit, and delete blog posts.
   - Personalized timelines for each user.

4. **Social Interaction:**

   - Follow other users to see their posts.
   - Explore page for discovering posts from all users.

5. **Advanced Features:**

   - Search functionality for finding specific posts.
   - Live translation of blog posts into different languages.
   - Private messaging between users.

6. **Advanced Interaction:**

   - Hover-over user details on the mouse.
   - Real-time notifications for new messages.

7. **Background Tasks:**
   - Export user posts as a data file in the background.

## Installation

To run Microblog on your local machine, follow these steps:

```bash
# Clone the repository
git clone https://github.com/jbizima/microblog-api.git

# Navigate to the project directory
cd microblog

# Create a virtual environment and activate it
python -m venv venv
.\venv\Scripts\activate  # for Windows

# Install dependencies
pip install -r requirements.txt

# Run the application
flask run
```

## API Endpoints

1. **/api/posts**

   - **Description:** Retrieve all blog posts.
   - **Method:** GET

2. **/api/users/<username>**

   - **Description:** Get user information.
   - **Method:** GET

## Authors

- Emelyne Uwimbabazi - [Github](https://github.com/emelyne1234)
- Fred Shema - [Github](https://github.com/Ndi-Shema)
- Joshua Bizima - [Github](https://github.com/jbizima)
- Beline Marie Mugisha Ahujabe - [Github](https://github.com/Mugisha-Beline)
