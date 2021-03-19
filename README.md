# Justice

Law firm themed business template for Hugo. Browse through a [live demo](https://loved-wood.cloudvent.net/).
Increase the web presence of a law firm or business with this configurable theme.

![Justice template screenshot](images/_screenshot.png)

Justice was made by [CloudCannon](https://cloudcannon.com/), a Jamstack platform for the whole team.

## Features

* Contact form
* Pre-built pages
* Pre-styled components
* Blog with pagination and category pages
* Disqus comments for posts
* Author system
* Configurable footer
* Optimised for editing in [CloudCannon](https://cloudcannon.com/)
* RSS/Atom feed
* SEO tags
* Google Analytics

## Setup

1. Add your site and author details in `config.toml`.
2. Add your Google Analytics and Disqus keys to `config.toml`.
3. Get a workflow going to see your site's output (with [CloudCannon](https://app.cloudcannon.com/) or Hugo locally).

## Develop

Justice was built with [Hugo](https://gohugo.io/) version `0.80.0`, but should support newer versions as well.

Run the standalone executable `hugo` to serve the site locally:

~~~bash
$ hugo server
~~~

## Editing

Justice is set up for adding, updating and removing pages, authors, posts, company details and footer elements in [CloudCannon](https://app.cloudcannon.com/).

### Posts

* Add, update or remove a post in the *posts* section.
* The **author** field links to the **authors** data.
* Change the defaults when new posts are created in `_posts/_defaults.md`.

### Contact Form

* Preconfigured to work with [CloudCannon](https://app.cloudcannon.com/), but easily changed to another provider (e.g. [FormSpree](https://formspree.io/)).
* Sends email to the address listed in company details.

### Author

* Reused around the site to save multiple editing locations.

### Footer

* Set how this displays with each page front matter in `menu.footer`.

### Company details

* Reused around the site to save multiple editing locations.
* Set in the *Data* / *Company* section.
