Quiz
What does DOM stand for?
  Document Object Model.


What is the name of the object we can use to get information about the browser enviroment?
  Window

What is the name of the object that we can use to get access to the DOM representation of the page?
  Document

What type of files might we see in the Network tab for in Chrome devTools?
  All files inside our public folder.

What version of HTML is document.querySelector from?
  HTML5. 

Which event do we hook into when we want to know the DOM has loaded, window.onload or document.onload?

  document.onload is fired when the DOM is loaded, which may be before the images/css is loaded. Window.onload is invoked only when the entire page is loaded along with all its contents.



We use window.createElement to make new DOM elements, true or false?
  false.

List two ways to get all the elements by class 'cat'
  document.getElementsByClassName('cat');
  document.querySelectorAll('.cat');

List two ways to retrieve the element with id "goat"
  document.getElementById('goat');
  document.querySelector('#goat');

List two ways to get all the li elements
  document.querySelectorAll('li');
  document.getElementsByTagName('li');

List two ways to get the first li element
  document.querySelector('ul + li');
  or 
  document.querySelector('ol + li'); 
  document.querySelector('ol:first-child');
  document.querySelector('li:first-of-type');

How can we set the a given element to be hidden?
  a.style.display = 'none';
  a.style.visibility = 'hidden';