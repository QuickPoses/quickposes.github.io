---
layout: help
category: Help
title: How to add more galleries in the app (1.5)
permalink: /help/1_5/add_more_galleries/
---

Quickposes comes with a few default galleries of royalty free images to help you start using the app right away without any special setup. But as you start using the app more regularly, you'll probably feel the need to add more diversity in your day-to-day practices.

In this page, we'll show you how you can add more galleries to your app so you can better improve your skills. 

## Quick & dirty import

If you are in a hurry and don't mind if your gallery appearance is a bit rough, you can simply follow the steps below:

1. Create a folder on your computer with a bunch a images inside
2. Import it in the app using the appropriate method as explain [at the end of this page](#importing-your-new-gallery-folder-into-your-app)
3. [Kill and restart the app][5] and you'll get a new gallery available to work with.

## Best practices

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

## Importing your new gallery folder into your app

Once your gallery folder is ready and tweaked to your taste, the last step is to import it into your app on your device. The step are a little different depending on your computer version:

### For macOS Catalina

If you are on a Mac with the lastest version of macOS, Catalina, you'll need to [use the Finder to share files between your Mac and your iPhone, iPad, iPod touch][3].

### For macOS Mojave or earlier or a Windows PC

If you are on a Mac with an older version of macOS or on a Windows PC, you'll need to [use iTunes to share files between your computer and your iOS or iPadOS device][4]

## Last Steps

As mentionned in the first section, to make your new galleries appear in the app, you'll need to [kill and restart the app][5].

Now you can enjoy your new galleries!! 🎉

Happy drawing! 👨🏻‍🎨🧑🏾‍🎨

[1]: ../../img/help/anatomy-gallery.png "Anatomy of a gallery"
[2]: ../../img/help/image-name-usage.png "How image names are used"
[3]: https://support.apple.com/en-us/HT210598 "Use the Finder to share files between your Mac and your iPhone, iPad, iPod touch"
[4]: https://support.apple.com/en-us/HT201301 "Use iTunes to share files between your computer and your iOS or iPadOS device"
[5]: https://support.apple.com/en-us/HT201330 "How to force an app to close on your iPhone, iPad, or iPod touch"