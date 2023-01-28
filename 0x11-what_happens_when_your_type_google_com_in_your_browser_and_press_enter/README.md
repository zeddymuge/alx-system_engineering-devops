## what happens when you type https://www.google.com in your browser and press Enter.


DNS request- Your computer sends a request to the DNS (Domain Name System) first, to resolve the domain name "google.com" to an IP address. This is because, unlike us, the computer communicate to each other using IP addresses.

TCP/IP - Once it has received the IP address, it establishes a secure Transmission Control Protocol (TCP) connection with the server using the Internet Protocol (IP). TCP/IP is the set of protocol that governs how data is transmitted.

Firewall - The firewall then checks the incoming requests against set of rules, to determine whether it should be allowed. Its job is to protect the server against malicious attacks.

HTTPS/SSL - Once the connection has been established, the browser sends a request to the server to access the webpage. Because Google uses HTTPS (Hypertext Transfer Protocol Secure), an additional layer of security is added in the form of an SSL (Secure Sockets Layer) certificate. This encrypts the communication between the browser and the server to protect sensitive information, such as login credentials, from being intercepted by third parties.

Load-balancer - Once information is received, it is passed to a Load balancer which will then distribute the workload to respective server using an algorithm. It helps improve scalability, reliability and performance of the servers.

Web server - The server receives the Get request and return the requested webserver that will then generate the HTML and CSS, images and JavaScript.

Application server - Some requests may also be routed to an application server, which runs the backend code that powers more dynamic features of the website, such as search functionality.

Database - The application server may need to obtain/retrieve the requested information that are contained in the Database.

Response: Once information has been received by the webserver or the application server, the response is sent back to the browser via TCP/IP protocol. The browser then renders the webpage and displays it on your screen.

