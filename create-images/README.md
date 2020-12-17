* Link to a Hosted Image
* Upload an Image to your GitHub Repository

Add an image to a page/essay using the `<param ve-image>` tag. This tag has significant benefits over using basic Markdown such as `![Image accessibility description goes here](http://exampleurl.com/image.png)`. By using the `<param ve-image>` tag, your image will automatically be shown in the right-hand pane of your essay within a specialized viewer called [Mirador](https://projectmirador.org/). Mirador has the following benefits:

1. Zoom, display, compare images
2. Create a gallery of images
3. Compare and annotate images
4. Automatic titling

The `<param ve-image>` requires two additional elements: `title` and `url`. The `title` contains the description of the image which will be displayed underneath and is important for accessibility purposes. The `url` is the address where the image is stored. Here is an example:

`<param ve-image title="The JSTOR Logo" url="https://upload.wikimedia.org/wikipedia/commons/7/7c/JSTOR_wordmark.svg">`

The `<param ve-image>` tag supports the following image types:

* .png
* .jpg

We are currently working on support for the .svg filetype. For the `url`, generally it is preferred to link to a hosted image instead of uploading an image to your GitHub Repository.

# Link to a Hosted Image (Preferred)

For most images, this is the best practice. Ideally, the image is hosted on a stable URL of some kind in a cultural heritage collection. Please include any information on Image Rights. If you have a copy of the image and the right to use it, you can also upload it to the [Wikimedia Commons](https://commons.wikimedia.org/wiki/Category:Images) and link to it there.

# Upload an Image to your GitHub Repository (Not Ideal)

This approach may make sense if you have an image whose rights are cleared, but that is not of general interest to the public (and therefore not appropriate for [Wikimedia Commons](https://commons.wikimedia.org/wiki/Category:Images). This makes sense for small, site-specific images like navigation arrows or buttons. This may also be appropriate for properly sizing the banner for your site (or for a specific page). Keep in mind that GitHub does enforce limitations on repository (and therefore image) sizes, so any uploaded images should be small in size.

## Making an Uploaded Image the Banner for your Website

A banner image is configured in 

## Making an Uploaded Image the Banner for a Single Page/Essay
