# Blazor File upload UPDATE to 5.0

I have taken my original file upload sample project(https://github.com/CodingWithDavid/BlazorFileUploadSample) and updated the code to use the new 5.0 upload component.


by [David Gallivan](http://twitter.com/CodingwithDavid)


## Why

The original file upload had to use javascript InterOp to do the file upload.  With .Net 5.0 there is a new Blazor component for file uploads.  I wanted to see what the differences were between the 2.  And there is a lot.

## Getting Started

1. Clone this repository

   ```Command Line
   git clone https://github.com/CodingWithDavid/FileUploadUpdate5.0
   cd FileUploadUpdate5.0
   ```

1.	Open in Visual Studio or Visual Code
a.	With Visual Code you will need to install the C# extensions
b.  With Visual Code you will need to install the Blazor extensions
2.	Press F5

## What's in the App

The first page are instructions on what the application does.  
The second page is the actual file upload
1. Select a file to upload
2. If the file is less than 512000 it will be uploaded to wwwroot/uploads
    a. If it is a text document, the contents will be displayed
    b. If it is an image, the image will be displayed
3. If the file size is greater than 512000, a message will be displayed.



## Problems or Suggestions

[Open an issue here]( https://github.com/CodingWithDavid/FileUploadUpdate5.0/issues)

## Thank You


## Resources

- [VS Code](https://code.visualstudio.com)
- [Visual Studio]( https://visualstudio.microsoft.com/)



