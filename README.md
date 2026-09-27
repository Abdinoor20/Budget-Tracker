README.md
Writing
My Budget Tracker
Project Description
This project is a simple Budget Tracker website created using HTML and CSS.
The Week 2 project builds on the Week 1 Budget Tracker by adding an expense table, an improved expense form, multimedia content, interactive elements, and advanced CSS selectors.
Project Files
index.html
The index.html file contains the structure of the Budget Tracker.
It includes:
Budget Tracker heading and logo
Add Expense form
Expense name input
Amount input
Category dropdown
Date input
Add Expense button
Expense table
Five sample expense records
How to use section
Embedded budgeting video
Footer
style.css
The style.css file controls the appearance of the Budget Tracker.
It includes:
Page styling
Form styling
Table borders
Table cell padding
Colored table header
Alternating table rows
Table row hover effect
Button styling
Input focus effects
Advanced CSS selectors
Video styling
Expense Table
The expense table uses the following HTML elements:
<table>
<thead>
<tbody>
<tr>
<th>
<td>
The table contains five sample expenses with:
Name
Amount
Category
Date
Add Expense Form
The form contains:
Expense Name
Amount
Category
Date
The category uses a dropdown with five options:
Food
Transport
Rent
Entertainment
Other
The Add Expense button uses:
<button type="button">Add Expense</button>
Multimedia
The project includes an image logo using the <img> element.
It also includes a YouTube budgeting video using the <iframe> element.
Interactive Elements
The project includes a <details> and <summary> section called "How to use this tracker".
The table rows change appearance when the mouse moves over them.
The Add Expense button uses cursor: pointer.
The form inputs also have a focus effect.
Advanced CSS Selectors
The project uses several advanced CSS selectors:
Descendant Selector
.expenses-section td
Direct Child Selector
.add-expense-section > h2
Position Pseudo-Class
tr:nth-child(even)
Negation Pseudo-Class
input:not([type="date"])
Focus Pseudo-Class
input:focus
Hover Pseudo-Class
tr:hover
Technologies Used
HTML5
CSS3
Visual Studio Code
GitHub
Future Improvements
JavaScript can be added in future weeks to make the Add Expense button functional and allow users to add expenses dynamically.
