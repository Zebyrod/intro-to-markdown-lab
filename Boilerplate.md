# Writing an HTML Boilerplate
![HTML Boilerplate](https://images.unsplash.com/photo-1517180102446-f3ece451e9d8?q=80&w=2070&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D)

An **HTML Boilerplate** is an essential in all index.html files. This will contain the entire HTML document as well as all important *meta* data which will not show up the user end. 

## 1. !DOCTYPE

```HTML 
<!DOCTYPE HTML>
```
**All** HTML documents must start with this declaration. This declares that the file being read is going to be an **HTML5** file. It is not a *tag*, rather it is giving the browser information about what to expect with this data.

## 2. The Head 

```HTML
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
```
The head element is a container for *metadata* and it is placed between the html tag and the body tag. *Metadata* is data about the HTML document and it is not displayed. *Metadata* typically defines the character set, language in use, and the title of the document. The *title* tag is **required** in every HTML document. 

## 3. The body

```HTML
<body>
    <h1>This is a heading</h1>
    <p>This is a paragraph</p>
</body>
</html>
```

The *body* element is where the information of the document resides. Within the body will contain all of the contents of the HTML document. This will include all other elements such as headings, paragraphs, lists, links, textboxes etc. 

> Important note: There can only be one *html*, *head*, and *body* element within an HTML document. 

The ***HTML Boilerplate*** will be essential for every HTML document you see. For more information on HMTL, take a look at the [MDN docs](https://developer.mozilla.org/en-US/docs/Web/HTML) or [W3 Schools](https://www.w3schools.com/html/default.asp)!