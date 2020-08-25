---
# Page settings
layout: default
keywords:
comments: false

# Hero section
title: Images
description: Learn how to work with images in Lunacy
icon: 'full-image'

# Micro navigation
micro_nav: false

# Page navigation
page_nav:
    next:
        content: Export
        url: '/export'
    prev:
        content: Libraries
        url: '/libraries'
---


This chapter details, ho to work with raster images. Lunacy supports all the popular image formats like PNG, JPG, JPEG, WEBP, BMP, ICO, GIF, SVG. The TIFF format is not supported.

## Adding images

You can:

* Use photos from the Lunacy <a href="https://docs.icons8.com/libraries/#photos-and-masked-photos" target="_blank">library</a>.
* Use the <a href="https://docs.icons8.com/tools/#image-tool" target="_blank">Image tool</a> to add images from your computer.
* Copy image files from your desktop or the Explorer and then paste them onto the canvas.
* Drag image files from your desktop or the Explorer and then drop them onto the canvas.
* Import images from the internet.

There are several ways of adding images from the internet.

**Way 1**

1. In your web browser, right-click over the image. The context menu appears.
2. On the displayed menu, click **Copy image** or similar command.
3. Switch to Lunacy and right-click over the canvas.
4. Click **Paste here** on the context menu.

**Way 2**

1. In your web browser, right-click over the image. The context menu appears.
2. On the displayed menu, click **Copy image address** or similar command.
3. Switch to Lunacy and right-click over the canvas.
4. Click **Paste here** on the context menu. The **Paste as image** dialog box appears.
5. Click **OK** to paste the image. If you click **Cancel**, Lunacy will paste the image address as text.

**Note:** The second method works only when a web site provides direct links to images with an image extension at the end (.jpg, .png, .etc.).

The demo below shows the above two methods.

<video autoplay="" muted="" loop="" playsinline="" width="100%" poster="/public/tool-imgeimportph.png" height="auto"><source src="/public/tool-importimage11.mp4" type="video/mp4"></video>

**Way 3**

1. In your web browser, right-click over the image. The context menu appears.
2. On the displayed menu, click **Copy image address** or similar command.
3. Switch to Lunacy and click the Image tool. The **Open** dialog box appears.
4. Paste the image URL into the **File name** field.
5. Click **Open**.
6. Click over the area where you want to put the image (this will add the image in its original size) or click and drag to get the required size of the image.

## Replacing images

There are two ways to replace images.

**Way 1**

1. Select an image on the canvas.
2. In the **Image** section of the Inspector, click the **Replace image** button. The **Open** dialog box appears.
3. Browse to the new image file, select it and click **Open**.

**Tip:** You can also use this method, when you need to replace your current image with an image from the internet. In such a case, just paste the URL of the new image into the **File name** of the **Open** dialog box and click **Open**.

**Way 2**

1. Drag an image from the library, desktop or Explorer and hover it somewhere near the center of the current image.
2. Wait a moment until the green mask appears, then release the mouse button.

**Tip:** If the green mask does not appear, try to zoom in a bit.

## Cropping images

To crop an image:

1. Select the image.
2. Press `Enter` or click ![Image crop button](public/images-cropbtn.png) on the context toolbar. The image crop frame gets enabled.
3. Drag the borders of the frame to select the required area.
4. Press `Enter` or click the **Apply editing** button in the Inspector.

<video autoplay="" muted="" loop="" playsinline="" width="100%" poster="/public/images-cropph.png" height="auto"><source src="/public/images-crop.mp4" type="video/mp4"></video>

## Adjusting image colors

You can make color adjustments to your images using the controls in the **Adjust image** section of the Inspector. The section appears only when an image is selected. Just click the `+` button to unfold the panel and move the sliders to adjust hue, saturation, brightness, and contrast.

These adjustments are non-destructive. You can quickly restore the initial color of an image by clicking the **Reset values** ([Reset values button](public/resetvaluesicon.png)) next to the section header (see the demo below).

<video autoplay="" muted="" loop="" playsinline="" width="100%" poster="/public/images-adjustph.png
" height="auto"><source src="/public/images-adjust.mp4" type="video/mp4"></video>

Also, you can adjust color settings of several images at a time.

## Background removal

To remove background from an image:

1. Select the image.
2. In the inspector, click the **Remove background** button.

<video autoplay="" muted="" loop="" playsinline="" width="auto" poster="/public/tips-bgremovalph.png" height="auto"><source src="/public/tips-bgremove.mp4" type="video/mp4"></video>