# searchbar
This code uses jQuery to get the value of a query parameter from the current URL and set it to the value of the search bar.
The first line of code uses the jQuery(document).ready() function to tell jQuery to execute the function inside the curly braces when the document is ready.
The next line of code creates a new URLSearchParams object and sets it to the value of the current URL using the window.location.search property.
The following line of code gets the value of the query parameter named s from the URLSearchParams object.
The last line of code sets the value of the search bar to the value of the query parameter named s using the val() method.
This code can be used to set the value of the search bar to the value of a query parameter from the current URL. This can be useful for a variety of purposes, such as pre-populating the search bar with a search term that the user has entered previously.
