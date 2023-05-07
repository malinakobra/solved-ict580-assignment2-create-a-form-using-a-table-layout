Download Link: https://assignmentchef.com/product/solved-ict580-assignment2-create-a-form-using-a-table-layout
<br>
<strong>  </strong>Assessment 2

In assignment 1, you created a newsletter for a local restaurant called “Joan’s Tacos”. The owners liked your work, and now they have a new project. They want you to create a customer feedback form, and their designer team provide you with this design:

<strong><img decoding="async" data-recalc-dims="1" data-src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2020/05/420.png?w=980&amp;ssl=1" class="lazyload" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">

  <noscript>

   <img decoding="async" src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2020/05/420.png?w=980&amp;ssl=1" data-recalc-dims="1">

  </noscript>Page  of 6 </strong>

Requirement (Client requirement)

<ol>

 <li>You must use the <strong>table CSS layout;</strong> not the &lt;table&gt; tag. If you use the &lt;table&gt;, your work will be considered as an unacceptable work, and you will be graded with zero.</li>

 <li>All items must be in the same order and have the same style as shown in figure 2.</li>

 <li>First, last name, Email, and message are <strong>required fields.</strong></li>

 <li>All text fields must be validated. Use the pattern attribute and attach these regular expressions to each filed:

  <ol>

   <li>First, last name: [<strong>a-zA-Z0-9]+</strong></li>

   <li>Email: <strong>/^[a-z0-9._%+-]<a href="/cdn-cgi/l/email-protection" class="__cf_email__" data-cfemail="230863">[email protected]</a>[a-z0-9.-]+.[a-z]{2,4}$/</strong></li>

   <li>Telephone: <strong>d{3}[-]d{3}[-]d{4}</strong></li>

   <li>Zip Code: <strong>/^[A-Za-z]d[A-Za-z][ -]?d[A-Za-z]d$/</strong></li>

  </ol></li>

 <li>Apply access keys for each label using the first letter from each text field name. For example, for Email, the access key should be the first letter ‘E’.</li>

 <li>Users are only allowed to upload fills type of ‘.png’.</li>

 <li>An active or focus text filed must have a green border (Tip: use <em>‘: focus’</em>). The focus style should be as follows: Border color is #0C0.  <strong>2.</strong> Border size is 1 px. <strong>3.</strong> Border style/type is solid.</li>

 <li>The default value for the ‘what was your order?’ is <strong><em>Taco</em></strong>.</li>

 <li>The default value for the ‘How was your experience?’ is <strong><em>Good</em></strong>.</li>

 <li><em>Bounce requirements (+1 point): </em>

  <ol>

   <li>Change the ‘submit’ button background color when the mouse goes over it. To do that, use ‘:hover’ class and set it background-color to #4CAF50 and font color to #fff</li>

  </ol></li>

 <li>Use label elements to name all form elements. Use &lt;label for=””&gt; to create a label, then attached it to a form element such as input or box list.</li>

</ol>

<strong>Design details: </strong>

Submit (Only submit a single .zip file)

<ol>

 <li>Name your folder feedback_project.</li>

 <li>Right-click on the folder and choose ‘Send to’ -&gt; ‘Compressed (zipped) folder’.</li>

 <li>Upload the zipped folder to the Assignment 2 Dropbox</li>

</ol>

With using the instructions steps from assignment 1 (refer to assignment 1 document). I would recommend approaching this project using these steps:

<ol>

 <li>First, think of how to fit all the design elements (e.g. checkbox) into table elements (e.g. tablerow, col…etc.). You can draw a table over the provide design (I attached full size of the design at the end of this document). Draw the table header, rows, and cols and defined the sizes of the cols and rows.</li>

 <li>Second, define elements with similar style and group them under CSS selectors. Also, define which cells need to be merged.</li>

 <li>By now, you should be able to position contents on the layout. Create the content to fit its position on the layout. In the case of the table layout, the position can be a whole row or cell. I would recommend using percentage values to set the width for cells, rows, and cols.</li>

 <li>Apply all styles and keep fixing it until you get a similar result as the required design.</li>

 <li>Finally, apply the nonessentials style such as access keys, default values, focus style for text files…etc.</li>

</ol>

&#x25fc; Tips: tags and CSS properties you may need to use. Feel free to use any tag is not listed below:

<table width="0">

 <tbody>

  <tr>

   <td width="99"><strong>Tags </strong></td>

   <td width="120">Attributes</td>

   <td width="95">Value</td>

   <td rowspan="2" width="33">  </td>

   <td width="156"><strong>CSS </strong></td>

   <td width="131"><strong>CSS Values </strong></td>

  </tr>

  <tr>

   <td width="99">–          from–          input–          button–          hr–          select–          option–          optgroup–          textarea–          label</td>

   <td width="120">–          type–          name–          checked–          value–          selected–          pleaceholder–          for–          id–          file–          accept–          required–          novalidate–          pattern–          title–          accesskey </td>

   <td width="95">–  radio–  checkbox–  text–  button </td>

   <td width="156">–  :focus–  :valid–  :invalid–  :required–  Display </td>

   <td width="131">–  table–  table-row–  table-cell</td>

  </tr>

 </tbody>

</table>


