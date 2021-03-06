# mod_autoindex.oh
Visual enhancement for apache's directory listing.

![mod_autoindex.oh screenshot](http://s17.postimg.org/ksod9t0cf/Screen_Shot_2014_10_21_at_19_34_34.png)

## Introduction
I use my `Sites` folder on OSX on a daily basis, so I felt the need to make the file listing a nice and cosy place. Can be used for any Apache file listing.

## Installation
Place the files found in this repository in whatever folder you want to enhance with `mod_autoindex.oh`

Assume you want to share a folder called `files`
- Download `mod_autoindex.oh` and unzip it in the `files` folder. Alternatively you can use shell go to your `files` folder and check out this project there `git clone git@github.com:meodai/mod_autoindex.oh.git`

- edit the `.htaccess` file. And replace all `($folder)` with `files`.
  *ex. `HeaderName /($folder)/.theme/header.html` should become `HeaderName /files/.theme/header.html`*

- Share you folder!

## Customize
Feel free to edit all the files. In order to style the project differently. Edit `.theme/style.css`

On OSX 10.9 and 10.10 you can get your Sites folder back using this [tutorial](http://coolestguidesontheplanet.com/get-apache-mysql-php-phpmyadmin-working-osx-10-10-yosemite/). After that just put the `mod_autoindex.oh` files in your Sites folder, and replace `($folder)` with `~yourusername`.


## Contributors & Credits
- [All the .htaccess magic](http://perishablepress.com/better-default-directory-views-with-htaccess/)
- [Icons: predawn theme](https://github.com/jamiewilson/predawn/tree/master/icons)
