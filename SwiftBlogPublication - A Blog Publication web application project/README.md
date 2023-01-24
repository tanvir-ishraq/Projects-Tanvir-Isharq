# SwiftBlogPublication - A Blog Publication web application project
## instructions: 
run:

python manage.py makemigrations

python manage.py runserver

## Description
###### using model:
* Deleting author deletes all correspoding blog posts. Cascade.
* Updates time if author edits a blog post.
* Ordering blog posts according to time published.
* Coded new serach fuctionality and filter fuctionality on admin dashboard to enhance management of blog posts.


* Using Template inheritance with base design to reduce code redundancy.
* Use bootstrap to be faithul to responsiveness.

## Created with:
django-admin startproject project

python manage.py startapp app
  
  
note: will require internet connection for frontend UI. uses CDN for frontend UI   
