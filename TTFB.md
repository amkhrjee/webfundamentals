# Time To First Byte (TTFB) 
This response for this initial request contains the first byte of data received. Time to First Byte (TTFB) is the time between when the user made the request—say by clicking on a link—and the receipt of this first packet of HTML. 

> The first chunk of content is usually 14kb of data.

Time to First Byte (TTFB) refers to the time between the browser requesting a page and when it receives the first byte of information from the server.  This time includes DNS lookup and establishing the connection using a TCP handshake and SSL handshake if the request is made over https.

> `TTFB = responseStart - navigationStart`