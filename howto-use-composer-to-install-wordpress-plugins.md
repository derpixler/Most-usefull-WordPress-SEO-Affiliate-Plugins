##How using composer to get all useful WordPress Plugins?

####1. Install composer
Quick you can read the [Getting Started](https://getcomposer.org/doc/00-intro.md#installation-linux-unix-osx) instructions or do the following on the commandline.
```
curl -sS https://getcomposer.org/installer | php
chmod +x composer.phar
mv composer.phar /usr/local/bin/composer
```
--

####2. [Clone this reposetory](https://github.com/derpixler/Most-usefull-WordPress-SEO-Affiliate-Plugins/blob/master/composer.json)
You have to clone this reposetory in your WordPress `plugins/` folder.

`git clone git@github.com:derpixler/Most-usefull-WordPress-SEO-Affiliate-Plugins.git`

--

####3. Run composer install
In your WordPress `plugins/`folder you have to run the composer install command.
`composer install``

It will looks like that:
```
Loading composer repositories with package information
Installing dependencies (including require-dev)
  - Installing mnsami/composer-custom-directory-installer (1.1.0)
    Loading from cache

  - Installing composer/installers (v1.0.23)
    Loading from cache

  - Installing wpackagist-plugin/auto-load-next-post (1.4.5)
    Loading from cache

  - Installing wpackagist-plugin/automatic-post-tagger (1.8.2)
    Loading from cache

  - Installing wpackagist-plugin/table-of-contents-plus (1601)
    Loading from cache

  - Installing wpackagist-plugin/rich-text-tags (1.7.3)
    Loading from cache

  - Installing wpackagist-plugin/schema-creator (1.1.1)
    Loading from cache

  - Installing wpackagist-plugin/easy-affiliate-links (1.2)
    Loading from cache

  - Installing wpackagist-plugin/autoptimize (2.0.1)
    Loading from cache

  - Installing wpackagist-plugin/thirstyaffiliates-for-foogallery-extension (1.0.1)
    Loading from cache

  - Installing wpackagist-plugin/nofollow (1.4.4)
    Loading from cache

  - Installing wpackagist-plugin/google-sitemap-generator (4.0.7.1)
    Downloading: 100%         

  - Installing wpackagist-plugin/if-modified-since-header (1.2.3)
    Downloading: 100%         

  - Installing wpackagist-plugin/add-headers (2.0.0)
    Downloading: 100%         

  - Installing wpackagist-plugin/responsify-wp (1.9.6)
    Downloading: 100%         

  - Installing wpackagist-plugin/broken-link-checker (1.10.10)
    Downloading: 100%         

  - Installing wpackagist-plugin/search-and-replace (3.0.1)
    Loading from cache

  - Installing wpackagist-plugin/image-lazy-load (1.0.9)
    Downloading: 100%         

  - Installing wpackagist-plugin/gotmls (4.15.49)
    Downloading: 100%         

  - Installing wpackagist-plugin/backwpup (3.2.5)
    Downloading: 100%         

Writing lock file
Generating autoload files

```
