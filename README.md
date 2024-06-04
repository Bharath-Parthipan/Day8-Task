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

HTML code :
```HTML
    <!DOCTYPE html>
    <html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Programming Languages and Databases</title>
    </head>
    <body>
        <h2>Programming Languages</h2>
        <ul>
            <li>JavaScript
                <ol>
                    <li>Angular</li>
                    <li>React</li>
                    <li>Vue.js</li>
                </ol>
            </li>
            <li>Python
                <ol>
                    <li>Django Framework</li>
                    <li>Flask Framework</li>
                </ol>
            </li>
            <li>Java
                <ol>
                    <li>Spring</li>
                    <li>Maven</li>
                    <li>Hibernate</li>
                </ol>
            </li>
        </ul>
    
        <h2>Databases</h2>
        <ul>
            <li>MySQL</li>
            <li>MongoDB</li>
            <li>Cassandra</li>
        </ul>
    </body>
    </html>
```

This HTML structure creates lists for both programming languages and databases, with sub-lists for specific frameworks/languages under each main category.

---

5. Create an element that helps you to open the https://google.com in separate new tab.

code : 

```HTML
    <a href="https://google.com" target="_blank">Click to View</a>
```

---

6. In the form, add two radio buttons with grouping them for employee type(Salaried and own business)

code :

```HTML
    <!DOCTYPE html>
    <html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>FSD Day8-Task</title>
    </head>
    <body>
        <h2>Employee Type Form</h2>
        <form>
            <p>Please select your employee type:</p>
            <input type="radio" id="salaried" name="employeeType" value="Salaried">
            <label for="salaried">Salaried</label>
            <input type="radio" id="ownBusiness" name="employeeType" value="Own Business">
            <label for="ownBusiness">Own Business</label>
            <input type="submit" value="Submit">
        </form>
    </body>
    </html>
```

---

7. Design form shown in the link (http://evc-cit.info/cit040/formguide/card_0.png)

---

8. Use the table tag to design given image [Click here](https://www.bapugraphics.com/assets/img/port_upload_dir/table-4.jpg).

---

9. Write HTML input tags snippet to show default values for all Form elements.

code : 

```HTML
    <!DOCTYPE html>
    <html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Form Elements with Default Values</title>
    </head>
    <body>
        <form>
            <!-- Text input -->
            <label for="text-input">Text:</label>
            <input type="text" id="text-input" name="text-input" value="Default Text"><br><br>
    
            <!-- Password input -->
            <label for="password-input">Password:</label>
            <input type="password" id="password-input" name="password-input" value="defaultpassword"><br><br>
    
            <!-- Email input -->
            <label for="email-input">Email:</label>
            <input type="email" id="email-input" name="email-input" value="default@example.com"><br><br>
    
            <!-- Number input -->
            <label for="number-input">Number:</label>
            <input type="number" id="number-input" name="number-input" value="10"><br><br>
    
            <!-- Date input -->
            <label for="date-input">Date:</label>
            <input type="date" id="date-input" name="date-input" value="2024-06-01"><br><br>
    
            <!-- Radio buttons -->
            <label>Radio:</label>
            <input type="radio" id="radio1" name="radio-group" value="option1" checked>
            <label for="radio1">Option 1</label>
            <input type="radio" id="radio2" name="radio-group" value="option2">
            <label for="radio2">Option 2</label><br><br>
    
            <!-- Checkbox -->
            <label>Checkbox:</label>
            <input type="checkbox" id="checkbox1" name="checkbox-group" value="option1" checked>
            <label for="checkbox1">Option 1</label>
            <input type="checkbox" id="checkbox2" name="checkbox-group" value="option2">
            <label for="checkbox2">Option 2</label><br><br>
    
            <!-- Select dropdown -->
            <label for="select-input">Select:</label>
            <select id="select-input" name="select-input">
                <option value="option1">Option 1</option>
                <option value="option2" selected>Option 2</option>
                <option value="option3">Option 3</option>
            </select><br><br>
    
            <!-- Textarea -->
            <label for="textarea-input">Textarea:</label>
            <textarea id="textarea-input" name="textarea-input">Default text in textarea</textarea><br><br>
    
            <!-- Color input -->
            <label for="color-input">Color:</label>
            <input type="color" id="color-input" name="color-input" value="#ff0000"><br><br>
    
            <!-- Range input -->
            <label for="range-input">Range:</label>
            <input type="range" id="range-input" name="range-input" min="0" max="100" value="50"><br><br>
    
            <!-- File input -->
            <label for="file-input">File:</label>
            <input type="file" id="file-input" name="file-input"><br><br>
    
            <!-- Submit button -->
            <input type="submit" value="Submit">
        </form>
    </body>
    </html>
```
This code includes various types of form elements, each pre-filled with a default value where applicable.

---

10. In your, HTML page add the below line and Highlight it without using any CSS.

- "HTML & CSS is awesome"

code : 

```HTML
    <mark>"HTML & CSS is awesome"</mark>
```

---

11. Create an HTML page, which should contain all types of input elements.