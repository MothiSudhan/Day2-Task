## Difference between DOCUMENTS and WINDOWS object

| Document Object  |  Windows Object |
| ---              |  ---            |
|Window object is the collection of objects with functions and variables to administrate and interact with the whole browser environment. | Document object provides the attribues for parsing the DOM files like HTML files,css and javacript files deployed in the particular website.|
|Document object is one of the object present in the Window object as a property.| One of the Objects in the Window Object. |
| It acts as a 'global object' where any variable or a function without a parent object falls inside this Window Object.example : 'var' keyword falls in to windows object as it is not block-scoped. | It provides the access to the contents of the webpage to manipulate the DOM,for example:Manipulating the HTML and Css while deveoping.|
| It provides properties and methods for interacting with the browser window, such as resizing the window, navigating to a different URL,asynchronous functions etc. | It connects the HTML documents and Javascript to read and Modify the DOM.|
|              | Does not involve in the manipulation of whole browser environment.This delas with the documents of the webpage to be parsed to the browser.|


In summary, while both the window and document objects are crucial for JavaScript interactions within a browser environment, the window object represents the browser window itself and provides methods and properties for managing the window, while the document object represents the HTML document loaded within the window and provides methods and properties for accessing and manipulating its content.