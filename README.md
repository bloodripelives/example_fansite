This is an example version of how I made my fic archive site that you can mess with or drop your own fic into to make it yours. 

To mess with the menu on the main page, go to data/menu.toml

To add something to the main page that is static and it makes more sense to put in HTML, like a webring button, go to themes/nostyleplease/layouts/index.html

To change the site title, url, etc, go to hugo.toml

To put your own fic on here, go to content/fics and replace the existing files with your own fic in markdown format, following the format in the examples to set metadata. If you're coming from AO3, the easiest way to do this is probably to download your stories in html and use an html to markdown converter online to get them in markdown. 

If you want to change how the site generally looks, go to themes/nostyleplease/assets/css/main.scss

To mess around with how fic and lists of fic display, go to /themes/nostyleplease/layouts/fics and uhhh well I'm not really sure I'm a bit fuzzy on the details of how hugo works beyond having set up my thing and knowing how to update it. But I think it happens here

To make new tags in existing taxonomies (fandom, category) you just have to add them to a new fic. To mess with what *kinds* of categories you have, er, mess around with stuff I guess? I suspect it's possible to make significantly more detailed categorization structures than I have here but I don't really know how and I set this up a while ago so I kind of forget how I did it. Look up taxonomies in hugo and get better at it than me...

To see how it looks, install hugo: https://gohugo.io/installation/ Then, from the top level directory, run 'hugo server' and follow the link it gives you to see how the site would look. When you're happy with it, run `hugo` and a version of your website ready to be uploaded to the internet will appear in the public folder. Personally, I use rsync to upload it to my server which I included here as the script push.sh. Or just upload it however neocities or whatever else you're using handles file uploads. 

If you notice that it's weird that there's duplication between the stuff in the themes folder and stuff outside of it you're correct. I tried migrating all the stuff in themes into the "main" part of the directory structure but it broke stuff I couldn't figure out. Disclaimer: I'm bad at this and doing it my way is probably bad. 

If you want to ask me questions or tell me how to actually use this thing come find me on the fediverse https://federatedfandom.net/@bloodripelives or email me tei@fastmail.org 
