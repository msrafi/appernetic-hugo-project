+++
author = "Göran Svensson"
date = "2016-03-09T14:28:30Z"
description = "Cloudinary is a cloud service that offers a solution to a web application’s entire image management pipeline. Easily upload images to the cloud. Automatically perform smart image resizing, cropping and conversion without installing any complex software."
draft = false
keywords = ["Digital Asset Management", "Cloudinary", "Appernetic Cloudinary setup", "static website"]
tags = ["Cloudinary", "Digital Asset Management", "Appernetic Service","Appernetic Static Site Generator", "Help", "static website"]
title = "Manage your web site images in the cloud"
topics = ["How-to"]
type = "post"

+++
## Cloudinary for image and video assets management in your static website
We no longer use GitHub to manage images in your Appernetic static website service account. You can still use GitHub and they have an easy to use image upload, but to use Appernetic's image upload you now have to first create a Cloudinary account. The advantages of using Cloudinary is so big that it was an easy decision to integrate it. Images are seamlessly delivered through Akamai's fast CDN. By not bogging down GitHub with large images you are also being a good netizen.

Cloudinary is a cloud service that offers a solution to a web application's entire image management pipeline. Easily upload images to the cloud. Automatically perform smart image resizing, cropping and conversion without installing any complex software. Integrate Facebook or Twitter profile image extraction in a snap, in any dimension and style to match your website’s graphics requirements. 

When you upload your image to your article in the PageDown editor it will be sent to your Cloudinary account where you can use the web interface to interactively manage your media library. 

## Setup your account
Start by signing up to [Cloudinary][1]. In the dashboard under the headline Account details, you have the **Cloud name**, that you need to add in the Appernetic user settings. 

![Cloud name in the dashboard ][2]
Cloud name settings in the dashboard.

Now to create a **Upload preset**  click Settings down to the left in the dashboard, select the Upload tab and scroll down to Upload Presets and configure an unsigned upload preset.

![Configure upload presets][3]
Configure unsigned upload presets.

To be able to list images you also need to unmark resource list in security settings.

![Unmark resource list][4] 
Unmark resource list in security settings.

Now all should be configured at Cloudinary! Don't forget to verify your account otherwise, it will be disabled. Now the last thing to do is add the information to your Appernetic settings. Click on your GitHub profile image up to the right to show your user settings.

![Appernetic cloudinary settings.][5]
Add your Cloudinary settings to your Appernetic account. 

![enter image description here][6]
Continue with your content strategy, now with a new tool in your arsenal!


  [1]: https://cloudinary.com/invites/lpov9zyyucivvxsnalc5/csv1uzzgc8ei8ww3ijtf
  [2]: https://res.cloudinary.com/appernetic/v1457539317/mgwu3dyjasovzrq7risa
  [3]: https://res.cloudinary.com/appernetic/v1457538951/s4jzrkhlauoororjskki
  [4]: https://res.cloudinary.com/appernetic/v1457539163/ybd0y47g0ojzsshvdfd4
  [5]: https://res.cloudinary.com/appernetic/v1457539785/yglkvrt4wjhns4xtmzwi
  [6]: https://res.cloudinary.com/appernetic/v1457543046/bgcxapwc14ebqcvn1apy
