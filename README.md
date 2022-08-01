# Day_03

The Difference between Document and Window Objects

Document object :

	The document object represent a web page that is loaded in the browser.
	The document object can be accessed with a 
						window.document
	It is loaded inside the window.
	By accessing the document object, we can can access the element in the HTML page.
	The document object is a property of the window object.

			Syntax : document =.property_name;

The Properties of document Objects thta are commonly used are body, cookie, domain,
URL, fullScrwwnElement, title, head
the Methods of Document 

			Syntax : document.method _name;

the most commonly used methods are addEventListener() , close(), createElement(),
createEvent(), createTextNode(), execCommand(), fullscreenEnabled(): It is used to 
check whether the document can be viewed in fullscreen mode or not. It returns a boolean value, write(): It is used to write some content or javascript code in the document.

Window Object :

	The window object is the topmost object of the DOM hierarchy. 
	The Window object is the JavaScript Global object.
	The window object represents the browser window or frame that displays the contents of the webpage.  
	It is the very first object that is loaded in the browser.
	
			Synntax : window.property_name;
			
		Closed, console: It returns a reference to the console object which provides access to the browser’s debugging console, defaultStatus: It is used to define the default message that will be displayed in the status bar when no activity is carried on by the browser. customElements: It returns a reference to the CustomElementRegistry object, which can be used to register new custom elements and also get information about already registered custom elements.	
			
			Methods of window Syntax: window.method_name;
			
			Methods in window elements that are commonly used are 
			
			alert(): It is used to display an alert box. It displays a specified message along with an OK button and used to make sure that the information comes through the user.
			close(): It is used for closing a certain window or tab of the browser which was previously opened.
			focus(): It is used to give focus to an element in the current window.
			open(): It is used to open a new tab or window with the specified URL and name.
			
			
			
			
