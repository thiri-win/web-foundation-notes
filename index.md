# Web Foundation အခြေခံများ ကို beginner များအတွက် note ထုတ်ထားတာပါ

- [Web Basic](#How-the-internet-work) internet, web, host များ ဘယ်လို အလုပ်လုပ်လဲ နားလည်နိင်ရန်အတွက်ပါ

- [HTML](#What-is-Hyper-Text-Markup-Language?) html elements များကို ဘယ်လိုအသုံးပြုရမလဲဆိုတာတွေပါဝင်မှာပါ

- [CSS](#What-is-CSS?) style sheet ထဲမှာ အသုံးပြုနိုင်ရန်ပါဝင်ပါတယ်

- [Javascript](#What-is-JavaScript) js ကို web ထဲတွင် အသုံးချနိုင်ရန် အခြေခံ အကြောင်းအရာများပါဝင်သွားမှာပါ

How the internet work
=====================

There are two main concepts that are fundamental to the way the Internet functions: packets and protocols.

Packets
-------

In networking, a packet is a small segment of a larger message. Each packet contains both data and information about that data. When data gets sent over the Internet, it is first broken up into smaller packets, which are then translated into bits. Packets are sent across the Internet using a technique called packet switching. Intermediary routers and switches are able to process packets independently from each other, without accounting for their source or destination.

Protocols
---------

In networking, a protocol is a standardized way of doing certain actions and formatting data so that two or more devices are able to communicate with and understand each other. There are protocols for sending packets between devices on the same network (Ethernet), for sending packets from network to network (IP), for ensuring those packets successfully arrive in order (TCP), and for formatting data for websites and applications (HTTP). In addition to these foundational protocols, there are also protocols for routing, testing, and encryption. And there are alternatives to the protocols listed above for different types of content - for instance, streaming video often uses UDP instead of TCP.

What is a web server and how does it work?
==========================================

A server is a computer that runs applications and services ranging from websites to instant messaging. It's called a server because it provides a service to another computer and its user also known as the client. Is typically stored in something called a data center with hundreds or thousands of other servers, all running different services connected to the internet. A web server is software and hardware that uses HTTP (Hypertext Transfer Protocol) and other protocols to respond to client requests made over the World Wide Web. The main job of a web server is to display website content through storing, processing and delivering webpages to users.

![](../images/pic-1.png)

What are websites and webpages?
===============================

What is a Website?
------------------

A website is a combination or collection of webpages grouped together, often handled by a person or an organisation, which can be accessed anywhere and anytime by anyone via the internet. This is also a good method to market the businesses and help them grow well. Al these pages are linked together using the hyperlinks. Websites can also be either static or interactive. In the meantime, some popular categories of websites are affiliate websites, e-commerce websites, dating websites, social networking websites and more.

What is a Webpage?
------------------

Webpage, in the meanwhile, is a single document or page that is displayed in web browsers like the Firefox, Google Chrome, Opera and so on. This is used to make up the World Wide Web (WWW) and is used chiefly to sell products and services to users or visitors. A unique URL address is also attached to the webpages and is used to render or access that particular page. Webpages can also be either static or dynamic.

What is a web browser and how does it work?
===========================================

A web browser takes you anywhere on the internet. It retrieves information from other parts of the web and displays it on your desktop or mobile device. The information is transferred using the Hypertext Transfer Protocol, which defines how text, images and video are transmitted on the web. When the web browser fetches data from an internet connected server, it uses a piece of software called a rendering engine to translate that data into text and images. This data is written in Hypertext Markup Language (HTML) and web browsers read this code to create what we see, hear and experience on the internet.

Web hosting
===========

A web hosting service is a type of Internet hosting service that hosts websites for clients, i.e. it offers the facilities required for them to create and maintain a site and makes it accessible on the World Wide Web. Companies providing web hosting services are sometimes called web hosts.

How Does Web Hosting Work?
--------------------------

When you set up an online business, you have a series of files, images, and HTML code that make up your website. These files take up space and need a place to live. Without an online home, your files would just sit on your computer and no one would ever see them. A hosting provider will provide a place on a web server to store all of your files and are responsible for delivering the files of your website as soon as a browser makes a request by typing in your domain name.

What is a Domain Name?
----------------------

if you are renting space at a physical location for your business, you give customers. your street address so they can find you. If you are renting space on the internet, you give customers your domain name. Whenever someone types in your domain name, it is converted into an IP address. The hosting company then locates all the files connected to your IP address and returns all of the pictures, videos, and words that make up your website.

How to Choose a Hosting Provider?
---------------------------------

When selecting a provider it is important to consider the different types of hosting services that are offered. Here are a few things to consider when determining where vou would like to host your site.

*   What type of website are you building? eCommerce, blog, portfolio, etc.
*   Based on the type website, what is the bandwidth needed to run your site
*   Can you create email addresses for vour domain?
*   What type of hosting options are available?
*   Do they provide SSL Certificates?

Types of Web Hosting
--------------------

1.  Shared Hosting
2.  Dedicated Hosting
3.  VPS Hosting
4.  Cloud Hosting

### Shared Hosting

Shared hosting is the most common type of web hosting and is suitable for most online business owners. With shared hosting, several customers share storage space on one powerful server. There are several advantages to shared hosting including:

*   Affordability - It's much cheaper to share the space on a server than to rent the entire machine.
*   Ease of use- Your server is preconfigured, well-organized, easy to use, and your hosting company does all the maintenance and security updates for you.

### Dedicated Hosting

Rather than sharing space, you get a server all to yourself if you choose a dedicated hosting package. Advantages to dedicated hosting include:

*   Customization - You can customize the software and hardware to meet your individual needs
*   Unlimited Resources- Since you don't share the server with anyone, all the storage space is yours.
*   Full control - You can configure the setup however you'd like.

### VPS Hosting

Virtual Private Server (VPS) hosting includes all the features of a dedicated server, but at the price point of a shared server. Here are some of the top reasons VPS hosting might be a great fit:

*   Functionality - VPS hosting is built on a cPanel and supports easy navigation with several intuitive tools.
*   One-click features - You have access to one-click installs of WordPress, Magento, and Drupal.
*   Easy site navigation - The clean interface makes site management a cinch.

Cloud Hosting
-------------

Cloud hosting is often considered the most reliable of all of the services. Rather than relying on disk space of a single server, it pulls its power from several resources, making sure you never have any downtime. Other benefits include:

*   Scalability - You can add to your cloud space at any time.
*   Unmetered bandwidth - You don't have to worry about your site going down due to a server failure.

Internet Protocols
==================

The Internet Protocol (IP) is a protocol, or set of rules, for routing and addressing packets of data so that they can travel across networks and arrive at the correct destination. Data traversing the Internet is divided into smaller pieces, called packets. IP information is attached to each packet, and this information helps routers to send packets to the right place. Every device or domain that connects to the Internet is assigned an IP address, and as packets are directed to the IP address attached to them, data arrives where it is needed. Once the packets arrive at their destination, they are handled differently depending on which transport protocol is used in combination with IP. The most common transport protocols are TCP and UDP.

HTTP
====

Hypertext Transfer Protocol (HTTP) is an application-layer protocol for transmitting hypermedia documents, such as HTML. It was designed for communication between web browsers and web servers, but it can also be used for other purposes. HTTP follows a classical client-server model, with a client opening a connection to make a request, then waiting until it receives a response. HTTP is a stateless protocol, meaning that the server does not keep any data (state) between two requests.

|HTTP Methods|Description|
|------------|-----------|
|GET|The client requests a resource on the web server|
|POST|The client submits data to a resource on the web server|
|PUT|The client replaces a resource on the web server|
|DELETE|The client deletes a resource on the web server|

Frameworks and Libraries
========================

What is Framework?
------------------

Frameworks are program scaffolds that supply the blueprint instead of a finished product. As a result, a framework gives the fundamental structure while indicating the required customization from the coder. The framework defines the workflow of a software application, informs the developer of what he needs, and invokes the developer's code when necessary.

What is Library?
----------------

A library is a group of pre-written codes that make jobs easier to complete. A library is a collection of pre-defined methods and classes that developers can use to ease their work and accelerate development. As a result, developers do not need to write code to achieve specific features. Most programming languages include standard libraries, but developers can create their own customized libraries.

Web Application & Website
=========================

Web Application
---------------

Web application is a piece of software that can be accessed by the browser. A Browser is an application that is used to browse the internet. Web application needs authentication. The web application uses a combination of server-side scripts and client-side scripts to present information. It requires a server to manage requests from the users. Example: Google Apps, Amazon, YouTube

Website
-------

Website is a collection of related web pages that contains images, text, audio, video, etc. It can be consist of one page, two pages, and n number of pages. Awebsite provides visual and text content that users can view and read. To view a website requires a browser(Chrome, Firefox). There are many types of websites like Archive website, Blog, Community website, etc.

What is an API Application Programming Interface?
=================================================

The term API, also known as Application Programming Interface, is a set of protocols and definitions that can allow one application to communicate with the other application. It is a computing interface that is being used to define interactions between various software intermediaries. It will define the kinds of requests and calls that can be made. It is an information gateway that will allow the software and services' backend to communicate with each other.

What is an IDE?
===============

An IDE, or Integrated Development Environment, enables programmers to consolidate the different aspects of writing a computer program. IDEs increase programmer productivity by combining common activities of writing software into a single application: editing source code, building executables, and debugging.

What is Hyper Text Markup Language?
===================================

HTML (HyperText Markup Language) is the most basic building block of the Web. It defines the meaning and structure of web content. Other technologies besides HTML are generally used to describe a web page's appearance/ presentation (CSS) or functionality/ behavior (JavaScript). "Hypertext" refers to links that connect web pages to one another, either within a single website or between websites. Links are a fundamental aspect of the Web. By uploading content to the Internet and linking it to pages created by other people, you become an active participant in the World Wide Web.
![html](https://gist.github.com/user-attachments/assets/b1de4ff4-2b57-410a-9a65-d3d3ad07bcde)

## HTML Basic

*   `<html>` : Every HTML code must be enclosed between basic HTML tags. It begins with `<html>` and ends with `</html>` tag.
*   `<head>` : The head tag comes next which contains all the header information of the web page or documents like the title of the page and other miscellaneous information. This information is enclosed within the head tag which opens with `<head>` and ends with `</head>`. The contents will of this tag will be explained in the later sections of the course.
*   `<title>` : We can mention the title of a web page using the `<title>` tag. This is header information and hence is mentioned within the header tags. The tag begins with `<title>` and ends with `</title>`.
*   `<body>` : Next step is the most important of all the tags we have learned so far. The body tag contains the actual body of the page which will be visible to all the users. This opens with `<body>` and ends with `</body>`. All content enclosed within this tag will be shown on the web page be it writings or images or audio or videos or even links. We will see later in the section how using various tags we may insert mentioned contents into our web pages.

## HTML - Heading Elements

A HTML heading or HTML `h` tag can be defined as a title or a subtitle which you want to display on the webpage.h1 is the largest heading tag and h6 is the smallest one. So h1 is used for most important heading and h6 is used for least important.
| syntax | description          |
| ------ | -------------------- |
| `<h1>` | `<h1>heading 1</h1>` |
| `<h2>` | `<h2>heading 2</h2>` |
| `<h3>` | `<h3>heading 3</h3>` |
| `<h4>` | `<h4>heading 4</h4>` |
| `<h5>` | `<h5>heading 5</h5>` |
| `<h6>` | `<h6>heading 6</h6>` |

## HTML - Paragraph

HTML paragraph or HTML `p` tag is used to define a paragraph in a webpage. Let's take a simple example to see how it work. It is a notable point that a browser itself add an empty line before and after a paragraph. An HTML `<p>` tag indicates starting of new paragraph.

```html
<p>This is the first paragph.</p>  
<p>This is the second paragph.</p>   
<p>This is the third paragph.</p>  
```

## HTML - Phrasing Elements

HTML tags are like keywords which defines that how web browser will format and display the content. With the help of tags, a web browser can distinguish between an HTML content and a simple content. HTML tags contain three main parts: opening tag, content and closing tag. But some HTML tags are unclosed tags.

| syntax                                 | description                          |
| -------------------------------------- | ------------------------------------ |
| `<b>bold tag </b>`                     | **bold tag**                         |
| `<strong>strong tag</strong>`          | **strong tag**                       |
| `<i>italic tag </i>`                   | _italic tag_                         |
| `<em>emphasized tag</em>`              | _emphasized tag_                     |
| `<u>underline tag</u>`                 | <ins>underline tag</ins>             |
| `<mark>marked text</mark>`             | <mark>marked text</mark>             |
| `<small>smaller text</small>`          | <small>smaller text</small>          |
| `<del>deleted text</del>`              | ~~deleted text~~                     |
| `<ins>inserted text</ins>`             | <ins>inserted text</ins>             |
| `<sub>subscript</sub> text`            | This is <sub>subscript</sub> text    |
| `<sup>superscript</sup> text`          | This is <sup>superscript</sup> text  |
| `<abbr>abbreviation tag</abbr>`        | <abbr>abbreviation tag</abbr>        |
| `<dfn>definition tag</dfn>`            | <dfn>definition tag</dfn>            |
| `<blockquote>quoting tag</blockquote>` | <blockquote>quoting tag</blockquote> |
| `<q>short quote tag</q>`               | <q>short quote tag</q>               |
| `<code>code tag</code>`                | `code tag`                           |
| `<kbd>keyboard tag</kbd>`              | <kbd>keyboard tag</kbd>              |
| `<address>address tag</address>`       | <address>address tag</address>       |

## HTML - Text Links

A webpage can contain various links that take you directly to other pages and even specific parts of a given page. These links are known as hyperlinks. Hyperlinks allow visitors to navigate between Web sites by clicking on words, phrases, and images. Thus you can create hyperlinks using text or images available on a webpage.

```html
<a href="https://hello.com">"Hello Website</a>
<a href="mailto: contact@hello.com">"Email To Me</a>
<a href="tel: +959123456">"Call Me</a>
<a href="myprofile.png” download">"Download Pic</a>
<a href="home.html#heading">"Heading</a>
```
a element အတွက် target attribute လေးတွေကို ဒီလိုလည်း သုံးလို့ရပါတယ်

*   <mark>_blank </mark> : Opens the linked document in a new window or tab.  
`<a href="home.html#heading" target="_blank">"Heading</a>`
*   <mark>_self </mark> : Opens the linked document in the same frame.  
`<a href="home.html#heading" target="_self">"Heading</a>`
*   <mark>_parent </mark> : Opens the linked document in the parent frame.  
`<a href="home.html#heading" target="_parent">"Heading</a>`
*   <mark>_top </mark> : Opens the linked document in the full body of the window.  
`<a href="home.html#heading" target="_top">"Heading</a>`

## HTML - Lists

HTML offers web authors three ways for specifying lists of information. Al lists must contain one or more list elements. Lists may contain -  
`<ul>` - An unordered list. This will list items using plain bullets.
```html
<ul>                                         
    <li>list 1</li>                                         
    <li>list 2</li>                                         
    <li>list 3</li>                                         
    <li>list 4</li>                                         
    <li>list 5<li>                                     
</ul>
```
`<ol>` - An ordered list. This will use different schemes of numbers to list your items.
```html
<ol>                                         
    <li>list 1</li>                                         
    <li>list 2</li>                                         
    <li>list 3</li>                                         
    <li>list 4</li>                                         
    <li>list 5<li>                                     
</ol>
```

## HTML - Media Elements

### Figure
`<figure>` tag ကို ပုံ၊ ဗီဒီယို စတဲ့ media content ကိုဖော်ပြဖို့ သက်ဆိုင်တဲ့ (caption) ရှိတဲ့ အခါအသုံးပြုတယ်။
figure က semantic tag ဖြစ်ပြီး၊ ပုံနဲ့ အညွှန်းစာသားတို့ကို အတူတူ ရေးဖို့သုံးပါတယ်။
```html
<figure>
    <img src="image.jpg" alt="A beautiful sunset">
    <figcaption>A beautiful sunset over the mountains.</figcaption>
</figure>
```

### Images

You can insert any image in your web page by using <img> tag. The <img> tag is an empty tag, which means that, it can contain only list of attributes and it has no closing tag. The alt attribute is a mandatory attribute which specifies an alternate text for an image, if the image cannot be displayed.

`<img src ="/images/test.png" alt ="Test Image" />`

### Video

*   The HTML `<video>` element is used to show a video on a web page.

```html
<video width="500" height="300" controls>
    <source src="movie.mp4" type="video/mp4">
    <source src="movie.ogg" type="video/ogg">
    Your browser does not support this video                                     
</video>
```

### Audio
The HTML `<audio>` element is used to play an audio file on a web page.
```html
<audio controls>                                            
    <source src="happy.ogg" type="type/ogg">                                         
    <source src="happy.mp3" type="type/mpeg">                                         
    Your browser does not support this audio.                                     
</audio>
```

### Youtube Video
```html
<iframe width="966" height="543" src="https://www.youtube.com/embed/oOjtEsVMacY?list=RDMM"></iframe>
```

## HTML - Tables

The HTML tables allow web authors to arrange data like text, images, links, other tables, etc. into rows and columns of cells. The HTML tables are created using the `<table>` tag in which the `<tr>` tag is used to create table rows and `<td>` tag is used to create data cells. The elements under `<td>` are regular and left aligned by default.

*   Table heading can be defined using `<th>` tag.
*   Cellpadding and Cellspacing Attributes
*   `<table border="1" cellpadding="5" cellspacing="5"></table>`
*   Colspan and Rowspan Attributes

```html
<table border="1">                     
    <tr>
        <th>Column 1</th>                                         
        <th>Column 2</th>                                         
        <th>Column 3</th>                                     
    </tr>                                 
    <tr>                                         
        <td rowspan="2">Row 1 Cell 1</td>                                         
        <td>Row 1 Cell 2</td>                                         
        <td>Row 1 Cell 3</td>                                     
    </tr>                                     
    <tr>                                         
        <td>Row 2 Cell 2</td>                                         
        <td>Row 2 Cell 3</td>                                     
    </tr>                                     
    <tr>                                         
        <td colspan="3">Row 3 Cell 1</td>                                     
    </tr>                                 
</table>
```

## HTML - Forms

The HTML form element is used to create HTML Form
`<form></form>`

| attribute    | value                                   | description                                                                                                                                                                                                                                  |
| ------------ | --------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| action       | action                                  | `<form action=”login.php”></form>`                                                                                                                                                                                                          |
| target       | _blank<br>_self<br>_parent<br>_top                                 | `<form action=”login.php” target=”_blank”></form>`<br>`<form action=”login.php” target=”_self”></form>`<br>`<form action=”login.php” target=”_parent”></form>`<br>`<form action=”login.php” target=”_top”></form>` |
| method       | get<br>post                             | `<form action=”login.php” method=”get”></form>`<br>`<form action=”login.php” method=”post”></form>`                                                                                                                                          |
| autocomplete | on<br>off | `<form action=”login.php” autocomplete=”on”></form>`<br>`<form action=”login.php” autocomplete=”off”></form>`                                                                                                                                |
### Forms - Input Elements
|HTML|Output|
|----|------|
|`<input type="button">`|<input type="button" style="width: 100px">|
|`<input type="checkbox">`|<input type="checkbox">|
|`<input type="color">`|<input type="color">|
|`<input type="date">`|<input type="date">|
|`<input type="datetime-local">`|<input type="datetime-local">|
|`<input type="email">`|<input type="email">|
|`<input type="file">`|<input type="file">|
|`<input type="hidden">`|<input type="hidden">|
|`<input type="image" src=”img/photo.jpg” alt=”photo”>`|<input type="image" src=”img/photo.jpg” alt=”photo”>|
|`<input type="month">`|<input type="month">|
|`<input type="number">`|<input type="number">|
|`<input type="password">`|<input type="password">|
|`<input type="radio">`|<input type="radio">|
|`<input type="range" min=”10” max=”90” step=”10”>`|<input type="range" min=”10” max=”90” step=”10”>|
|`<input type="reset">`|<input type="reset">|
|`<input type="search">`|<input type="search">|
|`<input type="submit">`|<input type="submit">|
|`<input type="tel">`|<input type="tel">|
|`<input type="text">`|<input type="text">|
|`<input type="time">`|<input type="time">|
|`<input type="url">`|<input type="url">|
|`<input type="week">`|<input type="week">|

### Forms - Input Elements Attribute

| attribute    | description                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              |
| ------------ | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| value        | * `<input type="text" value="John">`<br> * specifies an initial value for an input field                                                                                                                                                                                                                                                                                                                                                                                                                                                                 |
| readonly     | *   `<input type="text" value="John" readonly>`<br>*   specifies that an input field is read-only.                                                                                                                                                                                                                                                                                                                                                                                                                                                       |
| disabled     | *   `<input type="text" value="John" disabled>`  <br>*   specifies that an input field should be disabled.                                                                                                                                                                                                                                                                                                                                                                                                                                               |
| size         | *   `<input type="text" name="firstname" size="20">`  <br>*   specifies the visible width, in characters, of an input field.<br>*   The default value for size is 20                                                                                                                                                                                                                                                                                                                                                                                     |
| maxlength    | *   `<input type="text" name="firstname" maxlength="5">`  <br>*   specifies the maximum number of characters allowed in an input field.                                                                                                                                                                                                                                                                                                                                                                                                                  |
| min          | *   `<input type="date" name="dob" min="1980-11-31">`  <br>*   specify the minimum values for an input field.<br>*   min attributes work with the following input types: number, range, date, datetime-local, month, time and week.                                                                                                                                                                                                                                                                                                                      |
| max          | *   `<input type="date" name="dob" max="2023-04-01">`  <br>*   specify the maximum values for an input field.<br>*   max attributes work with the following input types: number, range, date, datetime-local, month, time and week.<br>                                                                                                                                                                                                                                                                                                                  |
| multiple     | *   `<input type="files" name="photos" multiple>`  <br>*   specifies that the user is allowed to enter more than one value in an input field.<br>*   attribute works with the following input types: email, and file.<br>                                                                                                                                                                                                                                                                                                                                |
| pattern      | *   `<input type="text" name="code" pattern="\[A-Za-z\]{3}">`  <br>*   The input pattern attribute specifies a regular expression that the input field's value is checked against, when the form is submitted.<br>*   The pattern attribute works with the following input types: text, date, search, url, tel, email, and password.                                                                                                                                                                                                                     |
| placeholder  | *   `<input type="text" name="firstname" placeholder="Enter Your First Name Here...">`  <br>*   The short hint is displayed in the input field before the user enters a value.<br>*   The placeholder attribute works with the following input types: text, search, url, tel, email, and password.<br>                                                                                                                                                                                                                                                   |
| required     | *   `<input type="text" name="firstname" required>`  <br>*   The input required attribute specifies that an input field must be filled out before submitting the form.<br>*   The required attribute works with the following input types: text, search, url, tel, email, password, date pickers, number, checkbox, radio, and file.                                                                                                                                                                                                                     |
| step         | *   `<input type="number" id="points" name="points" step="3">`  <br>*   The input step attribute specifies the legal number intervals for an input field.<br>*   Example: if step="3", legal numbers could be -3, 0, 3, 6, etc.<br>*   Tip: This attribute can be used together with the max and min attributes to create a range of legal values.<br>*   The step attribute works with the following input types: number, range, date, datetime-local, month, time and week.                                                                            |
| autofocus    | *   `<input type="text" name="firstname" autofocus>`<br>*   The input autofocus attribute specifies that an input field should automatically get focus when the page loads.                                                                                                                                                                                                                                                                                                                                                                              |
| list         | * The input list attribute refers to a element that contains pre-defined options for an  element.<br> `<input list="browsers">`<br>`<datalist id="browsers">`<br>&nbsp;&nbsp;&nbsp;&nbsp;`<option value="Internet Explorer">Internet Explorer</option>`<br>&nbsp;&nbsp;&nbsp;&nbsp;`<option value="Firefox">Firefox</option>`<br>&nbsp;&nbsp;&nbsp;&nbsp;`<option value="Chrome">Chrome</option>`<br>&nbsp;&nbsp;&nbsp;&nbsp;`<option value="Opera">Opera</option>`<br>&nbsp;&nbsp;&nbsp;&nbsp;`<option value="Safari">Safari</option>`<br>`</datalist>` |
| autocomplete | `<input type="text" name="firstname" autocomplete="off">`<br>*   The input autocomplete attribute specifies whether a form or an input field should have autocomplete on or off.<br>*   Autocomplete allows the browser to predict the value. When a user starts to type in a field, the browser should display options to fill in the field, based on earlier typed values.<br>*   The autocomplete attribute works with `<form>` and the following `<input>` types: text, search, url, tel, email, password, datepickers, range, and color.            |

The HTML `<form>` element can have one or more following elements:

### Forms - Label Element

*   defines a label for several form elements.
*   useful for screen-reader users, because the screen-reader will read out loud the label when the user focus on the input element.
*   help users who have difficulty clicking on very small regions (such as radio buttons or checkboxes) - because when the user clicks the text within the `<label>` element, it toggles the radio button/checkbox.
*   The `for` attribute of the `label` tag should be equal to the `id` attribute of the `input` element to bind them together.  
```html
<label for="name">Your Name:</label>
```

### Forms - Select Element

*   The select element defines a drop-down list:
*   The options elements defines an option that can be selected.
*   By default, the first item in the drop-down list is selected.
*   To define a pre-selected option, add the selected attribute to the option:
```html
<select name="programming" id="programming" multiple>
    <option value="php">PHP</option>
    <option value="py">Python</option>
    <option value="js">Javascript</option>
    <option value="mysql">MySql</option>
</select>
```

### Forms - Datalist Element


The `<datalist>` element in HTML is used to provide a list of predefined options to an `<input>` element. It helps users by suggesting available options as they type, improving usability.  

```html
<input list="languages" name="lang">                                             
<datalist id="languages">                                                 
    <option value="Javascript"></option>                                                 
    <option value="PHP"></option>                                                 
    <option value="Python"></option>                                                 
    <option value="Java"></option>                                                 
    <option value="C#"></option>                                             
</datalist>
```
### Form - optgroup
The `<optgroup>` element in HTML is used to group related options within a `<select>` element. It helps organize options in a dropdown menu, making it easier for users to navigate through the list.
```html
<select name="type">                                                 
    <optgroup label="Backend Developer">                                                     
        <option value="php">PHP Developer</option>                         
        <option value="laravel">Laravel Developer</option>                     
    </optgroup>
    <optgroup label="Frontend Developer">                        
        <option value="react">React Developer</option>                         
        <option value="vue">Vue Developer</option>                     
    </optgroup>
</select>
```

### Forms - Textarea Element

*   defines a multi-line input field (a text area):
*   The rows attribute specifies the visible number of lines in a text area.
*   The cols attribute specifies the visible width of a text area.
```html
<textarea name="" id="" cols="30" rows="10"></textarea>
```

### Forms - Button Element

*   defines a clickable button
```html
<button type="submit">Submit</button>
```

### Forms - Fieldset and Legend

*   The fieldset element is used to group related data in a form.
*   the legend element defines a caption for the fieldset element.
```html
<fieldset>
    <legend>Personal Information</legend>
    <label for="name">Name:</label>
    <input type="text" placeholder="Enter Your Name">
</fieldset>
```

What is CSS?
============
*   used to make web pages presentable.
*   the first technology you should start learning after HTML.
*   While HTML is used to define the structure and semantics of your content, CSS is used to style it and lay it out.

![](images/css-1.png)

How to link CSS?
================

External Link
-------------

The `<link>` HTML element specifies relationships between the current document and an external resource. This element is most commonly used to link to stylesheets, but is also used to establish site icons (both "favicon" style icons and icons for the home screen and apps on mobile devices) among other things.

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <!-- External CSS -->
    <link rel="stylesheet" href="css/style.css">
</head>
<body>
    <!-- html code -->
</body>
</html>
```

Internal Link
-------------

The `<style>` HTML element contains style information for a document, or part of a document. It contains CSS, which is applied to the contents of the document containing the `<style>` element.
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <!-- Internal CSS -->
    <style>
        /* css styles */
    </style>
</head>
<body>
    <!-- html code -->
</body>
</html>
```

Inline Attribute
----------------

The `style` attribute allows to style an element using CSS declarations. It functions identically to the style attribute in HTML.
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <!-- External CSS -->
    <link rel="stylesheet" href="css/style.css">
</head>
<body>
    <!-- Inline CSS -->
    <h1 style="color:white; background-color: brown">Cascading Style Sheet</h1>
</body>
</html>
```

CSS Selector
============

In CSS, selectors are used to target the HTML elements on our web pages that we want to style. There are a wide variety of CSS selectors available, allowing for fine-grained precision when selecting elements to style. In this article and its sub-articles we'll run through the different types in great detail, seeing how they work.

1.  universal selector
```css
* {
    /* code here */
}
```
2.  type selector (or) element selector
```css
h1 {
    /* code here */
}
```
3.  class selector
```css
.heading {
    /* code here */
}
```
5.  id selector
```css
#title {
    /* code here */
}
```
6.  attribute selector
```css
label[for="name"] {
    /* code here */
}
```
7.  grouping selector
```css
h1, #title, .para {
    /* code here */
}
```
8.  descendant combinator
```css
.box .title {
    /* code here */
}
```
9.  child combinator
```css
#main>.title {
    /* code here */
}
```
10. adjacent sibling combinator(+)
```css
h1+p {
    /* code here */
}
```
11.  general sibling combinator(~)
```css
p~span {
    /* code here */
}
```

Pseudo Class
============

A pseudo-class is a selector that selects elements that are in a specific state, e.g. they are the first element of their type, or they are being hovered over by the mouse pointer. They tend to act as if you had applied a class to some part of your document, often helping you cut down on excess classes in your markup, and giving you more flexible, maintainable code.

| Pseudo Class   | Explanation                                                                                                                                                                               |
| -------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| :active        | commonly used on `<a>` and `<btton>` elements.                                                                                                                                            |
| :checked       | represents any radio(`<input type=”radio”>`), checkbox (`<input type=”checkbox”>`),or option (`<option>`) element that is checked or toggled to an on state.                              |
| :hover         | triggered when the user hovers over an element with the cursor (mouse pointer).                                                                                                           |
| :focus         | represents an element (such as a form input) that has received focus.                                                                                                                     |
| :first-child   | represents the first element among a group of sibling elements.                                                                                                                           |
| :last-child    | represents the last element among a group of sibling elements.                                                                                                                            |
| :nth-child     | matches elements based on their position among a group of siblings.                                                                                                                       |
| :nth-of-type() | matches elements based on their position among siblings of the same type (tag name).                                                                                                      |
| :visited       | applies once the link has been visited by the user.applies only `<a>` and `<area>` elements that have an href attribute.                                                                  |
| :root          | matches the root element of a tree representing the document.In HTML, :root represents the `<html>` element and is identical to the selector html, except that its specificity is higher. |

Pseudo Element
==============

A CSS pseudo-element is a keyword added to a selector that lets you style a specific part of the selected element(s).

Ref: [More Info at developer.mozilla.org](https://developer.mozilla.org/en-US/docs/Web/CSS/Pseudo-elements)

| Pseudo Element | Explanation                                                                                                                                                                          |
| -------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| ::first-letter | applies styles to the first letter of the first line of a block level element but only when not preceded by other content (such as images or inline tables).                         |
| ::first-line   | applies styles to the first line of a block level element                                                                                                                            |
| ::before       | creates a pseudo-element that is the first child of the selected element. It is often used to add cosmetic content to an element with the content property. It is inline by default. |
| ::after        | creates a pseudo-element that is the last child of the selected element.It is often used to add cosmetic content to an element with the content property. It is inline by default.   |
| ::placeholder  | represents the placeholder text in an `<input>` or `<textarea>` element.                                                                                                             |
| ::selection    | applies styles to the part of a document that has been highlighted by the user.                                                                                                      |

# CSS values and units

| units | Description                                                                                                              |
| ----- | ------------------------------------------------------------------------------------------------------------------------ |
| px    | absolute length units — they are not relative to anything else, and are generally considered to always be the same size. |
| em    |                                                                                                                          |Font size of the parent, in the case of typographical properties like font-size, and font size of the element itself, in the case of other properties like width.
| rem   | relative to the size of root element.                                                                                    |
| vw    | 1% of the viewport's width.                                                                                              |
| vh    | 1% of the viewport's height.                                                                                             |
| %     | it will be a percentage of the font-size of the element's parent                                                         |

## color

*   HEX colors(hexadecimal notation, the hexadecimal ranges are 0-9,A-F)
```css
color: #abc123;
```
*   RGB(Red, Green, Blue)
```css
color: rgb(112, 255, 100);
```
```css
color: rgb(99, 50, 250, 0.7);
```
*   HSL(Hue, Saturation, Lightness, hue ranges are 0-360deg, Saturation ranges are 0-100%, Lightness ranges are 0-100%)
```css
color: hsl(255, 95%, 59%);
```
*   Color Keywords(148 named colors in CSS, eg: purple, tomato, goldenrod, etc…)
```css
color: red;
```

## border

*   A border provides a frame for your boxes.
*   border-style : (dotted, solid, groove, inset, dashed, double, ridge, outset)
*   to set border style of each side, you can use border-top-style, border-right-style, border-bottom-style, border-left-style
*   you can use border-color property to set the color of the border
*   to set border color of each side, you can use border-top-color, border-right-color, border-bottom-color, border-left-color
*   to set the thickness of border, you can use border-width property
*   to set each side of border-width, you can use border-top-width, border-right-width, border
*   `border` : Shorthand for `border-width`, `border-style`, and `border-color`
```css
border: 1px dashed gray;
```
*   `border-style` : to set the appearance of the border(`dotted`, `solid`, `groove`, `inset`, `dashed`, `double`, `ridge`, `outset`)
```css
border-style: dotted;
```
*   `border-color` : to set the color of the border
```css
border-color: #000;
```
*   `border-width` : to set the thickness of the border
```css
border-width: 3px;
```
*   `border-radius` : to set the rounded corners of the border
```css
border-radius: 10px;
``` 

## outline

*   Outline is a line outside of the element's border. Unlike other areas of the box, outlines don't take up space, so they don't affect the layout of the document in any way.
*   `outline`: shorthand for `outline-color`, `outline-style`, `outline-width`
```css
outline-style: double;
```
```css
outline-color: #0a0;
```
```css
outline-width: 1px;
```
```css
outline: 1px double #a0a;
```

## width

*   The width CSS property sets an element's width.
*   By default, it sets the width of the content area, but if box-sizing is set to border-box, it sets the width of the border area.

## max-width

*   The max-width CSS property sets the maximum width of an element.
*   It prevents the used value of the width property from becoming larger than the value specified by max-width.

## min-width

*   The min-width CSS property sets the minimum width of an element.
*   It prevents the used value of the width property from becoming smaller than the value specified for min-width.

## height

*   The height CSS property specifies the height of an element.
*   By default, the property defines the height of the content area. If box-sizing is set to border-box, however, it instead determines the height of the border area.

## max-height

*   The max-height CSS property sets the maximum height of an element.
*   It prevents the used value of the height property from becoming larger than the value specified for max-height.

## min-height

*   The min-height CSS property sets the minimum height of an element.
*   It prevents the used value of the height property from becoming smaller than the value specified for min-height.

## text-align

*   The text-align CSS property sets the horizontal alignment of the inline-level content inside a block element or table-cell box.
*   This means it works like vertical-align but in the horizontal direction.

## text-align-last

*   The text-align-last CSS property sets how the last line of a block or a line, right before a forced line break, is aligned.

## text-decoration

*   The text-decoration shorthand CSS property sets the appearance of decorative lines on text.
*   It is a shorthand for text-decoration-line, text-decoration-color, text-decoration-style, and the newer text-decoration-thickness property.

## text-decoration-color

*   The text-decoration-color CSS property sets the color of decorations added to text by text-decoration-line.
*   The color applies to decorations, such as underlines, overlines, strikethroughs, and wavy lines like those used to mark misspellings, in the scope of the property's value.

## text-decoration-line

*   The text-decoration-line CSS property sets the kind of decoration that is used on text in an element, such as an underline or overline.

## text-decoration-style

*   The text-decoration-style CSS property sets the style of the lines specified by text-decoration-line. The style applies to all lines that are set with text-decoration-line.

## text-decoration-thickness

*   The text-decoration-thickness CSS property sets the stroke thickness of the decoration line that is used on text in an element, such as a line-through, underline, or overline.

## text-indent

*   The text-indent CSS property sets the length of empty space (indentation) that is put before lines of text in a block.

## text-shadow

*   The text-shadow CSS property adds shadows to text.
*   It accepts a comma-separated list of shadows to be applied to the text and any of its decorations.
*   Each shadow is described by some combination of X and Y offsets from the element, blur radius, and color.

## text-transform

*   The text-transform CSS property specifies how to capitalize an element's text.
*   It can be used to make text appear in all-uppercase or all-lowercase, or with each word capitalized. It also can help improve legibility for ruby.

## letter-spacing

*   The letter-spacing CSS property sets the horizontal spacing behavior between text characters.
*   This value is added to the natural spacing between characters while rendering the text.
*   Positive values of letter-spacing causes characters to spread farther apart, while negative values of letter-spacing bring characters closer together.

## word-spacing

*   The word-spacing CSS property sets the length of space between words and between tags.

## cursor

*   The cursor CSS property sets the mouse cursor, if any, to show when the mouse pointer is over an element.
*   The cursor setting should inform users of the mouse operations that can be performed at the current location, including: text selection, activating help or context menus, copying content, resizing tables, and so on.
*   You can specify either the type of cursor using a keyword, or load a specific icon to use (with optional fallback images and mandatory keyword as a final fallback).

## list-style

*   The list-style CSS shorthand property allows you to set all the list style properties at once.
*   formal syntax is list-style: `<list-style-position>` `<list-style-image>` `<list-style-type>`

## list-style-position

*   The list-style-position CSS property sets the position of the: marker relative to a list item.

## list-style-image

*   The list-style-image CSS property sets an image to be used as the list item marker.

## list-style-type

*   The list-style-type CSS property sets the marker (such as a disc, character, or custom counter style) of a list item element.

## background

*   The background shorthand CSS property sets all background style properties at once, such as color, image, origin and size, or repeat method.
*   Component properties not set in the background shorthand property value declaration are set to their default values.
*   formal syntax is background:

## background-attachment

*   The background-attachment CSS property sets whether a background image's position is fixed within the viewport, or scrolls with its containing block.

## background-blend-mode

*   The background-blend-mode CSS property sets how an element's background images should blend with each other and with the element's background color.

## background-clip

*   The background-clip CSS property sets whether an element's background extends underneath its border box, padding box, or content box.

## background-color

*   The background-color CSS property sets the background color of an element.

## background-image

*   The background-image CSS property sets one or more background images on an element.

## background-position

*   The background-position CSS property sets the initial position for each background image. The position is relative to the position layer set by background-origin.

## background-repeat

*   The background-repeat CSS property sets how background images are repeated. A background image can be repeated along the horizontal and vertical axes, or not repeated at all.

## background-size

*   The background-size CSS property sets the size of the element's background image. The image can be left to its natural size, stretched, or constrained to fit the available space.

## font

*   The font CSS shorthand property sets all the different properties of an element's font.
*   Alternatively, it sets an element's font to a system font.

## font-family

*   The font-family CSS property specifies a prioritized list of one or more font family names and/or generic family names for the selected element.

## font-size

*   The font-size CSS property sets the size of the font. Changing the font size also updates the sizes of the font size-relative `<length>` units, such as em, ex, and so forth.

## font-style

*   The font-style CSS property sets whether a font should be styled with a normal, italic, or oblique face from its font-family.

## font-weight

*   The font-weight CSS property sets the weight (or boldness) of the font. The weights available depend on the font-family that is currently set.

## padding

*   The padding CSS shorthand property sets the padding area on all four sides of an element at once.

## margin

*   The margin CSS shorthand property sets the margin area on all four sides of an element.

## box-sizing

*   The box-sizing CSS property sets how the total width and height of an element is calculated.

## box-model

*   Everything in CSS has a box around it, and understanding these boxes is key to being able to create more complex layouts with CSS, or to align items with other items. In this lesson, we will take a look at the CSS Box Model. You'll get an understanding of how it works and the terminology that relates to it.

## opacity

*   The opacity CSS property sets the opacity of an element. Opacity is the degree to which content behind an element is hidden, and is the opposite of transparency.

## transform

*   The transform CSS property lets you rotate, scale, skew, or translate an element. It modifies the coordinate space of the CSS visual formatting model.

## transition

*   The transition CSS property is a shorthand property for transition-property, transition-duration, transition-timing-function, and transition-delay.

## float

*   The float property is used for positioning and formatting content e.g., let an image float left to the text in a container.

position

========
*   The position CSS property sets how an element is positioned in a document. The top, right, bottom, and left properties determine the final location of positioned elements.
*   A positioned element is an element whose computed position value is either relative, absolute, fixed, or sticky. (In other words, it's anything except static.)
*   A relatively positioned element is an element whose computed position value is relative. The top and bottom properties specify the vertical offset from its normal position; the left and right properties specify the horizontal offset.
*   An absolutely positioned element is an element whose computed position value is absolute or fixed. The top, right, bottom, and left properties specify offsets from the edges of the element's containing block. (The containing block is the ancestor relative to which the element is positioned.) If the element has margins, they are added to the offset. The element establishes a new block formatting context (BFC) for its contents.
*   A stickily positioned element is an element whose computed position value is sticky. It's treated as relatively positioned until its containing block crosses a specified threshold (such as setting top to value other than auto) within its flow root (or the container it scrolls within), at which point it is treated as "stuck" until meeting the opposite edge of its containing block.

## z-index

*   The z-index CSS property sets the z-order of a positioned element and its descendants or flex items. Overlapping elements with a larger z-index cover those with a smaller one.

## animation

*   CSS animations make it possible to animate transitions from one CSS style configuration to another.
*   Animations consist of two components, a style describing the CSS animation and a set of keyframes that indicate the start and end states of the animation's style, as well as possible intermediate waypoints.

## animation-composition

*   Specifies the composite operation to use when multiple animations affect the same property simultaneously. This property is not part of the animation shorthand property.

## animation-delay

*   Specifies the delay between an element loading and the start of an animation sequence and whether the animation should start immediately from its beginning or partway through the animation.

## animation-direction

*   Specifies whether an animation's first iteration should be forward or backward and whether subsequent iterations should alternate direction on each run through the sequence or reset to the start point and repeat.

## animation-duration

*   Specifies the length of time in which an animation completes one cycle.

## animation-fill-mode

*   Specifies how an animation applies styles to its target before and after it runs.

## animation-iteration-count

*   Specifies the number of times an animation should repeat.

## animation-name

*   Specifies the name of the @keyframes at-rule describing an animation's keyframes.

## animation-play-state

*   Specifies whether to pause or play an animation sequence.

## animation-timing-function

*   Specifies how an animation transitions through keyframes by establishing acceleration curves.

## display

*   The display CSS property sets whether an element is treated as a block or inline element and the layout used for its children, such as flow layout, grid or flex.
*   Formally, the display property sets an element's inner and outer display types. The outer type sets an element's participation in flow layout; the inner type sets the layout of children. Some values of display are fully defined in their own individual specifications; for example, the detail of what happens when display: flex is declared is defined in the CSS Flexible Box Model specification.
*   can set values to block, inline-block, none, flex, grid.

## flex

*   The flex CSS shorthand property sets how a flex item will grow or shrink to fit the space available in its flex container.

## flex-basis

*   The flex-basis CSS property sets the initial main size of a flex item. It sets the size of the content box unless otherwise set with box-sizing.

## flex-direction

*   The flex-direction CSS property sets how flex items are placed in the flex container defining the main axis and the direction (normal or reversed).

## flex-flow

*   The flex-flow CSS shorthand property specifies the direction of a flex container, as well as its wrapping behavior.
*   formal syntax is flex-flow: `<flex-direction>` `<flex-wrap>`

## flex-grow

*   The flex-grow CSS property sets the flex grow factor, which specifies how much of the flex container's remaining space should be assigned to the flex item's main size.

## flex-shrink

*   The flex-shrink CSS property sets the flex shrink factor of a flex item. If the size of all flex items is larger than the flex container, items shrink to fit according to flex-shrink.
*   In use, flex-shrink is used alongside the other flex properties flex-grow and flex-basis, and normally defined using the flex shorthand.

## flex-wrap

*   The flex-wrap CSS property sets whether flex items are forced onto one line or can wrap onto multiple lines. If wrapping is allowed, it sets the direction that lines are stacked.

## justify-content

*   The CSS justify-content property defines how the browser distributes space between and around content items along the main-axis of a flex container, and the inline axis of a grid container.

## justify-items

*   The CSS justify-items property defines the default justify-self for all items of the box, giving them all a default way of justifying each box along the appropriate axis.

## justify-self

*   The CSS justify-self property sets the way a box is justified inside its alignment container along the appropriate axis.

## align-items

*   The CSS align-items property sets the align-self value on all direct children as a group. In Flexbox, it controls the alignment of items on the Cross Axis. In Grid Layout, it controls the alignment of items on the Block Axis within their grid area.

## align-content

*   The CSS align-content property sets the distribution of space between and around content items along a flexbox's cross-axis or a grid's block axis.

## align-self

*   The align-self CSS property overrides a grid or flex item's align-items value. In Grid, it aligns the item inside the grid area. In Flexbox, it aligns the item on the cross axis.

## grid

*   The grid CSS property is a shorthand property that sets all of the explicit and implicit grid properties in a single declaration. Using grid, you specify one axis using grid-template-rows or grid-template-columns.

## grid-template-rows

*   The grid-template-rows CSS property defines the line names and track sizing functions of the grid rows.

## grid-template-columns

*   The grid-template-columns CSS property defines the line names and track sizing functions of the grid columns.

## grid-template

*   The grid-template CSS property is a shorthand property for defining grid columns, grid rows, and grid areas.

## Responsive Web Design

*   Responsive web design (RWD) is a web design approach to make web pages render well on all screen sizes and resolutions while ensuring good usability. It is the way to design for a multi-device web. In this article, we'll help you understand some techniques that can be used to master it.

## Media Queries

*   Media queries allow us to run a series of tests (e.g., whether the user's screen is greater than a certain width, or a certain resolution) and apply CSS selectively to style the page appropriately for the user's needs.

## The viewport meta tag

*   If you look at the HTML source of a responsive page, you will usually see the following `<meta>` tag in the `<head>` of the document.
*   `<meta name="viewport" content="width=device-width, initial-scale=1" />`
*   This viewport meta tag tells mobile browsers that they should set the width of the viewport to the device width, and scale the document to 100% of its intended size.

*   What is JavaScript
==================

*   JavaScript is a programming language initially designed to interact with elements of web pages. In web browsers, JavaScript consists of three main parts:
*   ECMAScript provides the core functionality.
*   The Document Object Model (DOM) provides interfaces for interacting with elements on web pages
*   The Browser Object Model (BOM) provides the browser API for interacting with the web browser.

Operator
========

Arithmetic Operator
-------------------
| operator | name           | example             | output |
| :------- | :------------- | :------------------ | :----- |
| +        | addition       | 3 + 2               | 3      |
| \-       | substraction   | 3 - 2               | 1      |
| \*       | multiplication | 3 * 2               | 6      |
| /        | division       | 3 / 2               | 1.5    |
| %        | modulus        | 3 % 2               | 1      |
| ++       | increment      | let a = 3 <br> a ++ | 4      |
| \--      | decrement      | let a = 3 <br> a -- | 2      |

Comparison Operator
-------------------
| operator | name                  | example   | output |
| :------- | :-------------------- | :-------- | :----- |
| \==      | equal                 | 3 == '3'  | true   |
| \===     | identical             | 3 === '3' | false  |
| !=       | not equal             | 3 != 5    | true   |
| \>       | greater than          | 5 > 3     | true   |
| <        | less than             | 7 < 10    | true   |
| \>=      | greater than or equal | 5 >= 5    | true   |
| <=       | less than or equal    | 8 <= 6    | false  |

logical operator
----------------
| operator | name | example           | output |
| :------- | :--- | :---------------- | :----- |
| &&       | and  | 3 > 1 && 1 <= 5   | true   |
| \|\|     | or   | 3 > 1 \|\| 1 >= 5 | false  |
| !        | not  | ! 3 > 1           | false  |

Assignment Operator
-------------------
| operator | description               | example |
| :------- | :------------------------ | :------ |
| \=       | assignment                | a = 1   |
| +=       | add and assign            | a += 2  |
| \-=      | substract and assign      | a -= 2  |
| \*=      | multiplication and assign | a *= 3  |
| /=       | divide and assign         | a /= 2  |
| %=       | modulus and assign        | a %= 3  |

conditional operator
--------------------
| operator | description | example                              |
| :------- | :---------- | :----------------------------------- |
| ? :      | conditional | (condition) ? (if true) : (if false) |

Control Flow
============

*   The if statement executes block if a condition is true.
```javascript
if(condition) {
    // statements to execute
}
```
*   if...else statement to execute a block if a condition is true and another block otherwise.
```javascript
if(condition) {
    // statements to execute
} else {
    // statements to execute
}
```
*   if...else...if statement is to check multiple conditions and execute the corresponding block if a condition is true.
```javascript
if(condition 1) {
    // statements to execute
} else if (condition 2) {
    // statements to execute
} else if (condition 2) {
    // statements to execute
} else {
    // statements to execute
}
```
*   you can use a ternary operator instead of the if-else statement.
```javascript
    condition ? expressionIfTrue : expressionIfFalse`
```
*   The switch statement evaluates an expression, compares its result with case values, and executes the statement associated with the matching case value.
```javascript
switch(expression) {
    case 1:
        // statement here;
        break;
    case 2:
        // statement here;
        break;
    case 3:
        // statement here;
        break;
    default:
        // statement here;
}
```
*   The JavaScript while statement creates a loop that executes a block as long as a condition evaluates to true.
```javascript
while(expression) {
    // statement;
}
```
*   The do...while loop statement creates a loop that executes a block until a condition evaluates to false.
```javascript
do {
    // statement;
} while(expression)
```
*   The for loop statement creates a loop with three optional expressions.
```javascript
for(initializer; condition; iterator) {
    // statement here;
}
```
*   The break statement prematurely terminates a loop such as for, do...while, and while loop, a switch, or a label statement.
*   The continue statement terminates the execution of the statement in the current iteration of a loop such as a for, while, and do…while loop and immediately continues to the next iteration.

Function
========

*   To avoid repeating the same code all over places, you can use a function to wrap that code and reuse it.
*   JavaScript provides many built-in functions
*   To declare a function, you use the function keyword, followed by the function name, a list of parameters, and the function body.
```javascript
function functionName(parameters) {
    // code
}
```
*   To use a function, you need to call it.
*   Calling a function is also known as invoking a function.
*   To call a function, you use its name followed by arguments enclosing in parentheses.
```javascript
functionName(arguments);
```
*   The terms parameters and arguments are often used interchangeably. However, they are essentially different.
*   When declaring a function, you specify the parameters. However, when calling a function, you pass the arguments that are corresponding to the parameters.
*   For example, in the say() function, the message is the parameter and the 'Hello' string is an argument that corresponds to the message parameter.
*   To specify a return value for a function, you use the return statement followed by an expression or a value.

anonymous function
------------------

*   An anonymous function is a function without a name.
*   Note that if you don't place the anonymous function inside the (), you'll get a syntax error. The () makes the anonymous function an expression that returns a function object.
```javascript
(function(){
    // ...                                             
})
```
*   An anonymous function is not accessible after its initial creation. Therefore, you often need to assign it to a variable.
```javascript
let show = function() {                                                 
    console.log('anonymous function');                                             
}                                             
show();
```
*   The anonymous function has no name between the function keyword and parentheses ().
*   Because we need to call the anonymous function later, we assign the anonymous function to the show variable.
*   Since the whole assignment of the anonymous function to the show variable makes a valid expression, you don't need to wrap the anonymous function inside the parentheses ().

arrow function
--------------

*   ES6 arrow functions provide you with an alternative way to write a shorter syntax compared to the function expression.
```javascript
let add = (x,y) => x+y;
console.log(add(3,4)); // 7
```
Variables
=========

*   A variable is a label that references a value like a number or string. Before using a variable, you need to declare it.
*   declare a variable: To declare a variable, you use the var keyword followed by the variable name as follows: `var temp;`
*   Initialize a variable: To initialize a variable, you specify the variable name, followed by an equal sign (=) and a value: `var temp = 100;`
*   Change a variable: Once you initialize a variable, you can change its value by assigning a different value. For example: `var temp = 150;`
*   `var` and `let` create variables that can be reassigned another value.
*   `const` creates "constant" variables that cannot be reassigned another value.
*   An undefined variable is a variable that has been declared but not initialized while an undeclared variable is variable that has not been declared.
*   Use the const keyword to define a readonly reference to a value.
*   A constant holds a value that doesn't change.
*   To declare a constant, you use the const keyword. When defining a constant, you need to initialize it with a value. For example: `const number = 10;`

Data Types
==========

JavaScript is a dynamically typed language. It means that a variable doesn't associate with a type. In other words, a variable can hold a value of different types. For example:

primitive data types:
---------------------

*   [number](#number)
*   [boolean](#boolean)
*   undefined
*   null
*   [string](#string)

complex data types:
-------------------

*   [object](#objects)

Number
======

*   JavaScript uses the number type to represent both integers and floating-point values.
*   Technically, the JavaScript number type uses the IEEE-754 format.
*   decimal integer: let number = 100; // 100
*   octal numbers: let number = 071 // 57
*   hexadecimal number: let number = 0X1a; // 26
*   floating numbers: let number = 0.99 // 0.99
*   big number: let number = 3.14e7; // 31400000
*   small number: let number = 5e-7; // 0.0000005
*   big integer: JavaScript introduced the bigint type starting in ES2022. The bigint type stores whole numbers whose values are greater than 253 - 1.
*   A big integer literal has the n character at the end of an integer literal like this:
*   big integer: let views = 9007199254740991n;
*   you can declare a variable that holds number as follows:
*   let number = new Number(100);
*   let number = 200
*   number properties:
*   MAX\_VALUE : Number.MAX\_VALUE // 1.7976931348623157e+308
*   MIN\_VALUE: Number.MIN\_VALUE //5e-324
*   Number.POSITIVE\_INFINITY // Infinity
*   Number.NEGATIVE\_INFINITY // -Infinity
*   number methods:
*   toExponential()
*   toFixed()
*   toLocaleString()
*   toPrecision()
*   toString()
*   valueOf()
*   Number Properties Cannot be Used on Variables
*   Number properties belong to the JavaScript Number Object.
*   These properties can only be accessed as Number.MAX_VALUE.
*   Using x.MAX_VALUE, where x is a variable or a value, will return undefined:
*   numeric separator: The numeric separator allows you to create a visual separation between groups of digits by using underscores (\_) as separators.
*   const amount = 1\_000\_000\_000;
*   JavaScript allows you to use numeric separators for both integer and floating-point numbers.
*   Use underscores (\_) as the numeric separators to create a visual separation between groups of digits.

[number properties & methods](pages/04_js-number.md)   

Boolean
=======

*   **Boolean primitive type:** JavaScript provides a Boolean primitive type that has two values of true and false.
*   **Boolean object:** In addition to the boolean primitive type, JavaScript also provides you with the global Boolean() function, with the letter B in uppercase, to cast a value of another type to boolean.
```javascript
let a = Boolean('Hi');
console.log(a); //true
console.log(typeof(a)); // boolean
```
*   The Boolean is also a wrapper object of the Boolean primitive type. It means that when you pass either true or false to the Boolean constructor, it'll create a Boolean object.
*   To get the primitive value back, you call the valueOf() method of the Boolean object.
```javascript
let b = new Boolean(false);
console.log(b.valueOf()); //false
```
[boolean properties & methods](pages/04_js-boolean.md)

String
======

*   Syntax : `var val = new String(string);`
*   JavaScript strings are primitive values. Also, strings are immutable. It means that if you modify a string, you will always get a new string. The original string doesn't change.
*   To create literal strings, you use either single quotes (') or double quotes (") like this:
```javascript
let str = "Hi";
let greeting = "Hello";
```
*   ES6 introduced template literals that allow you to define a string backtick (\`) characters:
```javascript
let name = `John`;
```
*   The template literals allow you to use the single quotes and double quotes inside a string without the need of escaping them.
```javascript
let message = `"I'm good". She said"`;
```
*   Also, you can place the variables and expressions inside a template literal. JavaScript will replace the variables with their value in the string. This is called string interpolation. For example:
```javascript
let name = 'John';
let message = `Hi, I'm ${name}`;
console.log(message); // Hi, I'm John
```
*   Escaping special characters: To escape special characters, you use the backslash `\` character. For example:
*   Windows line break: `'\r\n'`
*   Unix line break: `'\n'`
*   Tab: `'\t'`
*   Backslash `'\'`
*   Concatenating strings via `"+"` operator: To concatenate two or more strings,you use the `+` operator:
```javascript
let name = "John";
let str = 'Hello' + name;
console.log(str); // "Hello John"
```
*   If you want to assemble a string piece by piece, you can use the `+=` operator:
```javascript
let className = 'btn';
className += ' btn-primary';
className += ' none';
console.log(className); // btn btn-primary none
```
*   Comparing strings : To compare two strings, you use comparison operators such as `>`, `>=`, `<`, `<=`, and `==` operators.
*   The comparison operators compare strings based on the numeric values of the characters. And it may return the string order that is different from the one used in dictionaries.
```javascript
let result = 'a' < 'b';
console.log(result); // true
let result = 'a' < 'B';
console.log(result); // false
``` 
[string properties & methods](pages/04_js-string.md)

Objects
=======

*   JavaScript is an Object Oriented Programming (OOP) language. A programming language can be called object-oriented if it provides four basic capabilities to developers -
*   **Encapsulation** - the capability to store related information, whether data or methods, together in an object.
*   **Aggregation** - the capability to store one object inside another object.
*   **Inheritance** - the capability of a class to rely upon another class (or number of classes) for some of its properties and methods.
*   **Polymorphism** - the capability to write one function or method that works in a variety of different ways.
*   Objects are composed of attributes. If an attribute contains a function, it is considered to be a method of the object, otherwise the attribute is considered a property.

Object Properties
-----------------

*   Object properties can be any of the three primitive data types, or any of the abstract data types, such as another object.
*   Object properties are usually variables that are used internally in the object's methods, but can also be globally visible variables that are used throughout the page.
*   In JavaScript, an object is an unordered collection of key-value pairs. Each key-value pair is called a property.
*   The key of a property can be a string. And the value of a property can be any value, e.g., a string, a number, an array, and even a function.

Object Methods
--------------

*   Methods are the functions that let the object do something or let something be done to it.
*   There is a small difference between a function and a method - at a function is a standalone unit of statements and a method is attached to an object and can be referenced by this keyword.
*   Methods are useful for everything from displaying the contents of the object to the screen to performing complex mathematical operations on a group of local properties and parameters.

how to create an object
-----------------------

*   syntax
```javascript
let book = new Object();
```
*   JavaScript provides you with many ways to create an object. The most commonly used one is to use the object literal notation.
```javascript
let empty = {};
``` 
*   To create an object with properties, you use the key:value within the curly braces.
*   The person object has two properties firstName and lastName with the corresponding values 'John' and 'Doe'.
*   When an object has multiple properties, you use a comma (,).
```javascript
let person = {
    firstName: "John",
    lastName: "Doe",
}
```

Accessing properties
--------------------

*   To access a property of an object, you use one of two notations: the dot notation and array-like notation.
*   The dot notation( . )
```javascript
// objectName.propertyName
console.log(person.firstName);
console.log(person.lastName);
```
*   Array-like notation(\[\])
```javascript
// objectName['propertyName']
console.log(person['firstName']);
console.log(person['lastName']);
```
*   When a property name contains spaces, you need to place it inside quotes. For example, the following address object has the 'building no' as a property:
*   To access the 'building no' property, you need to use the array-like notation:
*   If you use the dot notation, you'll get an error:
*   Note that it is not a good practice to use spaces in the property names of an object.
```javascript
let address = {
    'buliding no' : 3960,
    street: 'North 1st stree',
    state: 'CA',
    country: 'USA'
}
console.log(address['building no']);
```
Modifying the value of a property
---------------------------------

*   To change the value of a property, you use the assignment operator (=).
*   we changed the value of the firstName property of the person object from 'John' to 'Jane'.
```javascript
let person = {
    firstName: 'John',
    lastName:'Doe'
};
person.firstName ='Jane';
console.log(person): // {firstName: 'Jane', lastName: 'Doe'}
```
Adding a new property to an object
----------------------------------

*   Unlike objects in other programming languages such as Java and C#, you can add a property to an object after object creation.
*   The following statement adds the age property to the person object and assigns 25 to it:
```javascript
person.age = 25;
```
Deleting a property of an object
--------------------------------

*   To delete a property of an object, you use the delete operator:
*   If you attempt to reaccess the age property, you'll get an undefined value.
```javascript
//delete objectName.propertyName;
delete person.age;
```
Checking if a property exists
-----------------------------

*   To check if a property exists in an object, you use the in operator:
*   The in operator returns true if the propertyName exists in the objectName.
```javascript
let employee = {
    firstName: 'Peter',
    lastName: 'Doe',
    employeeId:1
};
console.log('ssn' in employee); //false
console.log('emplyeeId' in employee); //true
```
Summary
-------

*   An object is a collection of key-value pairs.
*   Use the dot notation ( . ) or array-like notation (\[ \]) to access a property of an object.
*   The delete operator removes a property from an object.
*   The in operator check if a property exists in an object.

Arrays
======

*   First, an array can hold values of mixed types. For example, you can have an array that stores elements with the types number, string, boolean, and null.
*   Second, the size of an array is dynamic and auto-growing. In other words, you don't need to specify the array size up front.
*   In JavaScript, an array is an ordered list of values. Each value is called an element specified by an index:
*   An array can hold values of mixed types.
*   JavaScript arrays are dynamic, which means that they grow or shrink as needed.

Creating JavaScript arrays
--------------------------

*   JavaScript provides you with two ways to create an array.
*   The first one is to use the Array constructor as follows:
*   let scores = new Array(9,10,8,7,6);
*   The more preferred way to create an array is to use the array literal notation:
*   let arrayName = \[element1, element2, element3, ...\];
*   The array literal form uses the square brackets \[\] to wrap a comma-separated list of elements.

Accessing JavaScript array elements
-----------------------------------

*   JavaScript arrays are zero-based indexed. In other words, the first element of an array starts at index 0, the second element starts at index 1, and so on.
*   To access an element in an array, you specify an index in the square brackets \[\]:

Array properties
----------------

*   To access an element in an array, you specify an index in the square brackets \[\]: arrayName\[index\]
*   To change the value of an element, you assign that value to the element like this:
```javascript
let mountains = ['Everest', 'Fuji', 'Nanga Parbat'];
mountains[2] = 'K2';
console.log(mountains); //['Everest', 'Fuji', 'K2'];
```
*   Getting the array size : Typically, the length property of an array returns the number of elements. The following example shows how to use the length property:
```javascript
console.log(mountains.length); //3
```

Array Destructuring
-------------------

*   Prior to ES6, there was no direct way to assign the elements of the returned array to multiple variables.
*   The variables x, y and z will take the values of the first, second, and third elements of the returned array.
*   Note that the square brackets \[\] look like the array syntax but they are not.
```javascript
let [x,y,z] = [70, 80, 90];
console.log(x); // 70
console.log(y); // 80
console.log(z); // 90
```
Spread Operator
---------------

*   ES6 provides a new operator called spread operator that consists of three dots (...). The spread operator allows you to spread out elements of an iterable object such as an array, map, or set.
```javascript
const odd = [1, 3, 5];
const combined = [...odd, 2, 4, 6];
console.log(combined); // [1, 3, 5, 2, 4, 6];
```

[array properties & methods](pages/04_js-array.md)

Document Object Model
=====================

*   The Document Object Model (DOM) is an application programming interface (API) for manipulating HTML documents.
*   The DOM represents an HTML document as a tree of nodes. The DOM provides functions that allow you to add, remove, and modify parts of the document effectively.
*   Note that the DOM is cross-platform and language-independent ways of manipulating HTML and XML documents.

Selecting Elements
------------------

*   select element by Id : `document.getElementById()`
*   select elements by name : `getElementsByName()`
*   select elements by tag name : `getElementsByTagName()`
*   select elements by class name : `getElementsByClassName()`
*   select elements by css selectors : `querySelector()querySelectorAll()`

Travesing Elements
------------------

*   parent element : The `node.parentNode` returns the read-only parent node of a specified node or null if it does not exist. `node.parentNode`
*   sibling element : To get the next sibling of an element, you use the `nextElementSibling` attribute.
*   To get the previous siblings of an element, you use the `previousElementSibling` attribute.
*   To get the first child element of a specified element, you use the `firstChild` property of the element.
*   to get the first child with the Element node only, you can use the `firstElementChild` property:
*   To get the last child element of a node, you use the `lastChild` property:
*   If you want to select only the last child element with the element node type, you use the `lastElementChild` property:
*   To get a live NodeList of child elements of a specified element, you use the `childNodes` property:
*   The `childNodes` property returns all child elements with any node type. To get the child element with only the element node type, you use the children property:

Manipulating Elements
---------------------

*   The `document.createElement()` accepts an HTML tag name and returns a new Node with the Element type.
*   The `appendChild()` method allows you to add a node to the end of the list of child nodes of a specified parent node.
*   To get the text content of a node and its descendants, you use the `textContent` property.
*   The `innerText` takes the CSS style into account and returns only human-readable text.
*   you can also use the `textContent` property to set the text for a node.
*   The `innerHTML` is a property of the Element that allows you to get or set the HTML markup contained within the element.
*   The `element.before()` method allows you to insert one or more nodes before the element.
*   The `element.after()` method allows you to insert one or more nodes after the element.
*   The `parentNode.append()` method inserts a set of Node objects or DOMString objects after the last child of a parent node.
*   The `prepend()` method inserts a set of Node objects or DOMString objects before the first child of a parent node,
*   To replace an HTML element, you use the `node.replaceChild()` method.
*   The `cloneNode()` is a method of the Node interface that allows you to clone an element:
*   To remove a child element of a node, you use the `removeChild()` method.
*   To insert a node before another node as a child node of a parent node, you use the `parentNode.insertBefore()` method.

Events
------

*   mousedown
*   mouseup
*   click
*   dblclick
*   mousemove
*   mouseover
*   mouseout
*   mouseenter
*   mouseleave
*   keydown
*   keyup
*   keypress
*   focus
*   submit
*   blur
*   change
*   etc…

Browser Object Model
====================

The Browser Object Model (BOM) is the core of JavaScript on the web. The BOM provides you with objects that expose the web browser's functionality.

window
------

The global object of JavaScript in the web browser is the window object. It means that all variables and functions declared globally with the var keyword become the properties and methods of the window object.

*   `window.innerWidth`
*   `window.innerHeight`
*   `window.location`
*   `window.location.href`
*   `window.location.href`
*   `window.location.search`
*   `window.open()`
*   `window.resizeTo()`
*   `window.resizeBy()`
*   `window.moveTo(x,y)`
*   `window.close()`
*   `window.alert()`
*   `window.confirm()`
*   `window.prompt()`
*   `window.setTimeout()`
*   `window.setInterval()`

navigator
---------

The JavaScript Navigator provides information about the web browser and its capabilities. You can reference the Navigator object via the read-only window.navigator property.

*   `navigator.appCodeName`
*   `navigator.appName`
*   `navigator.appVersion`
*   `navigator.battery`
*   `navigator.cookieEnabled`
*   `navigator.geolocation`
*   `navigator.userAgent`
