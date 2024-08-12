# CSS-Notes
CSS Notes

Writing a class selector

You can assign classes to HTML elements to create a reference point for styling. A class is an attribute that can be added to any HTML element, providing additional details about that element.In CSS, we use a dot (.) before the class name to differentiate it from HTML element selectors. Write ".intro" and set the color to green.

CSS has two parts: 

The selector. 
The declaration block. 

The selector specifies a pattern in the HTML, and if the pattern matches, the styles within the declaration block are applied to the corresponding HTML elements. It is possible to have multiple styles applied to the same pattern, and that is where the cascading part of CSS comes into play

  ![image](https://github.com/user-attachments/assets/ef3bd5b3-0c55-4384-8647-4cae2a07aa91)

  In CSS, each style declaration consists of two parts: 

A property. 
A value. 

Css comments are different to HTMl comments whereas it uses a slash and a star and a start and a slash "/* */"

Formatting color in CSS

The most common way to represent colors online is through hex codes, also known as hex values or hex format. Hex is short for hexadecimal.

![image](https://github.com/user-attachments/assets/0da186c6-3560-4cf2-8141-6d2ff55f5c25)

 the last number (e.g., "CC" in the hex value or "0.8" in the RGB value) corresponds to Alpha, which relates to the opacity and transparency of the color.

 Fonts

 font-family = this is used to group certains font so that it is a fallback for the computer if certain fonts is not available.

 ![image](https://github.com/user-attachments/assets/faa4116e-e4e9-4b32-afbc-c261bf32b363)

In web design, there are two types of sizing: absolute and relative. Absolute sizes, such as points or pixels, remain the same regardless of the screen size. On the other hand, relative units like percentages or R-E-M (pronounced "rem") can adjust based on the page size.

font-size is used to diplay the font size

Understanding the Box Model in CSS

First, we have the content, which is the text inside the box. Then, there is the border, which is like a line surrounding the content. We can choose to display all four sides of the border or just a few. And there are various styles available for the border. 

Next, we have the padding, which is the space between the border and the content. It can also have its own background color. When we add padding, we are essentially pushing the edge of the box away from the content. 

Outside the border, there is the margin, which represents the space between elements on the page. If you want to separate intersecting elements, adding some margin will do the trick. 

we will be focusing on the concept of applying changes to either all four sides or just one side of the box. These sides are commonly referred to as left, right, top, and bottom
