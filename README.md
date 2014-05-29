# UNH-CORE Jekyll-Bootstrap site

## Dependencies 

To be able to build and work on the site locally, you will need to be running Linux or Mac OSX, with
  * Ruby
  * Jekyll
  * kramdown
  * rake

Of course, all text files can be edited directly from the repository on GitHub, but you will not
be able to preview changes.

## To view locally
In a terminal, execute

    jekyll serve --watch

Then, in a browser, navigate to http://0.0.0.0:4000/. As Markdown (*.md) and HTML files are edited,
the local server will update the site automatically. 

## Creating a new post
In a terminal, execute

    rake post title="This is the title" category="insert-category-here"

## To-do
  - [ ] Add posts for all papers, presentations, datasets, projects, etc.
  - [ ] Add content to `About` and `Contact` pages.
  - [ ] Reorganize `Facilities` page and make subpages for field sites.
