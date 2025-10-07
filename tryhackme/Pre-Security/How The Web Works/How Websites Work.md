# TryHackMe — [Pre Security]

**Date:** 05-10-2025 
**Pathway:** How Websites Work
**Objective:** "By the end of this room, you'll know how websites are created and will be introduced to some basic security issues."

---

## Tasks 
- Task 1 `How websites work`
    Two components make a website
        Front End (Client-Side)
        Back End  (Server-Side)
    Front End is what we see when we travel the internet requesting sites.
    Back End is what makes the website work

- Task 2 `HTML`
    HTML is used to build and define structure
    CSS is used to make websites palatable and nice to look at
    JavaScript is used for complex setting and interactivity
    ```
    HTML is madeup of elements, or tags, and tells browsers how to display content.
        <!DOCTYPE html> defines that the page is a HTML5 document
        <html> element is the root element of the HTML page - all other elements come after this element
        <head> element contains information about the page (such as the page title)
        <body> element defines the HTML document's body; only content inside of the body is shown in the browser.
        <h1> element defines a large heading
        <p> element defines a paragraph
    
    Within TryHackMe, this code was used to show the correcting of file extensions to render an image to reveal the question tags.
```
<!DOCTYPE html>
<html>
<head>
<title>TryHackMe HTML Editor</title>
</head>
<body>
<h1>Cat Website!</h1>
<p>See images of all my cats!</p>
<img src=>
<img src=>
<img src=>
</body>
</html>
```


- Task 3 `JavaScript`
    JavaScript (JS) is one tof the most popular coding languages in the world, allowing webpages to become interactive.
    While HTML is used to create the website structure and content, JS is used to controle the functionality of the webpage.
        JS can be added with either `<script>` or remotely with  with `<script src="/location/of/javascript_file.js"></script>` 

during this was a task to add the line of code in JS to get the flag to answer the questions.

- Task 4 `Sensitive Data Exposure`
    This was a quick task on understanding that the source of the page can hold sensative information. 
    In the fake website provided, it's tought that it is important to remove the username and password from the source code.

- Task 5 `HTML Injection`
    HTML Injection is a vulnerability where unclean user input is displayed on the page. If a website fails to filter malicious text that a user inputs, an attacker can inject HTML code in.
    This will allow a user to display what they want instead of what the website intended on showing.
    By surrounding the website name with HTML code <a href='example'>Link</a> you can creat links to show up on the website.
---

## Results
- There are a lot of simple areas that can cause major issues to a website if not resolved or "cleaned" before publishing.
- It is important to check your code before making it public.