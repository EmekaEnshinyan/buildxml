
# Xml & Terminal Parameters Builder

[![](https://img.shields.io/badge/license-Apache-blue.svg?)](https://github.com/remkop/picocli/blob/master/LICENSE)

*Questions?  Comments?  Feedback? Email me at emeka.enshinyan@gmail.com 

-----

Fundamental function: write data to a file, and place the data in a built .xml all of which will be run on a terminal.

This application takes in data from two sources: a source .xml file saved on the local disk and target data from an API call. There are four pieces of data that is stored in a .txt file: 1. an array of sentences from the source .xml file that will be in some language L, 2. an array of the source sentences but modified as a property value to build an API URL for each sentence, 3. the language code for the source language to be used in the API call, 4. the language code for the target language to be used in the API call.  

The program is run by using the terminal with self-made parameters and inputting the following: the directory of the source .xml, the language url parameters to be inserted for the API call, and the output path for the newly built .xml file (the target file) with the data inserted in the required places in the target file.

---This application uses the DOM XML parser, Maven Compiler, and PicoCli for creating custom commands---

Dom Parsing Documentation: https://docs.oracle.com/javase/tutorial/jaxp/dom/readingXML.html

PicoCli: https://picocli.info/

# Table of contents
1. [Requirements](#requirement)
2. [Setup](#Setup)
3. [Running-In-Terminal](#Running In Terminal)

## Requirements
**NOTE** This has not been tested on a Mac or Linux OS.
The computer specification requirements are negligable, meaning you can run this program on almost any local or remote machine with minimal drive space and CPU speed.

###### The following tools are required to to have the application serve its function:
- Java 15 (can also be run on Java 8)
- Apache-Maven version 15
- PicoCli version 4.6.3
- Internet connection for the API calls
- A .txt file
## Setup

paper documents

## Runnin In Terminal

to determine where you would like the .txt data to be written on your disk, you can go to TxtFile.java and set the return statement 
