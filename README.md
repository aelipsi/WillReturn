# Will Return

A simple one-page website that informs you that some input will return.

# Encoding Returner

To make sharing more fun, the name of the "returner" is Base64 encoded using ECMA btoa("string"). Add a URL parameter of "name" with a value of what you want to return. 

# Example Usage

To inform the world that "Elvis Presley" is coming back you would first Base64 encode the string to be "RWx2aXMgUHJlc2xleQ==". Then you would append it to the HTML page for the URL parameter "name". Thus the result is:
https://aelipsi.github.io/return.html?name=RWx2aXMgUHJlc2xleQ==

Then load the page, wait 1 second, and see the announcement.

 
