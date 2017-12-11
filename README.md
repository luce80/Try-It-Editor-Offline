# Try It Editor Offline

This is a wysiwyg "live" offline html editor. It is derived from [Try It Editor v3.3](http://www.learningslack.com/html/tryitfb35.html?filename=tryhtml_default) and [Try It Editor v3.5](https://www.w3schools.com/html/tryit.asp?filename=tryhtml_default).

It uses:
 - Fontello fonts
 - w3.css
 - codemirror.css
 - `Codemirror.js`
 - `FileSaver.js`

Main differences from original **Try It Editor v3.5** :
 - It updates preview at every key stroke
 - When divider is moved it preserves its position
 - It is possible to download previewed html
 - It can show the HTML source in a different tab/window

Due to origin restrisctions of the browsers, you can not save the document wherever you want and load one from wherever you want. What you should do is: download the document to the directory of this editor; load the document from the same directory of this editor, otherwise you will not be able to modify the loaded file.
When you save to localStorage the filename in the input field is used as the local name, so it is possible to save many pages but the available space in localStorage is limited so better not abuse of it.