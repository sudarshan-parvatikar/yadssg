# The idea
The project is to be designed in such as way, so that it can be used locally (on the machine and then push to github pages) and online (on personal site). As such below are the features/things to be done (not necessarily in order of importance).
 

## Common for offline and online
* Create a basic structure
* Ability to customize blog themes
* Code editor (write blog in md) + live rendering (similar to that of [Bookstack's](https://user-images.githubusercontent.com/21090563/45772099-b6a12680-bbfb-11e8-81ed-7c3c16e69a4c.png))
* OAuth / similar auth support
* Make optimizations to support ipython notebooks, etc, for Data Science use.
* Setup Travis CI / any other CI.
* Import blogs from Jekyll, markdown or wordpress.

## Offline use 
* generate md files for blogs (for use in github pages)
* a sqlite db to store username:password, oauth creds, etc.

## Online use
* multi user auth
* RSS feed support
* Render blogs using Django
* Store blogs in DB (psql/mysql)

