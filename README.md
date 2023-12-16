Introduction

Have you ever wondered what happens in the background when you type "google.com" into your browser and then push Enter? This simple-seeming action initiates a complex series of actions involving multiple web stack components. In this blog post, we'll examine the journey of a URL by looking at DNS requests, TCP/IP, firewalls, HTTPS/SSL, load balancers, web servers, application servers, and databases.

1. DNS Request:

The procedure begins with a first Domain Name System (DNS) request. The browser needs to translate the human-readable "www.google.com" into an IP address that servers can understand. It sends out a DNS server query, which may involve a number of steps, including examining the local cache, recursive DNS servers, and authoritative servers.

2. TCP/IP:

As soon as the browser receives the IP address, it establishes a Transmission Control Protocol (TCP) connection. Thanks to this trustworthy, connection-oriented protocol, data is transmitted accurately and without errors. The Internet Protocol (IP) then takes care of sending the data packets to the right place.

3. Firewall:

Firewalls are an obstacle that data packets must overcome to get to their intended location. Firewalls act as the first line of protection, filtering and allowing only authorized traffic. They are like the doorman or bouncer. They are necessary to maintain the security and integrity of the network.

4. HTTPS/SSL:

Security is crucial, especially when working with sensitive data. The browser and the server can establish a secure connection by using the Secure Sockets Layer (SSL) or Transport Layer Security (TLS) protocols and the Hypertext Transfer Protocol Secure (HTTPS) handshake. Because of this encryption, information sent between the browser and the server is kept secret.

5. Load Balancer:

For large websites like Google, incoming traffic needs to be efficiently distributed across multiple servers. Load balancers are necessary to achieve this because they ensure high availability, optimize resource utilization, and distribute requests equitably.

6. Web Server:

After passing via a load balancer, the request reaches a web server. Web servers manage static content, sending files like HTML, CSS, and other resources directly to the browser. These could be Nginx or Apache servers in the case of Google.

7. Application Server:

Application servers offer dynamic content, such as search results tailored to individual users. These servers use server-side code to establish connections with databases and other resources. Node.js and Django framework-powered application servers might be used by Google.

8. Database:

Databases work in the background to store and retrieve data. In the context of Google, databases might hold user information, indexed web pages, and other items. Two technologies that are useful for efficient data management are MongoDB and MySQL.

.. _`github`: https://github.com/VictorMaona/what-happens-when
.. _https://medium.com/@maonavictor/what-happens-when-you-type-google-com-in-your-browser-and-press-enter-421bde7d278d
