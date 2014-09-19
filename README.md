quickModal
==========

###jQuery Modal Dialog Plug-in

quickModal is a jQuery plug in that creates a modal dialog from a div on the page, using the trigger's href attribute to set which div to display.

* Multiple instances on a single page
* Customizable via plug in options and css
* Lightweight (1.8kb minimized)
* Clicking out of the modal area closes modal (i.e., close button optional)

###The Basics

 See the documentation in the quickModal.html file for options and a demo.

1. Make sure you have jQuery, add link to the quickModal.min.js script after jQuery link.
2. Link to the quickModal.css or include the relevant styles in your css file. Style it up.
3. Create a div with and ID or class that you will use to call the modal with, and put the modal content in the div. Header and footer are optional.
4. Create the trigger element
5. Call the modal: `$('.modalTrigger').quickModal();`

###Download Includes

* Formatted and minified versions of the script
* Demo page with modal and options information
* CSS for the modal
* CSS for the demo page 
* Readme and MIT license