<a href="https://visual-essays.app"><img src="/images/ve-button.png"></a>

# Image viewer

The `image viewer component` is used to view one or more images for a paragraph.

## Key features include:

1. All images are converted to IIIF enabling zooming and panning of high-resolution images
2. IIIF manifests are created for each image providing a means to associate metadata with each image.  Arbitrary metadata can be associated with the image but will typically include
    - Label
    - Description
    - Attribution
    - License
3. Images may be annotated
    - Annotations can be sequenced and used in an "annotation player" to provide a guided tour over image features of note
    - Annotations can be linked to essay text with actions performed on click or hover
4. Image zooming/panning may be inititated by linked passages in essay text
5. Captions with attribution and linked licenses are automatically generated using manifest metadata
6. Images may be cropped and rotated
7. Various multi-image modes are available
    - Gallery view displaying selected images
    - Layers view allowing an image to be superimposed over another
    - Curtain view allowing 2 images to be juxtaposed with an interface control for displaying relative portions of each
    - Compare view showing the images side-by-side
