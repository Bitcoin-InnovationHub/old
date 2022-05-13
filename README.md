# Bitcoin InnovationHub

The place to promote your Bitcoin projects. Where thinkers and makers team up to shape the future of a Bitcoin-based economy. Pitch your Bitcoin-only projects via GitHub Repositories which will then be hosted on this website to attract committed fellows. If you want to become a supporting fellow, browse through the listed  projects Browse through a [live demo](https://proud-alligator.cloudvent.net/).
Increase the web presence of your brand with this configurable theme.

The website is based on Hydra Template by [CloudCannon](http://cloudcannon.com/), the Cloud CMS for Jekyll.

[![Deploy to CloudCannon](https://buttons.cloudcannon.com/deploy.svg)](https://app.cloudcannon.com/register#sites/connect/github/CloudCannon/hydra-jekyll-template)

## Features

* Open Source content
* Pre-built pages
* Pre-styled components
* Blog with pagination
* Post category pages
* Disqus comments for posts
* Staff and author system
* Configurable footer
* Optimised for editing in [CloudCannon](http://cloudcannon.com/)
* RSS/Atom feed
* SEO tags
* Google Analytics

## Promote your ideas

1. Add your site and author details in `_config.yml`.
2. Add your Google Analytics and Disqus keys to `_config.yml`.
3. Get a workflow going to see your site's output (with [CloudCannon](https://app.cloudcannon.com/) or Jekyll locally).

## Develop with others

Bitcoin InnovationHub is a community project. 
Feel free to get push the development of this website by commiting changes and creating a Pull Request afterwards.

Install the dependencies with [Bundler](http://bundler.io/):

~~~bash
$ bundle install
~~~

Run `jekyll` commands through Bundler to ensure you're using the right versions:

~~~bash
$ bundle exec jekyll serve
~~~

## Editing

The Hydra Template is already optimised for adding, updating and removing pages, staff, advice, company details and footer elements in CloudCannon.

### Posts

* Add, update or remove a post in the *Posts* collection.
* The **Staff Author** field links to members in the **Staff** collection.
* Documentation pages are organised in the navigation by category, with URLs based on the path inside the `_docs` folder.
* Change the defaults when new posts are created in `_posts/_defaults.md`.

### Contact Form

* Preconfigured to work with CloudCannon, but easily changed to another provider (e.g. [FormSpree](https://formspree.io/)).
* Sends email to the address listed in company details.

### Staff

* Reused around the site to save multiple editing locations.
* Add `excluded_in_search: true` to any documentation page's front matter to exclude that page in the search results.

### Navigation

* Exposed as a data file to give clients better access.
* Set in the *Data* / *Navigation* section.

### Footer

* Exposed as a data file to give clients better access.
* Set in the *Data* / *Footer* section.
