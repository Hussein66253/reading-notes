# canvas
## What is canvas?
- < canvas> is an HTML element which can be used to draw *graphics* via scripting with JavaScript this can be used to draw *graphs*, *combine photos*, or create *simple animations*.
- unlike the < img> element, the < canvas> element **requires** the closing tag (< /canvas>).
- The canvas is initially blank. To display something, a script first needs to access the rendering context and draw on it the < canvas> element has a method called **getContext()**, used to obtain the rendering context and its drawing functions.
- The < canvas> element has only two attributes, **width and height.**
- When no *width and height* attributes are specified, the canvas will initially be **300 pixels wide** and **150 pixels high**.
- Because the canvas is an **HTML element**, you can use *CSS* styles to modify its *position, assign it a background color or image, add a border*, and so on
## Drawing Text on the Canvas:
- For getting text to appear in our canvas, we can use two methods: **strokeText** and **fillText.**
- With the **strokeText method**, you end up drawing an outline of your text:
![stroke Text](https://www.kirupa.com/canvas/images/canvas_stroke.png)
- The **fillText method** allows you to display a solid filled-in version of our text:
![fill Text](https://www.kirupa.com/canvas/images/canvas_fill.png)


