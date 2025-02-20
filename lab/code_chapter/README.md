


# Practical Node-RED Programming

**Learn powerful visual programming techniques and best practices for the web and IoT**

## What is this course material about?
Node-RED is a free and open-source flow-based programming tool used for handling IoT data that allows programmers of any level to interconnect physical I/O, cloud-based systems, databases, and APIs for building web applications without coding.

This guide covers the following exciting features: 
* Understand the history of Node-RED and why you need to learn a flow-based programming tool
* Use Node-RED for building Node.js-based applications
* Handle data for IoT devices using Node-RED flows
* Explore advanced Node-RED features such as connecting repositories and customizing the flow editor
* Find out what the MQTT protocol is and how it relates to Node-RED

## Instructions and Navigations
All of the code is organized into folders. For example, Chapter04.

The code will look like the following:
```
// generate random number
var min = 1 ;
var max = 10 ;
var a = Math.floor( Math.random() * (max + 1 - min) ) + min ;
// set random number to message
msg.payload = a;
// return message
return msg;

```

**Following is what you need for this guide:**
This Node-RED book is for web developers, IoT engineers, and enthusiasts with some background in JavaScript and Node.js. Although not necessary, familiarity with electronics will help you to make the most out of this book.

With the following software and hardware list you can run all code files present in the book (Chapter 1-13).

### Software and Hardware List

| Chapter  | Software required                   | OS required                        |
| -------- | ------------------------------------| -----------------------------------|
| 1-13        | Node-RED 1.2                        | Windows, Mac OS X, and Raspberry Pi OS |
| 1-13       | Node.js 12                          | Windows, Mac OS X, and Raspberry Pi OS |
| 1-13       | npm 6                               | Windows, Mac OS X, and Raspberry Pi OS |

