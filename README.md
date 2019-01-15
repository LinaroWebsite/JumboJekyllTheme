# Jumbo Jekyll Theme

This is an open source Jekyll theme built for use on the Linaro Jekyll static websites. This project aims to unify the styles and components of Linaro static websites and make it easier to replicate and deploy a new static site.

## Examples of sites using the theme

* [Linaro.org](https://www.linaro.org)
* [96boards.org](https://www.96boards.org)
* [Op-tee.org](https://www.op-tee.org)
* [OpenDataPlane.org](https://www.opendataplane.org)
* [DeviceTree.org](https://www.devicetree.org)

## Features

Some of the features this theme offers:

* Lazy loading of content.
* Generated breadcrumb
* Easy navigation / footer management using YAML Data files.

## Available Layouts

Below are a table showing the available layouts for you to use:
| Layout | Description | 
| ------ | ----------- |
| jumbotron | This layout adds either a carousel header, background-image header or a breadcrumb header. Content using this layout should be added to Boostrap 3 rows. This 
layout is useful when addng custom pages. |
| jumbotron-container (Most Common) | This is the exact same as the above but instead provides a Bootstrap 3 content container than can be used to add content to. |


### Jumbotron Layout

If you are using a layout that contains `jumbotron` then you can choose to display an image carousel header, standard background image header or a simple breadcrumb.

**Jumbotron Settings**
With the jumbotron layouts you can add a title, sub title and buttons to your header through changing your pages' front matter. 

The jumbotron `title` can be modified by changing the title value in the page front matter:

```yaml
---
title: Your Page Title (and jumbotron title)
...
---
```

The jumbotron `sub title`/`description` can be modified by changing the description value in the page front matter:

```yaml
---
...
description: >-
    Your Page description (and jumbotron description/sub title)
...
---
```

The jumbotron `buttons` can be added with the following front matter:

```yaml
---
...
jumbotron:
    ...
    buttons:
        - title: Learn More
          url: /about/
          icon: fa fa-github
          ...
...
---
```
The above should hopefully be fairly self explanatory other than the icon value which should be the icon class for a Font Awesome 4.7 Icon. For all available icons [click here](https://fontawesome.com/v4.7.0/icons/). 


**Displaying an image carousel**

If you would like to display an image carousel for your page then add the following front matter to your page:

```yaml
---
...
jumbotron:
    ...
    carousel-images:
        - /assets/images/content/background-image1.jpg
        - /assets/images/content/background-image2.png
        - /assets/images/content/background-image3.jpg
    ...
...
---
```
Add as many images here as you would like. Even though these images are loaded lazily, try and make sure the images have been optimized as large images will increase the page load time. Also try to ensure the resolution of these images are fairly high.


**Displaying an background image based jumbotron**

```yaml
---
...
jumbotron:
    ...
    background-image: /assets/images/content/background-image1.jpg
    ...
...
---
```
Here you can add image to be used an the background image of the jumbotron. Try and make sure the image has been compressed/optimized as large images will increase the page load time. Also try to ensure the resolution of these images are fairly high.



# The Docs
The documentation for this theme is currently available through the Collaborate space. I will be adding to readthedocs/github in due course.

# Feature Requests / Bug Fixes

If anyone that uses the theme has any useful bug fixes / feature requests that may be of interest then please feel free to fork/submit a PR with your fixes/features.



# Blog Post Images

To add a featured image to your blog post set the `image:` key in your posts front matter:

```yaml
image: /assets/images/social-media-image.png
```

Thumbnails are automatically generated from your high resolution image upon site build using the `jekyll-responsive-image` plugin.