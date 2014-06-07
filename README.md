# UNH-CORE Jekyll-Bootstrap site

## Contributing
### Getting started

It is recommended you are running Linux or Mac OSX to contribute. If running Windows, you can
[set up a Linux virtual machine using VirtualBox](http://www.instructables.com/id/Introduction-38/)

  1. Install [Git](http://git-scm.com)
  2. If you don't have one, create an account on [GitHub](https://github.com) and email a member of
     the [UNH-CORE organization](https://github.com/UNH-CORE) (e.g. Pete) your user name to be added.
  3. Open a terminal or command prompt in a folder you'd like to place the site subdirectory, e.g. your
     user home folder (Windows users can navigate to the folder in Windows Explorer and right click
     "Git bash here") and execute `git clone https://github.com/UNH-CORE/unh-core.github.io.git`
  4. Edit/create content inside the Markdown (`*.md`) files. See existing files in the `_posts` directory
     for examples. Also see the section below about creating a new post.
  5. Preview your changes locally (see section below).
  6. If your changes are acceptable, stage all for a commit by executing `git add -A` in the terminal, then 
     commit with `git commit -m "Your commit message goes here"`. A commit message should be descriptive
     of the changes made, e.g., "Create post about 2014 wave device experimental data set". 
  7. Upload or "push" your changes to the repository on GitHub by executing `git push`. 
  8. Repeat steps 4--7 as necessary. 

### Dependencies for local building and viewing

To be able to build the site locally, you will need to be running Linux or Mac OSX, with
  * Ruby
  * Jekyll
  * kramdown
  * rake

Of course, all text files can be edited directly from the repository on GitHub, but you will not
be able to preview changes.

### To view locally
In a terminal, execute

    jekyll serve --watch

Then, in a browser, navigate to http://0.0.0.0:4000/. As Markdown (`*.md`) and HTML files are edited,
the local server will update the site automatically. 

### Creating a new post
In a terminal, execute

    rake post title="This is the title" category="insert-category-here"

### To-do
See the [issues](https://github.com/UNH-CORE/unh-core.github.io/issues) on GitHub

## Deployment
We can either upload the entire site folder to the UNH server---via FTP for example---or get the UNH
domain name to point at GitHub servers. The latter is probably easiest, since updating the site would
require that a user simply `push` the changes to the repository, since GitHub builds the site on their
servers.
