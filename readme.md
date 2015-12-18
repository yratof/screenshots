# Screenshots. We fucking love them.

To get started with this, you're going to need to install a few things:

Paste this into terminal:

`gem install watir`

Then paste this:

`gem install watircats`

Then check if you have `ImageMagick`

`identify -version`

If you don't, install it here: http://cactuslab.com/imagemagick/

---

## Take screenshots

You should edit the config file to see wtf is happening, but basically, it's going to take 4 screenshots and plop them into a folder for you.

Make your way to your cloned folder
`cd screenshots;`

Edit the `urls.txt` to have the URLS you want to crawl on this domain. If you don't know them yet, I would recommend downloading something like [Screaming Frog](http://www.screamingfrog.co.uk/seo-spider/) and crawl your site. Then use that to populate the `urls.txt`. Sounds complicated, but it's just *click click click done*.

When you have your URLs sorted, run this beauty
`watircats screenshots http://website.com --config_file config.yml`
