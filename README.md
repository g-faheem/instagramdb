# Created an instagram database clone using PostgreSQL
This repository contains the PostgreSQL database schema and sample data for an Instagram-like project, created as part of the "SQL and PostgreSQL: The Complete Developer's Guide" course. The database models key features of an Instagram application, including user management, posts, comments, likes, and followers.

About the Database
The Instagram Database is structured to simulate core functionalities of an Instagram-style application. It includes tables for managing users, posts, comments, likes, and followers, supporting key interactions and activities on the platform.

Features and Functionality:
Users Table
Stores user details like username, email, password, profile information, and registration timestamps.

Posts Table
Tracks posts created by users, including captions, media URLs (images/videos), and timestamps.

Comments Table
Stores comments made by users on posts, linked to both the post and the user who commented.

Likes Table
Records which users liked which posts, enabling multiple users to like a post and multiple likes for a post.

Followers Table
Manages user follow relationships, allowing users to follow or unfollow other users.

Usage
To restore this database, use the following command:

bash
Copy
Edit
psql -U your_username -d your_database < instagram_database.sql
Replace your_username and your_database with your PostgreSQL credentials.
