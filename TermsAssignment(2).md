code {
  white-space : pre-wrap !important;
}

# Terms Assignment 

```
10 popular commands - daily use
10 popular network commands
10 popular OS commands
10 popular Git commands
Database
SQL Database
NoSQL Database
10 popular databases
ACID
Aggregations
Joins
CAP Theorem
Normalization
Database Sharding
7 network layers
Request Response Protocol
Web API
REST
HTTP Status Codes to Handle
HTML
Box Model
Margin
Padding
CSS Selectors
CSS Specificity
Flexbox
Grid
Git
HTTP
TCP 
UDP
Web server
Static server
Application server
DNS server
Database Server
Standalone Application
MVC
Operating System
Kernel
Process
Thread
SOLID
Apache Web Server
Nginx Web Server
Messaging Queue
Enterprise Message Bus
RabbitMQ
Kafka
Zookeeper
Service Oriented Architecture
Microservices Architecture
Redis? Why?
Solr? Why?
ElasticSearch? Why?
Celery? Why?
Node JS
MongoDB? Why?
Progressive Web Apps (PWA)
Session Based Authentication
Token Based Authentication
Authorization
Docker
IaaS
AWS
PaaS
Heroku
Hoisting
Pass by Reference/Pass By Value
Closures
Prototypal Inheritance
Mutable Methods in JS
Immutable Methods in JS
React
Why React?
Redux
Why Redux?
State
Props
```

### 10 popular commands - daily use



### Database

```	
A database can be defined as a software used for storing, retrieving, managing data. It helps in keeping the data in an organized fashion.
It helps Organizations in saving time to access and manipulate large amounts of data.
``` 
### SQL Database
```
SQL database means a relational database in which data is manipulated through Structured Query Language. It is a type of Database Management System. RDBMS usually have pre-defined data types. Eg:- MySQL, Postgres 
```
### NoSQL Database
```
No SQl is a non-relational database, it does not follow or needs a structured schema it works on dynamic schema for unstructured data. It is used for distributed data stores. Eg: Redis, Mongo Db, Cassandra
```

### ACID 
```
ACID are some standard properties that help in preventing the DBMS data and transaction from any failures.
ACID stands for Atomicity, Consistency, Isolation, Durability

Atomicity - any transactional process is either fully processed or else aborted, no process is left partially completed.

Consistency - It means all the transactional changes are maintained correctly, so that correct information gets committed into database.
This preserves the consistency in data.

Isolation - All transactional processes are to be handled independently with no interference, this will protect the consistency and will cater to zero possibility of data anomalies. 
 
Durability - It means once all the changes are committed, data is stored and updated. It ensures that there is no such case of data loss even if a system failure occurs.
```

### Aggregations
```
It is a framework of Elastic Search and basically its main purpose is 
to provide an aggregated or summarized result of any search query.
```

### Joins 
```
It's a SQL clause that helps in combining data of two tables based 
on any common column between them. 
Joins help in creating a relationship between two tables. 
There are many types of joins Inner Join, Left Join, Right Join,
Outer Join and cross join.
```
### CAP Theorem 


#### Request Response Protocol
```
It is the Http request made from the client-side to server-side. It helps in communication of devices, basically the client sends a message to server, this is known as request, then the request gets processed and the server returns the appropriate data/message known as response.
```

### Web API
```
Web API are the API services that are provided to the client through HTTP requests, Web API is just a web development concept it is limited to web browser of the client.
Web API's basically use REST and SOAP for interactions.
Eg:- Trello, Twitter provide Web API services so that programmers can access and build remote web applications 
```
 
### REST
```
REST is a an API that is used for creating web services and interact with the server by requests and fetch data, and it uses a set of Operations like GET,PUT,DELETE,POST to make changes in the textual context. Any request made through REST API to any server will return the data in HTML, JSON, text or some other format. 
```

