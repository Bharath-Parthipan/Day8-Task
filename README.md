# Day8-Task

1. Fix the bugs in below snippet

```HTML
    <html lang="en">
    <head>
        <title>Document
            <body>
                guvi
        </title>
    </head>
    <div>
        Lorem ipsum dolor sit amet consectetur adipisicing elit.
        <div>
            <div>
                Guvi Geek Network
            </div>
        </body>
    </html>
```
correct HTML code :

```HTML
    <!DOCTYPE html>
    <html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Document</title>
    </head>
    <body>
        <div>
            Lorem ipsum dolor sit amet consectetur adipisicing elit.
            <div>
                <div>
                    Guvi Geek Network
                </div>
            </div>
        </div>
    </body>
    </html>
```
what I fixed :
> 1. Moved the `<body>` tag outside the `<head>` tag. The `<body>` tag should be directly under the `<html>` tag.
> 2. Closed the `<div>` tag properly that wraps the content "Lorem ipsum dolor sit amet consectetur adipisicing elit."
> 3. Added `<meta charset="UTF-8">` and `<meta name="viewport" content="width=device-width, initial-scale=1.0">` in the `<head>` section for better compatibility and responsiveness.
> 4. Closed the `<title>` tag properly.

---

2. Try the below one

```HTML
<html lang="en">
    <head>
        <title>Document
            <body>
                guvi
    </head>
    <div>
        Lorem ipsum dolor sit amet consectetur adipisicing elit.
        <div>
            <div>
                Guvi Geek Network
            </div>
        </body>
    </html>
```
correct HTML code :

```HTML
    <!DOCTYPE html>
    <html lang="en">
    <head>
        <title>Document</title>
    </head>
    <body>
        guvi
        <div>
            Lorem ipsum dolor sit amet consectetur adipisicing elit.
            <div>
                <div>
                    Guvi Geek Network
                </div>
            </div>
        </div>
    </body>
    </html>
```

What I fixed :

> 1. Moved the `<body>` tag outside the `<head>` tag. The `<body>` tag should be directly under the `<html>` tag.
> 2. Closed the `<title>` tag properly.
> 3. Moved the text "guvi" inside the `<body>` tag for proper placement within the HTML structure.
> 4. Added a proper doctype declaration `<!DOCTYPE html>` at the beginning to specify the HTML version.

---

3. Design a contact us form with all fields as required.<br>
Task Complited ["click to View"](http://127.0.0.1:5500/ContactUs.html)

---

4. Use certain HTML elements to display the following in a HTML page.

- Programming Language
  - JavaScript
    1. Angular
    2. React
    3. Vue.js
  - Python
    1. Django Framework
    2. Flask Framework
  - Java
    1. Spring
    2. Maven
    3. Hibernate
- Database
  - MySQL
  - MongoDB
  - Cansandra

---

5. Create an element that helps you to open the https://google.com in separate new tab.

---

6. In the form, add two radio buttons with grouping them for employee type(Salaried and own business)

---

7. Design form shown in the link (http://evc-cit.info/cit040/formguide/card_0.png)

---

8. Use the table tag to design given image [Click here](https://www.bapugraphics.com/assets/img/port_upload_dir/table-4.jpg).

---

9. Write HTML input tags snippet to show default values for all Form elements.

---

10. In your, HTML page add the below line and Highlight it without using any CSS.

- "HTML & CSS is awesome"

---

11. Create an HTML page, which should contain all types of input elements.