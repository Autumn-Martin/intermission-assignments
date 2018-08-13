## How The Web Works

### Background:

Review the materials below.

* First let's read [MDN HOW WEB WORKS](https://developer.mozilla.org/en-US/Learn/Common_questions/How_does_the_Internet_work)
* Next let's watch a few quick examples of [how the internet works](https://www.youtube.com/watch?v=7_LPdttKXPc).
* And [how IP addresses work](https://www.youtube.com/watch?v=KFooN7Mu0IM   - how IP addresses work).
* Finally let's tie these things together and watch a video about [DNS - what happens when you type an address into a web browser](https://www.youtube.com/watch?v=72snZctFFtA).
* Lastly, let's read a little about [the anatomy of a URL](https://doepud.co.uk/blog/anatomy-of-a-url)

### Questions:

Now we have a better grasp about the internet, and how some of the things are working. Now, let's answer a few questions to check our understanding. Don't be afraid to do additional research (googleing) for an answer. Fork this gist and answer the following questions:

1. Describe, step by step, what happens when I type `www.example.com` into my browser and try to go to the page?

  * (1) client goes to the DNS server & finds the address of the server that the website lives on 
  * (2) client sends an HTTP request message across the internet connection using TCP/IP to the server to send a copy of the website to the client 
  * (3) If the server approves the client's request, the server sends the "200 OK" message to say so and then starts sending the website's files to the client as a series of small chunks called data packets. 
  * (4) The client assembles the small chunks into a complete website & displays it to you. 

1.  What does HTTP stand for?

  * **H**yper **T**ext **T**ransfer **P**rotocol
  
1. 	What protocol does the World Wide Web use?

  * HTTP/HTTPS
  
1. 	Each computer on the Internet is assigned an IP address, what does IP stand for?

  * **i**nternet **p**rotocol
  
1. 	What does DNS stand for?

  * A. Domain Name System
  * B. ~~Digital Number System~~
  * C. ~~Domain Number System~~
  * D. ~~Domain Name Service~~
  * E. ~~Digital Name Service~~
  
1. 	How are text domain names matched to their respective numeric IP addresses.

  * First, your browser asks your computer if it already knows what IP address the domain name points to (it may already know via a local DNS cache).
  * If your computer knows the associated IP address 
     * --> name is translated to the IP address based on local DNS cache
  * If your computer doesn't know the associated IP address 
     * --> the browser goes on to ask a DNS server, whose job is to answer that question. 

1. 	What is the client?

  *A. ~~A purchaser~~
  *B. ~~Internet shopping customer (Consumer)~~
  *C. The software which requests information from a server (browser)
  *D. ~~The server to which a particular computer sends data~~
  *E. ~~The computer which the IP address belongs to~~

1. 	What does URL stand for?

* **U**niform **R**esource **L**ocator

1. 	What are protocols

 * A. ~~The standardisation of IP addressess~~
 * B. ~~The DNS standard method for data transfer~~
 * C.	~~The standardised network address system~~
 * D.	The standardised method for transferring data or documents over a network
 * E.	~~The standardised method for prioratising data or document storage over a network~~
 
1. What does DNS stand for?

  * **D**omain **N**ame **S**ystem
  
1. what is the `www` portion of a url?

  * `www` stands for world wide web. The domain name, which is substituted for an IP address to indicate which web server is being requested. 
  
1. What is The markup language used for all web documents?

  * **H**yper**t**ext **M**arkup **L**anguage, or HTML

1. What is the organization that monitors web technologies?

  * W3C
  
1. What is the Protocol for transferring web documents on the Internet?

  * TCP/IP

1. What matches the domain names with numeric IP addresses?

  * A DNS server or a local DNS cache on your computer