### HTTP status codes
```
Status code 200- OK, this means that the request has been carried out.
Status code 201- Created, this means the POST request is executed and the new data entry has been made.
Status code 400- Bad request, this means that the server was not able to process the request and returns this generic error code, the main cause can be some syntax errors 
Status code 410- Gone, this means that data has been deleted and that particular entry does not exists.
Status code 404- Not Found, this means that request made to server did not match any entry.
```

### HTML
```
HTML is known as Hyper Text Markup Language, it is used for designing the structure of a webpage.
Html helps in displaying the content on a web browser.It uses tags, these tags are not displayed on the web page, only the content inside them is shown.
```
### Box Model
```
The CSS box model is essentially a box that wraps around every HTML element. 
It consists of: margins, borders, padding, and the actual content.
Content - The content of the box, where text and images appear
Padding - Clears an area around the content. The padding is transparent
Border - A border that goes around the padding and content
Margin - Clears an area outside the border. The margin is transparent
```

### Margin
```
margin means the space that gets created outside the css element, its like creating an extra layer of space around the actual borders of the element.It has four properties top, bottom, left, right and they can be given values like auto, %, px,inherit, rem, em.
```
### Padding
```
padding means the space that gets created within the css element's border.It has four properties top, bottom, left, right and they can be given values like auto, %, px,inherit, rem, em.
```
### Css selectors
```
These are the patterns used for accessing the elements of an Html page that have to be styled. Some of the used patterns are, 
.intro 			Selects all elements with class="intro"
#id  			Selects the element with id=""
* 			Selects all elements
element 		Selects all <p> elements
element.class 		Selects all <p> elements with class=""
element,element 	Selects all <div> elements and all <p> elements
element element 	Selects all <p> elements inside <div> elements
element>element 	Selects all <p> elements where the parent is a <div> element
element+element 	Selects all <p> elements that are placed immediately after <div> elements
element1~element2 	Selects every <ul> element that are preceded by a <p> element
::active 	 	Selects the active link
::after 	 	Insert something after the content of each <p> element
::before 	 	Insert something before the content of each <p> element
:hover 			make changes on mouse over over the particular element
```

### Flexbox
```
It is a type of layout. Its like a container and it helps the elements inside it in alignment. It has many properties like flex-direction, flex-flow , flex wrap.
```

### Git
```
It is an open source platform used for the purpose of version control,that is used to store different versions of a file in a remote or local repository. It is used to track changes in the source code. It allows multiple developers to work together. Projects made on git can be made public or private.
```

### Grid
```
It is a type of css layout with rows and columns, it helps in designing the webpages more eaisly as we dont need to take care of positioning.
```

### HTTP
```
It means HyperText Transfer Protocol.It defines how messages are formatted and transmitted, and what actions Web servers and browsers should take in response to various commands.
```

### TCP
```
Transmission Control Protocol is connection oriented protocol that is formed between two application programs to transfer messages. TCP works with IP, the messages are broken into packets and delivered over the network. TCP gives reliability in data. TCP provides extensive error checking mechanisms.It provides flow control and acknowledgment of data.
eg:-World Wide Web(HTTP)
E-mail (SMTP TCP)
File Transfer Protocol (FTP)
```

### UDP
```
Datagram oriented protocol is efficient for broadcast and multicast type of network transmission. Data consistency is not guaranteed in UDP. UDP provides basic error checking mechanism using checksums. 
eg:-Domain Name System (DNS)
Streaming media applications such as movies.
Online multiplayer games.
Voice over IP (VoIP).
```

### Web Server
```
A Web server serves static content to a Web browser by loading a file from a disk and serving it across the network to a user's Web browser. This entire exchange is mediated by the browser and server talking to each other using HTTP.
```
### Static Web server
```
It consists of a computer (hardware) with an HTTP server (software). We call it "static" because the server sends its hosted files "as-is" to your browser.
```

### Application Server
```
Sometimes referred to as a type of middleware, application servers occupy a large chunk of computing territory between database servers and the end user, and they often connect the two.
```

