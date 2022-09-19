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
 
## The netlify route for deployment.
First step is to create a free account here:
* [Netlify](https://www.netlify.com/)

Once the account is created, we can choose a template from here:
 * [Wowcehemy](https://wowchemy.com/): Instruction to deploy on Netlify included.
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
## What can I edit my site? A lot, but is a bit confusing.
The site is built around [Widgets]( https://wowchemy.com/docs/getting-started/page-builder/). You could create your own. 
### Fist steps: Editing the Bio and welcome page.
In your repo (or local copy), search for ‘content/authors/admint/_index.md’
There you can change your experience, add a short bio and your work experience.
### Second step: Simplify your welcome page (remove the wowchemy welcome).
The first thing that appear in your site is a demo + a hero widget. We can deactivate those.
1.	Deactivate the green demo page.
In your repo (or local copy), search for ‘content/home/demo.md’
And toggle: active = false   on line ~8, this will deactivate the green demo page. 
2.	Deactivate the hero landing page.
?
### Creating a publication.
### Creating a project.
### Other cool stuff.
## Can I import some stuff in other languages? [Apparently yes]( https://wowchemy.com/docs/import/)
