# Code_Alpha-Task-2
Social Media Platform

##Overview
This repository contains the source code for a social media platform built using Django. The platform allows users to create accounts, post updates, follow other users, and interact with posts through likes and comments.

##Features
User Authentication: Users can sign up, log in, and manage their profiles.
User Profiles: Each user has a personal profile page with information and their posts.
Post Creation: Users can create and share posts with text and media.
Following System: Users can follow and unfollow other users.
Interactions: Users can like and comment on posts.
Feed: Users see a feed of posts from people they follow.

##Installation
Prerequisites
Python 3.8 or higher
Django 4.0 or higher
sqlite3 (or another database, as configured)

##Setup
Clone the Repository:
git clone https://github.com/yourusername/social-media-platform.git

Navigate to the Project Directory:
cd social-media-platform

Create and Activate a Virtual Environment:
python -m venv venv
source venv/bin/activate   # On Windows use: venv\Scripts\activ

Install Required Packages:
pip install -r requirements.txt

Apply Migrations:
python manage.py migrate

Create a Superuser:
python manage.py createsuperuser

Run the Development Server:
python manage.py runserver
The application will be accessible at http://127.0.0.1:8000/

##Usage
Homepage: View the latest posts and updates.
Profile Page: Access and edit your personal profile.
Feed: See posts from users you follow.
Create Post: Share new updates and media.
Follow/Unfollow: Manage your connections with other users.
Like/Comment: Interact with posts.

##Contributing
If you want to contribute to the development of this platform, please follow these steps:
Fork the repository.
Create a new branch (git checkout -b feature-branch).
Make your changes and commit them (git commit -am 'Add new feature').
Push to the branch (git push origin feature-branch).
Create a new Pull Request.

##License
This project is licensed under the MIT License - see the LICENSE file for details.
