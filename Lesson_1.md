# Introduction to HTML
## 1.0 - What is HTML?
HTML, or Hypertext Markup Language is a _markup language_, which means that it simply has the ability to define _elements_ within a document.  While HTML has many applications, it is most known for being the primary markup language of the Internet, a vast collection of interlinked documents written not only with HTML but also PHP, XML, and the like.  

There are several core components that define HTML.
- **Tags**: tags make up the structure of HTML.  They are made up of the less than (`<`) and greater than (`>`) symbols, and often forward slashes (`/`).  
- **Opening Tags**: opening tags begin a section of an HTML document.  One of the first opening tags you'll learn to use is `<h1>`, which defines the start of a header section in a document.  
- **Closing Tags**: closing tags end a section of an HTML document.  Not every element has a closing tags, but about 90 percent (including `<h1>`) do.  They look identical to opening tags, except right after the less than sign there is a forward slash (`/`), for example the closing tag to `<h1>` is `</h1>`.  

## 1.1 - Where to Write HTML
HTML is fairly easy to get started with, as you don't need any complicated or pricey programs to write it.  Many people begin writing HTML in a default program installed on their computer, such as Windows Notepad.  You can use the Ideoxan Web IDE.  

Let's begin by creating a file.  Use the plus button to create a new file in the Ideoxan Web IDE and call it `index.html`.  While you can technically call it anything you want, naming your main HTML file `index` is a common practice among web developers.  

The IDE will automatically open the file.  Now you can start writing your first web page!

## 1.2 - Getting Started
As was mentioned earlier, HTML is not the only language on the Internet, so we need to tell the _web browser_ what language we're writing in.  A web browser is a program on your computer such as Google Chrome, Brave, Microsoft Edge, Firefox, or Opera that has the ability to read and display different markup languages.  To tell the browser that we want to write HTML, we type the following tag: 
```html
<!DOCTYPE html>
```
This syntax (or way of writing a programming language) is a little wacky, but it's probably the weirdest you'll experience in this course.  The closing tag to end an HTML document is simply `</html>`.

When we write HTML, we generally go ahead and close the tag before we start writing more code inside the tag.  So let's go ahead and do that: 
```html
<!DOCTYPE html>

</html>
```

Now if we visit our file in a web browser, we will see a plain white screen.  It might not seem very exciting, but you have just written your first HTML website!

## 1.3 - Adding Content
You definitely want to add content of some kind to your website.  After all, no one wants to just stare at a plain white screen!  But before we can start adding text and images to an HTML document, we have to tell the web browser where to read that content from.  Why can't we just put it inside of the `<!DOCTYPE html>` and `</html>` tags?  Well, because a website is more than just what's visible.  If you continue learning with Ideoxan, then you'll discover that you can add invisible things such as _stylesheets_, _scripts_, _meta tags_, and more.  Right now, we'll ignore those and begin creating visible content.  

To tell the browser where content begins, we add an opening and closing `<body>` tag under the HTML declaration like so:
```html
<!DOCTYPE html>
    <body>
    </body>
</html>
```
You might notice something a little funky: the `<body>` tags are _indented_, or spaced out from the left of the editor.  The Ideoxan Web IDE will automatically format your code like this, as it has become a standard convention for web developers.  

Now it's time to make something visible!  Let's make a header using an `h` tag.  `h` tags (header tags) are sorted by importance using the numbers 1 to 6.  For example, `<h1>` is the largest and boldest heading while `<h6>` is the smallest.  Let's add the most important heading to our `<body>`:
```html
<!DOCTYPE html>
    <body>
        <h1></h1>
    </body>
</html>
```
As you see, we indented the header tags even further.  But wait- where are we going to put our content?  Well, content goes in between the `<h1> ` tags: 
```html
<!DOCTYPE html>
    <body>
        <h1>Hello, world!</h1>
    </body>
</html>
```
Now our website will say in a nice, bold, 90s-esque serifed font: 
![Hello world!](https://github.com/micahlt/curriculum-introduction-to-html/blob/master/assets/hello.png)
<!--stackedit_data:
eyJoaXN0b3J5IjpbMjQyNTMwNTQwLDEyNDgxOTQyNjMsMTUzMT
AzMDUxNF19
-->