### DNS Server
```
Its like an Internet Protocol address directory, its main function is to translate the named string entered by the user in the url and then return it as Ip address that is understanable by the machines.
eg:-
When you type in a web address, e.g., www.letslearn.com, your Internet Service Provider views the DNS associated with the domain name, translates it into a machine friendly IP address (for example 216.168.224.70 is the IP for letslearn.com) and directs your Internet connection to the correct website. 
```

### Database Server 
```
A database server is a computer system that provides other computers with services related to accessing and retrieving data from a database. Its like to keep a dedicated computer in a network just for the database purposes.Upon requests from the client machines, it searches the database for selected records and passes back the results.
```

### MVC 
```
It stands for Model View Controller, it is basically a way of designing an application,that includes the 
Model (data)- this may be a database file
View (user interface)- this includes the pages through which user will interact with application.
Controller (processes that handle input)- It contains functions that performs changes in database. For example, a controller can update a model by changing the attributes of an element in Web page.
```

### Standalone applications
```
These are the software that are installed on each client system.They are capable of operating independently of any other device or system. For example :- Any code developed in Java can just be tranferred and run on other system.
```
### Operating System
```
It is an interface between a user and computer hardware.It performs all the basic tasks like file management, memory management, process management, handling input and output, and controlling seconary devices.eg:- Windows, Ubuntu.
```
### Kernel
```
It is the central part of an operating system. It manages the operations of the computer and the hardware - most notably memory and CPU time.
It performs tasks, such as running processes, managing hardware devices such as the hard disk, and handling interrupts.
```

### Process
```
In terms of Operating system Process is said to be any program in execution, now this process can be seen as an instance that is being executed through threads.While one process is blocked and waiting, a second process cannot run.In multiple processes each process operates independently of the others.
```

### Thread
```
Thread can be said as the process flow,it keeps track of which instruction to execute next.While one thread is blocked and waiting, a second thread in the same task can run.One thread can read, write or change another thread's data.
```

### Solid
```
It is an acronym that stands for-
    S - Single-responsiblity principle
    O - Open-closed principle
    L - Liskov substitution principle
    I - Interface segregation principle
    D - Dependency Inversion Principle

Single-responsibility principle- It states that a class should have one and only one reason to change, meaning that a class should have only one job.

Open-closed principle- Objects or entities should be open for extension, but closed for modification.

Liskov substitution principle- Objects in a program should be replaceable with instances of their subtypes without altering the correctness of that program.

Interface segregation principle- Many client-specific interfaces are better than one general-purpose interface.It means a client should never be forced to implement an interface that it doesn't use or clients shouldn't be forced to depend on methods they do not use.

Dependency inversion principle- One should depend upon abstractions, [not] concretions.It states that the high level module must not depend on the low level module, but they should depend on abstractions.
```
### Apache Web Server 
```
It is not a physical server, but rather a software that runs on a server. Its job is to establish a connection between a server and the browsers of website visitors (Firefox, Google Chrome, Safari, etc.) while delivering files back and forth between them (client-server structure). Apache is a cross-platform software, therefore it works on both Unix and Windows servers.
```

### NGINX 
```
It is open source software for web serving, reverse proxying, caching, load balancing, media streaming, and more. It started out as a web server designed for maximum performance and stability. In addition to its HTTP server capabilities, NGINX can also function as a proxy server for email (IMAP, POP3, and SMTP) and a reverse proxy and load balancer for HTTP, TCP, and UDP servers.

```

### Message queue 

```
It is kind of storage for message when it doesn't reach its destination. It insert the message in a queue and provide asynchronous communication.
```

### Enterprise Message Bus

```
It is a kind of middleware application used for distributing and communicationg among the components of applications. Though their no standard in this, but it is majorly used by organisation.
```

### Rabbit MQ
```
RabbitMQ is an open source message broker software. It accepts messages from producers, and delivers them to consumers.
```

### Kafka

```
Apache Kafka is an open-source stream-processing software platform developed by LinkedIn and donated to the Apache Software Foundation, written in Scala and Java. The project aims to provide a unified, high-throughput, low-latency platform for handling real-time data feeds.
```

