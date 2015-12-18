# Screenshots. We fucking love them.

To get started with this, you're going to need to install a few things:

Install `watir` by pasting this into terminal: `gem install watir`

Then install `watircats` by pasting this into the same terminal: `gem install watircats`

Now check if you have `ImageMagick` by pasting `identify -version`. Should tell you `yay` or `nay` basically.

If you don't, install it here: [http://cactuslab.com/imagemagick/](http://cactuslab.com/imagemagick/)

---

## Everything installed? Wicked, lets take some screenshots

Clone this repo `git clone git@github.com:yratof/screenshots.git && cd screenshots`

You should open the `config.yml` file to see wtf is happening, but basically it's going to take 4 screenshots and plop them into a folder for you.

Edit the `urls.txt` to have the URLS you want to crawl on this domain. If you don't know them yet, I would recommend downloading something like [Screaming Frog](http://www.screamingfrog.co.uk/seo-spider/) and crawl your site. Then use that to populate the `urls.txt`. Sounds complicated, but it's just *click click click done*.

When you have your URLs sorted, run this beauty
`watircats screenshots http://website.com --config_file config.yml`
