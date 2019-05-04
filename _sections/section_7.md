---
section_number: 7
section_title: Styling your content

---

This section will show you how to style your page content.


### Headings

There are several different sizes of heading, these are styled as follows.

    # Heading 1
    ## Heading 2
    ### Heading 3
    #### Heading 4

This will produce the following:

# Heading 1
## Heading 2
### Heading 3
#### Heading 4   


### Links

You can add links to your pages, this is done as follows.

    [Visit Google](https://www.google.com)

This will produce:

[Visit Google](https://www.google.com)


### Images

Images belong in the 'img' folder and can be uploaded as follows.

- Make sure you're in the thetanewzealand/thetanewzealand folder.

- Click on the 'img' folder.

![img folder](img/img_folder.png)

Click the 'upload files' button on the right of the page.

![img folder](img/upload.png)

Drag your files across or click **choose your files**

![img folder](img/choose.png)

Find the image you'd like to use then click open.

To display the image on a page you will need to use the following text.

    ![Image Title](img/imagename.extension)

    ![Image Title] - This is the name of the image
    (img/imagename.extension) - This is where the image is stored

For example, if we wanted to upload the Theta logo and the file name was 'logo.png' we would write the following text:

    ![Theta Logo](img/logo.png)

The image title would be Theta Logo
And the image path would be **img/logo.png**

This will produce:

![Theta Logo](logo.png)

### Lists

    1. First ordered list item
    2. Another item
    ⋅⋅* Unordered sub-list.
    1. Actual numbers don't matter, just that it's a number
    ⋅⋅1. Ordered sub-list
    4. And another item.

    ⋅⋅⋅You can have properly indented paragraphs within list items. Notice the blank line above, and the leading spaces (at least one, but we'll use three here to also align the raw Markdown).

    ⋅⋅⋅To have a line break without a paragraph, you will need to use two trailing spaces.⋅⋅
    ⋅⋅⋅Note that this line is separate, but within the same paragraph.⋅⋅
    ⋅⋅⋅(This is contrary to the typical GFM line break behaviour, where trailing spaces are not required.)

    * Unordered list can use asterisks
    - Or minuses
    + Or pluses


### Styling Text

Text can be styled in several ways.

    Emphasis, aka italics, with *asterisks* or _underscores_.

    Strong emphasis, aka bold, with **asterisks** or __underscores__.

    Combined emphasis with **asterisks and _underscores_**.

    Strikethrough uses two tildes. ~~Scratch this.~~

Emphasis, aka italics, with *asterisks* or _underscores_.

Strong emphasis, aka bold, with **asterisks** or __underscores__.

Combined emphasis with **asterisks and _underscores_**.
