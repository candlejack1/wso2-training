
# What is an API?

  

## API definition

  

**API** stands for Application Programming Interface and describes how to interact with a program.

  

This can be seen as some form of contract that specifies that if you provide a program with certain inputs it will provide the relevant output as a response.

  

A program that is exposed via an API can be called by other programs on the same network. For example if you have a batch job running in your environment where **Program A** needs some data from **Program B**.

  

If the API for **Program B** is exposed over the internet it will allow users and other systems to gain access to the data it provides.

For example if a user installs and uses a app on their mobile phone and this app needs to access **Program B** to get some data.

![What is an API Diagram](https://github.com/candlejack1/wso2-training/blob/master/api_manager/introduction/diagrams/1_api_introduction_api_overview.png?raw=true  "API overview")

  

From the above examples we can see that API's have the following 3 important characteristics:


 - Standard web protocols
 - Well defined interfaces
 - Network accessible

  

## Different types of API's
In this section we will cover in high level detail the different types of API's you are likely to encounter.

In each of these sections you will find a link that provides a more in depth look at each API.
  

### Simple Object Access **Protocol** (SOAP)
SOAP was created by Microsoft as a way of sending XML data over Http in a structured way.

SOAP specifies a structured way of sending XML data between two points. 
A SOAP message consist of the following elements :
* Envelope  - This identifies the XML document as a SOAP message.
* Header - Contains authentication details and can also define complex data types used by the message body.
* Body - Specifies the format of the request and response messages.
*  Fault - This is an optional element and is a child of the body element. This element describes the fault messages of the service.

![What is an API Diagram](https://github.com/candlejack1/wso2-training/blob/master/api_manager/introduction/diagrams/1_api_introduction_soap_elements.png?raw=true
  "SOAP Elements")

### RESTFUL APIs

### Websocket APIs

### GraphQL APIs

  