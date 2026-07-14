# Student Management System using Django REST Framework:
Developed a RESTful Student Management System using Django and Django REST Framework. The application supports CRUD (Create, Read, Update, Delete) operations for student records through REST APIs. Implemented serializers, URL routing, views, models, and SQLite database integration for efficient data management

# Features
             Add Student (POST)
             View All Students (GET)
             View Single Student (GET by ID)
             Update Student (PUT)
             Delete Student (DELETE)
             Django Admin Panel
             REST API Endpoints
             SQLite Database

# Architecture

Client (Postman / Browser)
          ↓
       Django URLs
          ↓
        Views.py
          ↓
   StudentSerializer
          ↓
      Student Model
          ↓
      SQLite Database
