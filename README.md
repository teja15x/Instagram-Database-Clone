# Instagram Database Clone
A MySQL-based database schema designed to emulate the core functionality of Instagram. This project provides a structured representation of a social media platform, allowing users to post photos, engage with content through comments and likes, follow other users, and apply tags to photos.

# Introduction
This project lays the groundwork for developing a simplified Instagram-like social media application. It focuses on designing a robust and efficient database schema that captures essential user interactions and relationships commonly found in social networking platforms.
Whether you are a developer exploring backend database design or someone seeking to understand the underlying data structure of a social media app, this project provides a clear, well-documented, and scalable foundation.

# Database Schema Overview
The schema is composed of the following core tables:

1.users – Stores user profiles, including unique usernames and account creation timestamps.
2.photos – Contains image URLs, user associations, and timestamps of uploads.
3.comments – Records user comments on photos, linking each comment to both the user and the photo.
4.likes – Tracks user likes on specific photos.
5.follows – Represents follower–followee relationships between users.
6.tags – Maintains unique tag names used to categorize photos.
7.photo_tags – Establishes a many-to-many relationship between photos and tags.
Each table is carefully designed to maintain data integrity using foreign key constraints and optimize query performance through the use of appropriate indexing strategies.
