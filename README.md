# NBMFS

##1. Demo of Application

![alt text](https://github.com/venetsia/NBMFS/blob/master/NBMFSapp.gif)

##2. Report for Coursework 

https://github.com/venetsia/NBMFS/blob/master/40313507Report.pdf

##3. Overview

The main purose of the program is to accept messages (SMS/Tweet/Email(Standard/Incident Report)) by manual input or by file input. 
File input: There are two choices:
  - TXT file (input/output)
  - JSON file (input/output)
 Manual Input: There are two choices:
  - Input box for each entry with smart helpers detecting what kind of message are you about to input and give a hint 
  - Two input message boxes accepting the Incident Number and Message Body. Clicking Process shows how the message is recognised by the software and if any issues the user can fix them before adding it to the lists or just add it without Processing the message to view it beforehand.
    *Message Body Consists of: Sender, Subject (If Email) and Message*
 
 Message accepted by manual input or file input recognizes if there ar eany abbreviations (that are previously loaded into program with Short and Long word) and replaces them. Messages are recognised as type and inserted into lists (in ViewLists). 
 Messages are able to be viewed by category or all in one and since it only shows the most important information for each categoty selecting a message and clicking the View Button opens another Window where you can view the whole message with its full information. 

##4. Instructions

In order to launch the application, the whole code needs to be downloaded and the version of .Net Standard Framework must be  4.7.2 at least -> found in https://dotnet.microsoft.com/download/visual-studio-sdks?utm_source=getdotnetsdk&utm_medium=referral

##5. Programming Overview

Object-Oriented Programming was used to create this program. It is in 3 Layers. -> View more in report



