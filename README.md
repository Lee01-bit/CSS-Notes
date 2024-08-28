# CSS-Notes
CSS Notes

Writing a class selector

You can assign classes to HTML elements to create a reference point for styling. A class is an attribute that can be added to any HTML element, providing additional details about that element.In CSS, we use a dot (.) before the class name to differentiate it from HTML element selectors. Write ".intro" and set the color to green.

CSS has two parts: 

The selector. 
The declaration block. 

Css has 3 types :

Internal- it is where you would create a style within the head of your HTML using the <code><style></style></code>

external- creating a style sheet and linking it to your HTML document

Inline- you would insert your code directly inline with your element  <code><p></code>Want to try crossing out an </code><code><a href='nowhere.html'
  </code>style='color: #990000</code>; text-decoration: line-through;'></code>obsolete link</a>?
   This is your chance!</p></code>

Css unit mesurement -the most common ones you’ll encounter are px (pixel) and em

![image](https://github.com/user-attachments/assets/d3d92341-440b-4e4a-a1f8-6d49b83b9a93)


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

 Each HTML element rendered on the screen is a box, and they come in two flavors: “block” boxes and “inline“ boxes

 block level boxes alwasy appear below each other, the width of the box are always
 the width of its parent contaianer which in this case is the body

 shorthand properties

 ![image](https://github.com/user-attachments/assets/09719b76-3b6c-401c-8de7-8e1d74bf6436)


There are three methods for horizontally aligning block-level elements: “auto-margins” for center alignment, “floats” for left/right alignment, and “flexbox” for complete control over alignment.

Pseudo-classes begin with a colon followed by the name of the desired class. The most common link pseudo-classes are as follows:

:link – A link the user has never visited.

:visited – A link the user has visited before.

:hover – A link with the user’s mouse over it.

:active – A link that’s being pressed down by a mouse 

Float

![image](https://github.com/user-attachments/assets/be235fc9-83ba-4df6-8021-a83bd9dbd2ee)

Cross-Axis (Vertical) Alignment
![image](https://github.com/user-attachments/assets/2c084225-b5e3-47e8-bff4-17ec12466865)


Wrapping Flex Items
![image](https://github.com/user-attachments/assets/a2b2c71a-7add-4420-a346-3009d861b9dc)


Flex Container Direction
![image](https://github.com/user-attachments/assets/234bc352-95dd-4991-bb3d-a5f3aca52216)

One of the most amazing things about flexbox is its ability to transform rows into columns using only a single line of CSS. Try adding the following flex-direction

alignment consideration 

when changing the direction of the content from a row to column or vise versa , the justify contetn and aling itme changes as well
![image](https://github.com/user-attachments/assets/11cb05eb-8fa8-4b4d-994f-06e65e72b34c)

Summary 
<li>Use display: flex; to create a flex container.</li>
<li>Use justify-content to define the horizontal alignment of items.</li>
<li>Use align-items to define the vertical alignment of items.</li>
<li>Use flex-direction if you need columns instead of rows.</li>
<li>Use the row-reverse or column-reverse values to flip item order.</li>
<li>Use order to customize the order of individual elements.</li>
<li>Use align-self to vertically align individual items.</li>
<li>Use flex to create flexible boxes that can stretch and shrink.</li>



