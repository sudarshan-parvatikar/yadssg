# yadssg
Yet Another Django Static Site Generator


## What is this?
This project aims to create a static site generator, similar to [Jekyll](https://jekyllrb.com/). The plan is to create a project that can be used primarily to manage personal blogs that can be hosted on github pages and like, whilst, if needed, can be hosted on a private server to create and manage blogs on that server and/or on github pages.  

## Why another static site generator ????
Well, tbh, it's because I don't know Ruby (as of now). I wanted to customize Jekyll themes, but as a Python user, I thought it would be easier to do it via Jinja like syntax and add themes. Furthermore, as an aspiring Data Scientist, I was really impressed by simple, yet powerful blogs like the one by [Christopher Olah](https://colah.github.io/). That's the gist of it.

## Is it only Django?
Well, I mean, maybe some JS and CSS is definately needed. Will update as the changes come.

-------

## Installation Instructions
1. Install `virtualenv` using:
```
python3 -m pip install --upgrade virtualenv
```   
This creates an isolated environment, virtualenv is used to manage Python packages for different projects.

2. After installing `virtualenv` create a new virtualenv and activate it. Run:  
```
virtualenv -p python3 venv
source venv/bin/activate
```  
The name of the virtualenv is `venv`. Upon activating it, you'll get a `(venv) ` on your terminal prompt. 


3. Next, install the python packages needed using:
 ```
 python3 -m pip install -r requirements.txt
```

4. Check if everything is running. Go to `yaddsg` and run:  
 ```
 python manage.py runserver
 ``` 
 If the index page opens w/o error @ `http://localhost:8000/` or `http://127.0.0.1:8000/`, then everything is working fine. If there's an error, check the issues page to see if it's documented. If there isn't one, create one, whilst giving as much as specifics as possible.


## Interesting Links
* [Readme Driven Development](https://tom.preston-werner.com/2010/08/23/readme-driven-development.html) by Tom Preston-Werner. 

