## Simple-Instagram-photo-feed-with-HTML-CSS

The `div` element is a generic container with no particular semantic meaning.
It is commonly used in document development for stylistic purposes, in
set with the `style` and `class` attributes.

To perform this exercise we mainly split each area into `<div>` to have
control over the containers, these are divided in the upper part of our
web for the main title. Then in the post a head that contains the title 
and thepost counter, body for the image to be displayed and footer for 
the bottomof the text. Using the css properties `Display:Flex` and 
`Justify-content` we have better control over the layout of inline 
elements, like tips it's good to leave a defined width and height 
on each `<div>` container to apply abetter margin control.

Recommended websites for theme icons, images and tools:

[-Google Fonts](https://fonts.google.com/).

[-Fontawesome](https://fontawesome.com/).

[-Pexel](https://www.pexels.com/es-es/).

----------------------------------------------------------------------------------------------------------------

## What to do next?

Create an `index.html` file with the [basic HTML structure](http://content.breatheco.de/lesson/what-is-html-learn-html#page-structure) and see it live by running a web-server using the following command:

```sh
$ pip3 install flask && python3 server.py
```

- You can create as many HTML files as you want
- You can also create CSS files and import them into your website using a `<link>` tag placed between the `<head></head>` tags, like this:

```html
<head>
  ...
  <link rel="stylesheet" type="text/css" href="styles.css">
  ...
</head>
```
