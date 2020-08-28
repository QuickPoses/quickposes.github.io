---
layout: help
category: Help
title: Best practices
permalink: /help/1_5/best_practices/
---

[<< Back][3]  

If you want a better control on the gallery appearance in the app and use the safe filter option, this section describe exactly how galleries folder are interpreted by the app so you can tweak it to use its full potential.

### Anatomy of a gallery

Here is a schema showing how the folder and images informations are used to display and use the gallery content in the app:

![show how the file listing relate to the gallery rendering in the app][1]

Let's describe each part:

- **Gallery name:** the name of the gallery is directly taken from the name of the folder, as-is.
- **Thumbnail image:** For the thumbnail image displayed, you have two options: 
    - If nothing special is done, like in the [previous section](#quick--dirty-import), the app will take one of the images as the thumbnail and try to fit it in a square. 
    - To achieve a better result, just add an additional image that should be named exactly `gallery_thumb.jpg`. For this image, we recommend using a _square image of size 500x500px_ for better result and performance.
- **Poses images**: The images used as poses for your session includes all images present at the root of the folder except for the `gallery_thumb.jpg` image if present.
- **Safe filter**: By default, all given images are considered unsafe, so if you do nothing special, when switching the filter on, your gallery will be grayed out and you'll not be able to select it for your next session. To mark images as safe, simply add the characters `-safe-` anywhere inside the image's filename. All images marked like this will stay available when safe filter is on.

![show how the image names are used in the app's session results][2]

Also note that, as shown in the picture above, images' filenames are used when displaying the results at the end of a session.

[<< Back][3]

[1]: ../../../img/help/anatomy-gallery.png "Anatomy of a gallery"
[2]: ../../../img/help/image-name-usage.png "How image names are used"
[3]: ../add_more_galleries/