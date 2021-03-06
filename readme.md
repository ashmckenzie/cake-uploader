# Uploader v2.6.1 #

A CakePHP plugin that will upload multiple types of files. Adds support for file validation and attachments within the model layer. Also has minor support for Amazon S3.

### Not Backwards Compatible ###

Version(s) 2.5.1 and above are not backwards compatible with 2.5.0 and below.
Check the commit log for changes and please update your code accordingly!

## Requirements ##

* CakePHP 1.2.x., 1.3.x
* PHP 5.2.x, 5.3.x
* ClamAV module (for virus detection)

## Features ##

* Automatically sets all ini settings required for file uploading
* Support for a wide range of mime types: text, images, archives, audio, video, application
* Logs all internal errors that can be retrieved and displayed
* Saves a log for all uploads happening during the current request
* Automatically validates against the default mime types and internal errors
* Can scan the uploaded files for viruses using the ClamAV module
* Files can be uploaded anywhere within the webroot folder
* Convenience methods for deleting a file, moving/renaming a file and getting the file extension or dimensions
* Built in methods for resizing images and generating thumbnails
* Custom Behavior to add validation rules to your Models validation set
* Custom Behavior that allows models to attach files to automatically upload the file and save its information to a database
* Component to support the Amazon S3 system, allowing you to transfer your files to the bucket
* S3 Transfer functionality is also inherited into the Attachment Behavior

## Documentation ##

Thorough documentation can be found here: http://milesj.me/resources/script/uploader-plugin

## Installation ##

Clone the repo into a folder called "uploader" within your plugins directory.
