Download Link: https://assignmentchef.com/product/solved-cs142-project1-html-and-css
<br>
Problem 1

Create a single HTML document that presents two di erent appearances, determined by the document’s CSS stylesheet. Your HTML le should be called index.html and the document’s title should be “CS142 Project #1”. Along with this HTML document, you should also create two stylesheets called styleA.css and styleB.css .

If the HTML le links to styleA.css then it should appear like this (“Version A”):

If the HTML le links to styleB.css then it should appear like this (“Version B”):

<strong>Note: The D in the screenshot is highlighted to show you what space the text should occupy. Your solution should not style the D with a blue background.</strong>

<h2>Style A Speci cations</h2>

There should be six box elements, lined up vertically.

All boxes are centered horizontally and equally spaced vertically. When the browser window is resized, the spacing between the boxes should change (they should be equally spaced vertically across the page). However, the boxes themselves should never overlap or change size.

Each box is 100×100 pixels, with a 1px line (color: #687291) on top. Text is centered horizontally.

Boxes alternate colors (colors: #dfe1e7, #eee 2).

The nal element (color: #687291) has a 4px, black border and the text is centered vertically. The font in all elements is Tahoma, 40 pixels.

<h2>Style B Speci cations</h2>

Five box elements, lined up horizontally in the top left corner.

Boxes do not wrap with window resizing (i.e. Boxes A through E should stay on the same line even if your browser window is too small to display them all).

The last box is positioned in the bottom right corner of the window and stays there even when the window resizes.

Each box is 100×150 pixels (color: #eee 2), with a 10px dotted line (color: #D0D0FF) on the left. Boxes are separated by 10 pixels of space. When hovering over an box, the cursor changes to a hand and the box and font colors change (colors: yellow, goldenrod, respectively). The font in all elements is Tahoma, 40 pixels.

There are 10 pixels of space between the letters and the edge of the box.

<table>

 <tbody>

  <tr>

   <td width="12"></td>

  </tr>

  <tr>

   <td></td>

   <td></td>

  </tr>

 </tbody>

</table>

If a property is not outlined in these speci cations (e.g. space between elements in style B and edge of window) you should choose something reasonable.

<h1> Style Points</h1>

<a href="https://validator.w3.org/#validate_by_input+with_options">Your HTML le must be a valid XHTML 1.0 document that passes validation at http://validator.w3.org</a>

<a href="https://validator.w3.org/#validate_by_input+with_options">(http://validator.w3.org/#validate_by_input+with_options). In addition, your HTML and CSS must be c</a>lean, readable, properly indented, and wellstructured.

<h1> Extra Credit</h1>

Create a third stylesheet styleC.css that utilizes 2 of the following:

gradients transitions animations web fonts shadows


