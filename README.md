# responsive-gallery
A template for a super basic responsive gallery for various TTBOOK thingies. It assumes you're hosting all of your images or other assets on an S3 bucket, and you've gathered the direct links to each image.

[Based on flexbox guide here.](https://www.taniarascia.com/how-to-build-a-responsive-image-gallery-with-flexbox/)

[this guide to "object-fit" was also super helpful](https://alligator.io/css/cropping-images-object-fit/)

This was designed as a workaround for not having direct CSS control for our base website. The stylesheet and HTML are hosted here via Github pages -- you can test locally by cloning this repo and tweaking, then use drupal-inline-code.html as a model for your code on the CMS side.

To use this:
1. Fork repo (rename closer to purpose to avoid confusion)
2. Pull local and customize to your liking.
3. Push changes.
4. Activate Github Pages on the master branch (or specific branches if you wanna get fancy)
5. Grab the Github.io URL from your repo and use it to update drupal-inline-code.html per the inline comments.
5. Paste the code from that file into the body field of the content on your Drupal site. (have not tested this for other CMSes)
