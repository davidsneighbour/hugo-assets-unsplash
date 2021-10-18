Hi and congratulations you found this repository ;) Right now it does not do much, but I am working on getting it to do the following:

- have a collection of tagged, labeled and captioned images (free stockimages from Unsplash) for use as article images in gohugo weblogs
- add them via @dnb-org/shortcodes-pictures shortcode module to themes/posts
- have a frontmatter variable that will then enable to add a random image based on tags or keywords (first build, if-exists)
- add article image with reponsive picture tag and various formats (happy lighthouse, happy google) - via shortcodes-pictures
- several fallbacks (via tagged image, category image, section image, global repo default image)

**Basically this: you create a post, you add some tags, GoHugo retrieves an image that is fitting the article and uses it for social imagery and the article image. **

Longterm goals:

- right now we have all images saved in this repo. better would be some form of usage of the Unsplash API to retrieve images based on the keywords. that's probably also more proper usage in regards to the licenses of Unsplash and gives us more images to use
- image processing

This is work in progress. Come back or offer help.
