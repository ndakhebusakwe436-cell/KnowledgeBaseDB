# Knowledge Base Database

## Project Description
This project contains the database schema for a Knowledge Base Management System.

## Tables
- Users
- Roles
- Articles
- Categories
- Tags
- ArticleTags
- Attachments
- Revisions
- Comments

## Database Relationships
- One Role can have many Users.
- One User can create many Articles.
- One Category can contain many Articles.
- One Article can have many Comments.
- One Article can have many Attachments.
- Many Articles can have many Tags through ArticleTags.

## Technologies Used
- SQL Server
- SQL Server Management Studio (SSMS)
- GitHub
- Visual Studio Code