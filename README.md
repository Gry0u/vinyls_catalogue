# Music collection management application
Thought mainly for people having registered their music collection on
[Discogs](https://www.discogs.com/),
this web application fulfills the following functions:
- *optional: Download user's collection stored on
[Discogs](https://www.discogs.com/)*
- User login/logout
- Create, add, edit, delete depending on user's  specific rights:
  - Genre
  - Album
  - Song
- Authentification and authorization via 3rd party service (**Google sign in**)

## Getting started
1. Set up virtual machine:
  - Install Virtual Box
  - Install Vagrant
  - [Download or clone](https://github.com/udacity/fullstack-nanodegree-vm)
  the virtual machine configuration files
  - Open terminal
  - Change to the `\vagrant` directory
  - Download or clone this repository in this directory
  - Start the virtual machine: `vagrant up` then `vagrant ssh`
2. Set up the back-end SQL database  
*You will need a
[developer account](https://www.discogs.com/settings/developers)
and a Discogs API token.  
If you don't want to register as a developer or
don't have a Discogs account, skip this step and use the initial*
`vinyls.db` *file instead.*
  - Run `python addcollection.py`
3. Start the application
  - Run `python views.py`
4. Access the application
  - Go to `localhost:5000` in your web browser  

## Resources
- [Python](https://www.python.org/): application's code  
- [sqlalchemy](https://www.sqlalchemy.org/) python toolkit and [SQlite](https://sqlite.org/index.html) engine: back-end database
- [Discogs](https://www.discogs.com/)
-[OAuth ](https://oauth.net/)
