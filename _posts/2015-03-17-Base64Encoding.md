---
layout: post
title: Encoding demystified
---

Base64 encoding is being used in lot of places these days. For eg. AWS services expects you to send data in Base64 encoding. So what is Base64 encoding and when should we use it?

Base-64 encoding is a way of taking binary data and turning it into text so that it's more easily transmitted in things like e-mail and HTML form data.

But then whyn't use ASCII?
ASCII is a 7bit encoding scheme.It has numbers, alphabets, control and punctuation symbol. But the problem is that there are different interpretations of ASCII characters in different computers. For eg. new line can be encoded in different ways. Also, computers uses 8bit to store data in bytes so some systems may wipe the most significant bit.

Base64 was introduced to send data safely without getting corrupted. The disadvantage is that encoding the message using Base64 increases its length - every 3 bytes of data is encoded to 4 ASCII characters.

Base64 isn't a encryption mechanism.

http://stackoverflow.com/questions/3538021/why-do-we-use-base64 


