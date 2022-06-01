# ErayPDF
This project is an attempt to provide an alternative way to convert plain HTML files to PDF without relying on anything that utilizes QT Webkit (looking at you, WK).
<hr>

### F.A.Q

<hr>

#### Is the project production-ready?
No. Conversion process is too hard-coded and inflexible to be used in a production project unless the requirement is generating a PDF with A4 page dimensions. Won't take long before it gets ready for general use cases, however.

#### Does this converter support latest HTML5/CSS3 features?
Yes.
#### What is the caveat?
a Chromium binary MUST be added from https://chromium.woolyss.com/ to the root path or printing won't work! Couldn't get it into project as it'd turn the repo to LFS, sorry.
<hr>

#### Usage Example
```
var result = HtmlToPdfConverter.ConvertAndSavePDF(filePath); // Returns generated pdf's path.
```
