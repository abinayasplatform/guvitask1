Write a blog on Difference between HTTP1.1 vs HTTP2

INTRODUCTION:

    * HTTP - HyperText Transfer Protocol
    * HTTP was developed by Timothy Berners-Lee in 1989.
    * It is an application protocol that been the fact standard for communication on the World Wide Web (WWW).
    * HTTP is an application protocol that exchanges information between a client computer and a local or remote web server.

HTTP1.1:

    * HTTP1.1 released in 1997.
    * It was made more versatile,
    * In this process, a client sends a text-based request to a server by calling a method like GET or POST. 
    * In response, the server sends a resource like an HTML page back to the client.
    * The requests and responses will go back and forth between the server and client until the web browser has received all the resources necessary to render the contents of the HTML page on your screen.

HTTP2:

    * HTTP2 released in 2015.
    * It is also known as Reimagined version.
    * It decreases delay by using techniques such as compression, multiplexing, and prioritization.
    * Many browsers supported this standardization effort, including Chrome, Opera, Internet Explorer, and Safari.
    * It uses the binary framing layer to encapsulate all messages in binary format.


1.Multiplexing

HTTP1.1 : In HTTP1.1 each request and response was handled sequentially,it leads to latency and the web pages loading was slower.

HTTP2 : In HTTP2 multiple request and response was handled simultaneously over a single connection.It loads web pages faster and more efficient resource utilization.


2.Header Compression

HTTP1.1 : In HTTP/1.1 headers are sent in plaintext for every single request, resulting in redundant information being transmitted repeatedly.

HTTP2 : It emplos the header compression, reducing the size of headers by using a technique called HPACK. Redundancy is reduced,saves bandwidth and speeding up the loading of web pages.


3.Binary protocol 

HTTP1.1 : It used a text-based protocol, which was human-reachable but had some inefficiencies in parsing and processing.

HTTP2 : It used a binary-protocol,which means data is encoded in binary format.Allows for more efficient parsing and reduces complexity in data transmission.


4.Server push :

HTTP1.1 : All the resources must be requested by the client, leading to potential delays in fetching necessary assets.

HTTP2 : It allows servers to push additional resources to the client's cache without waiting for a request. This approach can enhance the performance of web applications.


5.Prioritization :

HTTP1.1 : Requests were treated equally, there is no prioritise.

HTTP2 : The concept of steam Prioritization is introduced, enabling the client to specify the priority of each resource.


CONCLUSION :

While HTTP/1.1 served the internet well for many years, the demands of modern web development and user expectations for faster and more efficient experiences necessitated a change.HTTP/2's multiplexing, header compression, binary framing, and server push capabilities collectively contribute to a more streamlined and faster web experience.