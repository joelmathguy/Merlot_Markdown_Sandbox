ddd 2021-08-25 TIME: 16:43:22
----------------------------------------------------------- 
ddd 2021-08-25 TIME: 16:43:25
It seems that the jekyll merlot them is responsible for putting the
project name on top.  It seems that I'd have to modify this theme
or shop around for another to modify this...
----------------------------------------------------------- 
ddd 2021-08-25 TIME: 16:54:09
About to follow instructions on https://github.com/pages-themes/merlot
to use Merlot theme (which is different from what it is now);

HERE ARE THE INSTRUCTIONS:

Usage
To use the Merlot theme:

Add the following to your site's _config.yml:

remote_theme: pages-themes/merlot@v0.2.0
plugins:
- jekyll-remote-theme # add this line to the plugins list if you already have one
Optionally, if you'd like to preview your site on your computer, add the following to your site's Gemfile:

gem "github-pages", group: :jekyll_plugins
Customizing
Configuration variables
Merlot will respect the following variables, if set in your site's _config.yml:

title: [The title of your site]
description: [A short description of your site's purpose]
Additionally, you may choose to set the following optional variables:

show_downloads: ["true" or "false" (unquoted) to indicate whether to provide a download URL]
google_analytics: [Your Google Analytics tracking ID]

