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

`cd desktop; mkdir screenshot-capture; cd screenshot-capture;`

`watircats screenshots http://fpd.fullphatdesign.co.uk --config_file config.yml`