# H.E.L.P Website

This project provides the basic information needed to create a website for a real-world non-profit organization.

## Replacing Images

The following HTML Code is a tag that embeds an image in your site. In order to change the image being embeded,all that needs to be done is to place the new image inside of the "images" folder, and then change the "src=" value to match the name of your new image. If you simply want to replace an existing image with an updated one,then an easy way to do so is to name the new image the same as the old one and remove the old one by placing the new image in the same folder as the old, all HTML can stay the same.

<img src="logo/New Lifeline Logo.jpg" title="PBL Logo">

## Adding a new image

This step is very similar to replacing an image. Start by preparing your new image and placing it in the "images" folder. Next you need to find an "img" tag similar to the one above and change the "src=" value to "images/" and then the name of your file, following the format that all images on the site already follow. After you have prepared your "img" tag, you just need to place the tag in the desired position in the HTML, and possible add any attributes that you want for your image (ie. fixed size/position).

## Updating CDN Style Links

To change the style links all you need to do is to change the "href" value in the "link" tag of your desired style at the top of your page to change and update that value with your new desired link.
<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css"
        integrity="sha384-ggOyR0iXCbMQv3Xipma34MD+dH/1fQ784/j6cY/iJTQUOhcWr7x9JvoRxT2MZw1T" crossorigin="anonymous">

and then find the appropriate "script" tag near the bottom of the page (if applicable) and change the "src" value in it to the desired JavaScript source path.
<script src="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/js/bootstrap.min.js"
    integrity="sha384-JjSmVgyd0p3pXB1rRibZUAYoIIy6OrQ6VrjIEaFf/nJGzIxFDsf4x0xIM+B07jRM"
    crossorigin="anonymous"></script>

## Our Team

tbd