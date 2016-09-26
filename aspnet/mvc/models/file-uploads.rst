:version: 1.0.0

File Uploads
============
By `Steve Smith`_

Files can be uploaded to ASP.NET Core MVC apps using several techniques.

.. contents:: Sections
	:local:
	:depth: 1
	
`View or download sample from GitHub <https://github.com/aspnet/Docs/tree/master/aspnet/mvc/models/file-uploads/sample>`_

How to upload simple files
--------------------------

Files can be uploaded from HTML forms using simple markup like the following:

example

Uploaded files can be buffered in memory and processed all at once, or streamed and processed in chunks. The former approach is much simpler and is recommended for small and/or infrequent uploads.

Handling file uploads with IFormFile
------------------------------------

content

Handling file uploads with streaming
------------------------------------

content