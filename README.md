# Welcome 

Welcome to the repository for the website workshop. The objective for this repo is to hold useful link and resources for developing your 
[online presence](presentations/01-online.Rmd).

# Department website

You can edit your personal departmental site on http://www.stat.iastate.edu/login/ and log in using your single sign-on credentials.

Next, click on “My Public Profile” in the top bar, and enter your information (including your current office number) in Snedecor. 

There is also a place to enter a bio, link your website, and upload a CV. 

Note, that you do not need to add a phone number, but if you do, please understand that it will be published on the website. 

Please upload a profile pic, add your education history, and add any other information you would like to include.


# Personal website

## Example websites

[Jekyll-Bootstrap/Github Pages](http://jekyllbootstrap.com/)

- [Jarad Niemi's website](https://www.jarad.me/) and its [code](https://github.com/jarad/jarad.github.com)

[Blogdown/Netlify](https://www.apreshill.com/blog/2020-12-new-year-new-blogdown/)

- [NCCC-170 website](https://nccc170.netlify.app/) and its [code](https://github.com/NCCC-170/nccc170-website)

[Blog Down/Netlify] ~ following tutorial in Wowchemy.
 - [Fede's website](https://fveneri.netlify.app/)
 - [Ricardo's website](https://www.ricardobatista.com/)
 - [ISU](https://www.stat.iastate.edu/)
 - [Laura's website](https://lauraziegler.netlify.app/)
 
 
## The netlify route for deployment.

Create accounts
* [GitHub](https://github.com/)
* [Netlify](https://www.netlify.com/)

Once the account is created, we can choose a template from here:
 * [Wowchemy](https://wowchemy.com/): Instruction to deploy on Netlify included.
Following the steps, we will have created a Netlify site + a repo in Github.
Take a look at your site, does it work?
## The github pages route for deployment.
	?
## Can I edit my site? Yes
Once the repo is created, we can modify it. Some options include:
-	[Using Hugo your PC](https://wowchemy.com/docs/getting-started/install-hugo-extended/).
-	[Using CMS from your site](https://wowchemy.com/docs/getting-started/hugo-cms/)
-	Changing the code in Github directly. 
-	Using R studio, then push changes to Github. ( I used this option)

## What can I edit on my site? A lot, but is a bit confusing.

The site is built around [Widgets]( https://wowchemy.com/docs/getting-started/page-builder/). 
You could create your own or use the ones already made.

### Editing the Bio and welcome page.
In your repo (or local copy), search for ‘content/authors/admin/_index.md’

There you can change:

1. your education: Edit the text below -Education to show in About widget
2. add a short bio: Edit the text at bio:
3. add a Long bio for the welcome page: Edit the text at the bottom of the page.
4. Change the main picture: in the author folder, there is a file called 'avatar.jpg'. You can replace this with your profile pictures by uploading a new file with the same name. 

### Simplify your welcome page (remove the wowchemy welcome).

The first thing that appear in your site is a demo + a hero widget. We can deactivate those.

1.	Deactivate the green demo page.
In your repo (or local copy), search for ‘content/home/demo.md’
And toggle: active = false   on line ~8, this will deactivate the green demo page. 

2. You may want to change the top navigation button, meaning the links to each part of your site.
	You can change that in the configuration file withing config folder.
	Config/menus.yaml

So here, you will have something like this
-	 name: About
 	       url: '#about'
   	       weight: 10
The name is what you will display in the navigation bar, and the url is what you want to be linked to.
	weight probably has something to do with the size. 


### Remove a section (eg talk tags etc.) 

1. Search for the markdown file for the section you want to delete eg ‘content/home/talks.md’
2. Add a line active: false  below the line headless: true

### Change your work experience.

### Adding your CV.

### Changing your email/contact info.

### Creating a publication.
### Creating a project.
### Other cool stuff.
## Can I import some stuff in other languages? [Apparently yes]( https://wowchemy.com/docs/import/)
