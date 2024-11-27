# Responsive Images

1. What is the main difference between object-fit and background-size?

`object-fit` is for determining how an image will fit its container, and
`background-size` is for determining the size of an element's background image.

2. How can you define a width and a height on an img without distorting it?

By setting one to a flexible value and the other to `auto`.

3. Why would you want to provide different images at different screen resolutions?

Smaller screens usually indicate a phone, so a smaller image with less data would
be more performant as those usually require a wireless cellular connection.

4. When would you want to use an img with a srcset vs a picture?

Use a picture when you want to serve different images based on the
screen size, and use a img with srcset when you want to serve different
sizes of the same image based on screen size.
