## libxmlrpc-net
This library is forked from https://www.xml-rpc.net/, v2.5.0 Release.

Copyright (C) 2001-2010 Charles Cook (chascook@gmail.com)

The source code can be download from https://code.google.com/archive/p/xmlrpcnet/downloads. Here is the download link of the source ball:
https://storage.googleapis.com/google-code-archive-downloads/v2/code.google.com/xmlrpcnet/xml-rpc.net.2.5.0.zip

XML-RPC.NET is licensed with MIT X11 license.
(see http://www.xml-rpc.net/faq/xmlrpcnetfaq-2-5-0.html#6.12)

The original xml-rpc.net library has been out of maintenance for a while and it can only run on .Net 2.0. It cannot run on .Net Standard 2.0 and UWP environment.

The major changes:
- Remove the codes related to the http server and client
- Remove the codes related to compact .net framework
- Remove the codes to generate proxy classes
- Migrate some deprecated APIs to the new versions
- Rename the namespace to HelpLightning.XmlRpc
- Upgrade the visual studio project to be a C# library of .Net Standard 2.0
- Support IEnumerable and IDictionary

