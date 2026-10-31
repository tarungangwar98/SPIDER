Assignment 1 –What happens between typing a URL and seeing the page?

When I type a URL in the browser and press Enter, 
a lot happens in just a few seconds. 
First, the browser needs to find the server. It checks its cache, 
and if the IP address is not saved there, 
it asks a DNS server to convert the domain name into an IP address.
After that, the browser connects to the server using TCP. 
If the website uses HTTPS, a TLS handshake also happens so that the data is encrypted and safe. 
Then the browser sends an HTTP request (like GET /index.html), 
and the server replies with a status code (like 200 OK) and the HTML file.
Once the HTML arrives, the browser reads it and 
builds the DOM. While reading, it finds links to CSS, 
JavaScript and images, so it downloads those files too. 
Then it combines the DOM and CSS to make the render tree, works out the layout, 
and paints the page on the screen. 
In the end, JavaScript runs and makes the page interactive.