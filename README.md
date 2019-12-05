# nuxt-vue-meta-bug

> Repo showing that a head script is loading multiple times on navigation

## Build Setup

``` bash
# install dependencies
$ npm run install

# serve with hot reload at localhost:3000
$ npm run dev
```

* Open the site in Chrome, with dev tools open to the navigation tab
* Click on the link to "foo" - see that "head-script.js" is loaded
* Click on the link to "index"
* Click on the link to "foo" - see that "head-script.js" is loaded again