### Zookeeper
```
Apache ZooKeeper is a software project of the Apache Software Foundation. It is essentially a service for distributed systems offering a hierarchical key-value store, which is used to provide a distributed configuration service, synchronization service, and naming registry for large distributed systems.
```

### Service Oriented Architecture
```
Service-oriented architecture is a style of software design where services are provided to the other components by application components, through a communication protocol over a network. The basic principles of service-oriented architecture are independent of vendors, products and technologies.
```

### Microservices Architecture
```
Microservices are a software development technique —a variant of the service-oriented architecture structural style— that arranges an application as a collection of loosely coupled services. In a microservices architecture, services are fine-grained and the protocols are lightweight.
```

### Redis? Why?
```
Redis, an open source, in-memory, data structure server is frequently used as a distributed shared cache (in addition to being used as a message broker or database) because it enables true statelessness for an applications' processes, while reducing duplication of data or requests to external data sources.
```
### Solr? why ?
```
Solr is a popular search platform for Web sites because it can index and search multiple sites and return recommendations for related content based on the search query's taxonomy. Solr is also a popular search platform for enterprise search because it can be used to index and search documents and email attachments.
```

### ElasticSearch? Why?
```
Elasticsearch is a highly scalable open-source full-text search and analytics engine. It allows you to store, search, and analyze big volumes of data quickly and in near real time. It is generally used as the underlying engine/technology that powers applications that have complex search features and requirements.
```

### Celery? Why?
```
Celery is a task queue implementation for Python web applications used to asynchronously execute work outside the HTTP request-response cycle. Celery is an implementation of the task queue concept. Learn more in the web development chapter or view the table of contents for all topics.
```

### NODE JS
```
Node.js is an open-source, cross-platform, JavaScript runtime environment
```

### MongoDB? Why?
```
The motivation of the MongoDB language is to implement a data store that provides high performance, high availability, and automatic scaling. MongoDB is extremely simple to install and implement. MongoDB uses JSON or BSON documents to store data.
```
### Progressive Web Apps (PWA)
```
A Progressive Web App (PWA) is a web app that uses modern web capabilities to deliver an app-like experience to users. These apps meet certain requirements (see below), are deployed to servers, accessible through URLs, and indexed by search engines.
```
### Server Based Authentication 
```
When using a session based auth system, the server creates and stores the session data in the server memory when the user logs in and then stores the session Id in a cookie on the user browser.
```
### Token Based Authentication
```
In the token based authentication, the user data is encrypted into a JWT (JSON Web Token) with a secret and then sent back to the client.
The JWT is then stored on the client side mostly localStorage and sent as a header for every subsequent request. The server receives and validates the JWT before proceeding to send a response to the client.
```
### Authorization

```
Authorization means being allowed access to the system. Authorization verifies your rights to grant you access to resources only after determining your ability to access the system and up to what extent.
```
### Docker
```
Docker is a popular open-source project based on Linux containers. Docker is written in go and developed by Dotcloud (A PaaS Company). Docker is basically a container engine which uses the Linux Kernel features like namespaces and control groups to create containers on top of an operating system and automates application deployment on the container.

It provides a lightweight environment to run your application code. Docker has an efficient workflow for moving your application from developers laptop, test environment to production. It is incredibly fast and it can run on the host with compatible Linux Kernel.
```
###  IaaS
```
Infrastructure as a Service , provides you the computing infrastructure, physical or (quite often) virtual machines and other resources like virtual-machine disk image library, block and file-based storage, firewalls, load balancers, IP addresses, virtual local area networks etc.
```
### AWS
```
Amazon Web Services (AWS) is a secure cloud services platform, offering compute power, database storage, content delivery and other functionality to help businesses scale and grow.
```
### PaaS
```
Platform-as-a-Service (PaaS) model, developers essentially rent everything they need to build an application, relying on a cloud provider for development tools, infrastructure, and operating systems. 
```
### 








