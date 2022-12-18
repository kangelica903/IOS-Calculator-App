# IOS-Calculator-App

The Document Object Model (DOM):

- is a logical structure that defines how elements in a document that can be manipulated & changed.
- commonly referred to as a tree in which everything is connected
  can access, modify, delete, or add new elements or content to a document using DOM

getElementbyId():

- select an element on a webpage that has an id
- only selects the first unique element on a page even if there are multiple items w/ the same id

getElementsByClassName

- is a method to select any element that has a class

getElementsByTagName

- is a method to select any tags

querySelector() & querySelectorAll()

- can select any element in the DOM
- querySelector() selects a single element & if there are multiple of the same element. Only the 1st one is chosen.
- querySelectorAll() will select all items in the document that match the selector

document.createElement()

- Creates a DOM Element

setAttribute()

- set the attributes, such as adding a class, changing the ID or changing the SRC

setAttribute("attribute", "value")

- takes two parameters (attribute & value) to be applied to the attribute

createTextNode()

- creates texts & add them to our newly created elements

removeChild()

- can remove elements in the DOM

forEach()

- This method will loop through the array & run a function that you define for each item in the array.

addEventListener()

- This method will accept one argument.

removeEventListener()

- This method will remove an event listener from an element
