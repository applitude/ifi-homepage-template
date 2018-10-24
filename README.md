# IFI Homepage Template

A template for a home page for students at the Institute for Informatics at the University of Oslo.

### Run a development server on your local machine
```bash
# Install live-server
npm i -g live-server

# In the top directory
live-server .
```

If you don't have `npm`, you can get it by downloading [NodeJS](https://nodejs.org/en/about).
Check out [this page](https://nodejs.org/en/download/package-manager/) to find out how to install it with a package manager on your system.

If you don't want to download `NodeJS` for some reason, you can run any other [HTTP](https://developer.mozilla.org/en-US/docs/Web/HTTP)-server, for example:
```bash
python3 -m http.server
```
Will run a HTTP-server at `http://localhost:8000/`

### Deploy this to your own website hosted by UiO
Every UiO student has access to a website hosted at [https://folk.uio.no/](http://folk.uio.no/)
Follow this [guide](https://www.uio.no/tjenester/it/web/personlig-nettside/hjelp/www.html) to put your website on `https://folk.uio.no/<yourusername>`. The main idea is to place your websites files in the `~/www_docs/` directory of your UiO user and edit the permissions of the directory, so that it is displayed.

It is worth noting that websites hosted here often appear in google search results. If you wish to make sure that the website won't appear in any search engine results, include a [robots.txt](https://moz.com/learn/seo/robotstxt) in your top directory. For the `robots.txt` to block access to everything you can write it as such:
```
User-agent: *
Disallow: /
```

### Deploy using GitHub Pages
Another alternative for hosting your website is to put it on [GitHub Pages](https://pages.github.com/).

To do that you can [fork this repository](https://help.github.com/articles/fork-a-repo/) and follow this [guide](https://pages.github.com/) to host it at `https://<yourgithubusername>.github.io/`.
