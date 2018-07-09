# Content Management System
The Content Management System is a full stack web application using HTML, CSS, Bootstrap, JavaScript, and jQuery for the front-end, Java and the Spring framework for the back-end, JSP's and servlets for server-side, and MySQL for the database.

## Overview 
The application we would like you to create is a blog and content management site.  A small company has decided to engage your team for this project.  Like many clients, this firm has only a vague idea of what the actual requirements are.  The initial specification is attached above - you will most certainly need to get clarification from the client.  Your instructor will assume the roles of client, project manager, tech lead (when needed), and (of course) instructor.

## Content Management Specs Sent By the Client
I’m a small company owner that wants to blog to the world to help generate publicity. My needs
are small:
- Give me a way to display my blog posts to everyone who comes to my site.
- Give me a way to enter my blog posts so that only I can add them.

Now, I don’t want to have to write HTML in my blog posts. Could you give me a way to write my posts in an editor like Word? I hear there’s something called TinyMCE.

I need a way to add static pages. Again, I want the world to view the pages, but only I can write these pages. Remember, I don’t like writing straight HTML at the end of the day, so if you can hook me up with an editor that lets me write rich text and post images, that would be awesome.

I am hiring someone to handle my marketing and blog posts. So, I need the ability to let them post as well. But I want to be able to approve their posts when they’re made.

I also need the ability to schedule my posts and also make them expire on their own? For example, I may make a post talking about my monthly specials, and I wouldn’t want that post to show up after that month. Maybe give me a way to set an expiration date that then prevents the post from being shown after that date.

## Requirements Derived as a Team
- Must be a content management system
- Must allow the creation of different types of users
- When registering → user type is automatically registered as contributor
  - Admin: Full management rights
    - Add, edit and delete  posts
    - Posts created are automatically approved 
    - Create, edit, and delete static pages to be used throughout the site
    - Set posts to publish at a later date
    - Set posts to expire
    - Manage users 
      - Approve posts created by contributors to publish
      - Edit and delete other user’s posts
      - Promote other users to admin or demote to contributor
  - Contributor: Limited management rights
    - Add posts subject to approval by admins 
    - Edit their own posts only
    - Set posts to expire
- Must allow the creation of blog posts and static pages through an in-browser editor
  - Static pages
    - Do not contain categories or tags
    - Only admin can create static pages
    - Static pages are added to the navigation bar
    - Not dynamic, only show text 
  - Blog Posts
    - Contain categories and tags
    - Have only 1 author (admin or contributor)
    - Can be scheduled for publish
    - Dynamic 
    - Can expire
    - Expiration date can be set by admin or contributor 
- Must allow Blog posts to be sorted by Category and Tags
  - Categories
    - Each blog post has only 1 category
    - Categories contain multiple blog posts
  - Tags
    - Each blog post can have multiple tags
    - Tags can be attached to multiple blog posts


