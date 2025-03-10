---
title: How to create this page
categories: pages github
excerpt: |
  First step is create your **own acount** on [GitHub](https://github.com/). Then visit the style you want to use and _(Remeber to do Fork of repository to help the comunity)_ 
feature_text: |
  ## How to create this page
  Fast guide to create a github pages
feature_image: "https://picsum.photos/2560/600?image=733"
image: "https://picsum.photos/2560/600?image=733"
---

### First steps
First step is create your **own acount** on [GitHub](https://github.com/). Then visit the style you want to use and
_(Remeber to do Fork of repository to help the comunity)_
* [Hacker-Blog](http://github.com/tocttou/hacker-blog).
* [Neumorphism](https://github.com/longpdo/neumorphism).
* [Alembic](https://github.com/daviddarnes/alembic).

<!-- more -->

### Second steps
Second step is change the name of the repository: Go to the `settings` and then give the name you want ending with `<your-name>.github.io`

### More of usage

#### Local Build
If you want to see the changes before puching the blog to GitHub, do a local build.
1. Add `gem "alembic-jekyll-theme"` to your Gemfile to add the theme as a dependancy
2. Run the command `bundle install` in the root of project to install the theme and its dependancies
3. Add theme: alembic-jekyll-theme to your _config.yml_ file to set the site theme
4. `bundle exec jekyll serve`

#### Update your local data
When you have all the local change finished, you can update your web following this steps:
1. `git add .`
1. `git commit -m "<name-of-update>"` This show you the change you will update.
1. `git push -u origin` This will require your name user and your token-password. [Crear token-password](https://docs.github.com/es/authentication/keeping-your-account-and-data-secure/creating-a-personal-access-token)
