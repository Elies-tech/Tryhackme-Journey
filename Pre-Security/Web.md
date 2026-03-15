## How the Web Works

When a user enters a website address in the browser, several steps happen in the background before the page is displayed.

1. DNS Lookup

The browser first needs to find the IP address of the website.

It asks a DNS server to translate the domain name (for example google.com) into an IP address that computers can understand.

2. Establishing a Connection

Once the IP address is known, the client (your device) establishes a connection with the server.

This is usually done using the TCP protocol, which ensures reliable communication between the devices.

3. Sending a Request

After the connection is established, the browser sends an HTTP request to the server.

This request asks the server to send the data for the website (for example the HTML page).

4. Server Response

The server processes the request and sends back an HTTP response.

This response contains the requested data, such as:

HTML (structure of the page)

CSS (styling)

JavaScript (interactive elements)

5. Receiving and Displaying Data

The browser receives the response and starts rendering the website.

It processes the received files and displays the page so the user can interact with it.

All of this usually happens within milliseconds.