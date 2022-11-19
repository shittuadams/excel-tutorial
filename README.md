<h1>Excel for Data Analysis</h1>

<h2>Excel Keyboard Shortcuts</h2>
<p><img src="images/keyboard-shortcuts.png"></p>

<h2>Data Cleaning</h2>

<p>Data cleaning involves fixes inconsistencies in datasets. The following are some inconsistencies that could be preent in a data set and how to rectify them.</p>

<ol>
  
  <li>
    <p><b>Spell Checking:</b></p>
    <p>Select what data we wish to check for spelling. Then we click Spelling which is on the Review tab. If there is an error or a name has been misspelt, or more likely, mistyped. We just click Change if we are happy with the spelling suggestion, or we could choose another suggestion from the list, or even ignore this error if we know the data is correct.</p>
  </li>
  
  <li>
    <p><b>Check for empty cells:</b></p>
    <p>Use <b><code>CTRL+DOWN</code></b> ARROW to check if the there is a split of the dataset (to check for empty rows in the dataset). This could be used to check for empty cells too.</p>
     <p>There is a much better way - which involves selecting all our data first, either using the mouse, or the <b><code>CTRL+SHIFT+END</code></b> keyboard shortcut. Then we select the Filter icon on the Data tab. Click on the filter icon on a column, uncheck all and check blanks. This shows you all the blank cells in that column.</p>
  </li>
  
   <li>
    <p><b>Duplicated rows of data:</b></p>
    <p>How to remove duplicate rows.</p>
    <p><b><code>METHOD 1</code></b></p>
    <p>
     Select a column that shouldn't have duplicates and choose Conditional Formatting, then Highlight Cells Rules, and then Duplicate Values. When we click OK, and scroll down the sheet, we wll see that only a few values have been identified as being duplicates. Next step is to delete the duplicated rows of data.
    </p>
    <p><b><code>METHOD 2</code></b></p>
    <p>
     Select the whole datasheet, and on the Data tab, we use the Remove Duplicates button. We then unselect all the columns, then only select the a column which we want to check duplicates for. Click ok to remove or delete the duplicate rows. This method is less secure.
    </p>
    <p><img src="images/duplicates.png"></p>
  
  </li>
  
   <li>
    <p><b>Misspelt Names:</b></p>
    <p>The <b><code>Find & Replace</code></b> feature to repair some misspelt names. <b><code>Find and Replace</code></b> tools are under Find & Select on the Home tab in Excel. Type the misspelt name into the <b><code>‘Find what’</code></b> box and click <b><code>Find Next</code></b>, then click it again to see there are multiple incorrect entries. If we click <b><code>Find All</code></b>, all instances are listed, and we can open the <b><code>Replace</code></b> tab to enter a name to replace the incorrect spellings.</p>
    </li>
    
    
   <li>
    <p><b>Case Inconsistencies:</b></p>
    <p>
      The <b><code>UPPER, LOWER, and PROPER</code></b> functions can help you change the case of text in your data.  If you want to change from uppercase characters to use proper case then you need to add another row to put the function in; this is referred to as a ‘helper’ row. The <b><code>PROPER</code></b> function is simple to use; you can use SHIFT+RIGHT ARROW to select the columns across to X first then press F2 to bring the cursor into focus in cell A2 then you hold down the CTRL key while you press Enter, and it fills across for you. You might think that you could now remove the original row; but look what happens when you do; you get a REF error because the formula is referencing an invalid reference, and the header row cells now contain just the failed formula rather than the actual header text. So, you need to undo that, and instead, you copy the contents of the helper row to row 1 but when you paste you need to choose the Paste Values option. Now the header row cells just contain header text, and you can remove the helper row in row 2.
    </p>
    <p>
      The <b><code>UPPER</code></b> function is used to change characters to uppercase, while the <b><code>LOWER</code></b> function is used to change characters to lower case.
    </p>  
    <p><img src="images/excel-case.jpg"></p>
    </li>
  
</ol>
