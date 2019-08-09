---
title: "Replacing Wordpress with a static site sade with Hugo"
date: 2019-08-10T01:00:00+02:00
draft: false
tags: ["hugo"]
---
If you have a Wordpress website to document some projects you worked on but rarely post anything like I do, replacing it with a static website might just be the right thing for you. Compared to Wordpress a static website has multiple advantages:

*   You don't need to update it.

    To keep your Wordpress secure you regularly need to install security updates for themes, plugins and Wordpress itself. While it has an auto update feature, there is always the risk that an update could break something.

*   Speaking of security: A static website can't get hacked.

    Because the websever only serves static files and doesn't use any user input to render your site you don't have to worry that someone could exploit a vulnerability in the site to inject malicious code or do other nasty things. The only thing you have to keep secure is the webserver.

*   A static website can be put under version control.
    
    With a static website you don't have to worry about managing database backups anymore. Just put your files in a git repository. If your latest changes broke something, just revert them.

*   A static website can be redeployed easily.

    Want to switch your hosting provider or host your website on multiple servers? Just copy your files to a new webserver. Done.

A useful tool for building static websites is [hugo](https://gohugo.io). This open source tool takes markdown files and generates the necessary files. All you have to do is put them on a webserver. You can choose between hundreds of existing themes, customize them or create your own theme from scratch. This site for example uses the [Coder](https://themes.gohugo.io/hugo-coder/) theme.