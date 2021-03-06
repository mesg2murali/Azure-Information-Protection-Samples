# RPMSG  viewer code sample

This sample project is not a compilable project that one can just download and use.
All the code samples are written in C# using Xamarin Libraries (especially iOS and Android)
The purpose of this code is show users how to encrypt and decrypt RPMSG objects. 
RPMSG is the way Azure Information Protection encrypts protected email messages.
The code snippets shared in this directory highlight the RPMSG handler capabilities

## Directory Structure 
The directories of importance are the 
+ Common Code for RPMSG Viewer 
+ Android RPMSG handler sample
+ iOS RPMSG handler sample

The sample shows how to decrypt and RPMSG files. The RPMSG Handler class on Windows is done by the Outlook Client. RPMSG is not an Azure Information Protection format but a format supported by Outlook. As in the begining this code is there to just show how a RPMSG message object can be decrypted and encrypted

### Important Files 
Within the Common directory there is the Lib directory within which you will find the directory called Message.rpmsg
Inside the Message.rpmsg directory the files that important are:
- MessageRpmsg.cs
- RpmsgAttachments.cs 

The Common Code directory has an RpmsgHanlder.cs file, **Please ignore this file**
The RpmsgHandler.cs file you need to look at are in the Android and iOS directories. 

Looking forward to getting your feedback on this sample guidance code
