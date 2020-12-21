* The Image Tag
* Link to a Hosted Image
* Upload an Image to your GitHub Repository
___

# The Image Tag

Add an image to a page/essay using the `<param ve-image>` tag. This tag has significant benefits over using basic Markdown such as 
```![Image accessibility description goes here](http://exampleurl.com/image.png)```

By using the `<param ve-image>` tag, your image will automatically be shown in the right-hand pane of your essay within a specialized Mirador](https://projectmirador.org/) viewer. Mirador has the following benefits:

1. Zoom, display, compare images
2. Create a gallery of images
3. Compare and annotate images
4. Automatic titling

The `<param ve-image>` requires two additional attributes: `title` and `url`. The `title` contains the description of the image which will be displayed underneath and is important for accessibility purposes. The `url` is the address where the image is stored. Here is an example:

`<param ve-image title="Roasted Coffee Beans" url="https://upload.wikimedia.org/wikipedia/commons/c/c5/Roasted_coffee_beans.jpg">`

The `<param ve-image>` tag supports the following image types:

* .png
* .jpg
* .tiff (a high-resolution format, often used in cultural heritage)

We are currently working on support for the .svg filetype. For the `url`, generally it is preferred to link to a hosted image instead of uploading an image to your GitHub Repository.

# Link to a Hosted Image (Preferred)

For most images, this is the best practice. Ideally, the image is hosted on a stable URL of some kind in a cultural heritage collection. If you have a copy of the image and the right to use it, you can also upload it to the [Wikimedia Commons](https://commons.wikimedia.org/wiki/Category:Images) and link to it there.

# Upload an Image to your GitHub Repository (Not Ideal)

This approach may make sense if you have an image whose rights are cleared, but that is not of general interest to the public (and therefore not appropriate for [Wikimedia Commons](https://commons.wikimedia.org/wiki/Category:Images). This makes sense for small, site-specific images like navigation arrows or buttons. This may also be appropriate for properly sizing the banner for your site (or for a specific page). Keep in mind that GitHub does enforce limitations on repository (and therefore image) sizes, so any uploaded images should be small in size.

## Making an Uploaded Image the Banner for your Website

When editing a banner image for your site, aim for:

* Height- ~400 pixels
* Width- 1200-1600 pixels
* .jpg file type
* ≤ 150 kb in size

It is a good practice to create a `/images/` directory in your GitHub repository to hold sitewide images. For images that are likely to appear on a single page, include those images in the directory for that page (alongside the README.md file). 

## Making an Uploaded Image the Banner for a Single Page/Essay
