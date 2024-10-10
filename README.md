# single-ball
# Ball Animation with HTML, CSS, and JavaScript

This project creates a basic web page that animates a ball bouncing inside a 600x600 pixel container. The ball's movement is controlled using simple JavaScript and CSS styling. The ball changes direction when it reaches the boundaries of the container.

## Features

- Creates a sky-blue background container of size 600x600 pixels with a black border.
- Animates a circular ball with a linear gradient from black to blue.
- The ball moves inside the container and bounces when it reaches the container's edges.

## How it works

1. The ball is created using JavaScript by dynamically generating a `div` element with CSS styles applied.
2. The ball's position and movement are controlled by the `move()` function, which updates its position on the screen based on a simple velocity.
3. The ball's direction is reversed when it hits the edges of the container.
4. The animation updates every 150 milliseconds using `setInterval()`.

## Code Example

Here is the main HTML, CSS, and JavaScript structure:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ball Animation</title>
</head>
<body>
    <div style="border: 1px solid black; height: 600px; width: 600px; background-color: skyblue;"></div>
    
    <script>
        function hello() {
            var hi = document.createElement('div');
            hi.style.top = '50px';
            hi.style.left = '50px';
            hi.style.width = '50px';
            hi.style.height = '50px';
            hi.style.backg
