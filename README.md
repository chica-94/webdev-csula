# webdev_csula

# Overview of the Internet and the World Wide Web

## What is the Internet?
The Internet is a worldwide collection of networks. **The term Internet is derived from the term internetworking, which means connections of networks. **Simply put, the Internet is a large network of computers that communicate together.

The Internet is also decentralized, which means no one actually owns or runs the Internet.

At its most basic, we can think of the Internet as a system of wires encompassing almost every region in the world. These wires are very useful because two computers anywhere in the world connected directly to them can communicate.


### How does the Internet work?
As users of the Internet, we do not connect directly to the Internet.

Using different technologies such as Wifi or Ethernet (cable), we connect to the Internet through an Internet Service Provider (ISP) .

It is this collection of ISPs and computers connected to the ISPs that we refer to as the Internet.


### The Domain Name System(DNS)
Every computer connected to the Internet has a unique numeric address called Internet Protocol (IP) address. An IP address is made of strings of numbers.

Because it would be incredible difficult for Internet users to remember IP addresses, the **Domain Name System (DNS)** is a service running over the Internet that translates IP addresses to English-like names called **domain names**.

## What is the Web?
The **World Wide Web (WWW)** or **Web** is the most popular Internet service used for requesting, retrieving, formatting, and displaying information over the Internet.

The WWW is different from the Internet. **The Internet is the infrastructure, while the Web is a service built on top of that infrastructure **(and not the only one!).

Another way to look at this difference is that the Internet is a global network of computers while the Web is a collection of information accessed via the Internet.

### The Web: Web Pages
Information in the Web is made available through **web resources**, often just called resources, such as web pages, images, and other types of media.

A **web page** is a document used for presenting information on the Web. Web pages usually include hypertext. A **website** is a collection of web pages.

**Hypertext** consists of text containing references or links that users can follow to other documents. 


### The Web: HTTP
The Hypertext Transfer Protocol (HTTP) is the protocol used for transferring transferring web pages between a client and a server.

HTTP is the foundation of data communication in the Web. 

### Web Technologies
**HTML** stands for **Hyper Text Markup Language** and it is the standard language used for displaying content in a web browser.

**CSS** stands for **Cascading Style Sheets** and it is the standard language used for describing the presentation or style of a document written in HTML.

**JavaScript** is a programming language that allows you to implement complex features on web pages.

Small websites are often written just using **HTML** and **CSS**. However, larger websites, such as content  blogging sites and e-commerce software, often use of more technologies like **JavaScript**, databases, and other programming languages like PHP, Python, Ruby, or Java.


## Creating an HTML document
### Basic structure of an HTML document


### What is metadata?
While much of the content included in an HTML document is visible to the user, an HTML document can also include additional information called **metadata** that influences several aspects of the web page.

Metadata typically consists of descriptors of the content in the web page used by search engines and links to external resources such as JavaScript and CSS files and. 

Different tags can be used to specify metadata, such as the meta tag (meta tag) and the title tag. The **meta tag** is critical for implementing search engine optimization, as you will learn later.

Metadata is included inside the head element of an HTML document: 
```
<head>
<meta charset="utf-8"> 
<title>My home page</title>
</head>
```

An important  use of the meta tag is to specify the character encoding or charset of the web page:
```
<meta charset="utf-8"> 
```

This meta tag informs the browser about the encoding used to represent the text on the web page. **.**

**The current standard to be used in any web page (regardless of the language) is UTF-8.**