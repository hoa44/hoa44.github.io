# Overview

This is an example one-pager site that prospective job-seekers can use to quickly
highlight their accomplishments and make an introduction. It can be hosted for free using
GitHub Pages (as a Jekyll static page).

This is based on a heavily pared-down version Jerome Lachaud's [Freelancer Jekyll theme](https://github.com/jeromelachaud/freelancer-theme).
Jerome's original theme is well-suited for designers to easily assemble a portfolio site of their visual work; this
is a prose-centric version tailored to software developers. [formspree](http://formspree.io/) is used for the contact form.

My page is totally based on Chuck Groom's One Page Bio.

## Demo

- View Chuck's example one-pager [here](http://chuckgroom.com/onepage-bio/)
- View My example [here](https://test.com)

## How to use

 - Place your photo in `/img/profile.png` to have a picture of yourself on the page, this is optional.
 - If you are like me and don't want to have a picture on your page comment out this following line the `_layouts/default.html` file.
 ``` html
 <!-- <img class="profile-img" src="img/profile.png" alt="{{ site.name }}"> -->
 ```
 - (Optional) Update the favicon `/img/icon.png`
 - Edit `_config.yml` to give your name, email address, social media contacts, etc. You can also update the color scheme.  I have added a GitHub glyphicon incase you have a GitHub Repository with code you want to highlight.
 - Edit content in `/_includes/about_me.html` and `/_includes/interests.html`
 - Create a new GitHub repo according to the instructions [Basic GitHub Pages Instructions.](https://pages.github.com/) Here are the longer [instructions for GitHub Pages](https://help.github.com/en/categories/github-pages-basics.)
 - GitHub Pages directly supports the Jekyll static site genetator that this one page bio is based on.  [Read about Jekyll](https://jekyllrb.com/)
 - Jekyll installation Instruction are [here.](https://jekyllrb.com/docs/installation/).

## Screenshot

![screenshot](https://raw.githubusercontent.com/chuckgroom/onepage-bio/master/screenshot.png)


