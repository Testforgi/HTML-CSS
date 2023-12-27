# [Guvi Zen](https://www.guvi.io/zen/)

## HTML Task to know usage of basic tags.

1. Fix the bugs in below snippet

```HTML
    <html lang="en">
    <head>
        <title>Document
            <body>
             <h1>guvi<h1>
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
2. Try the below one

```HTML
<html lang="en">
    <head>
        <title>Document<title>
</head>
  <body>
              <h1>  guvi<h1>

    <div>
        Lorem ipsum dolor sit amet consectetur adipisicing elit.
        <div>
            <div>
                Guvi Geek Network
            </div>
        </body>
    </html>
```

---

3. Design a contact us form with all fields as required.
<div class="container">
  <form action="action_page.php">

    <label for="fname">First Name</label>
    <input type="text" id="fname" name="firstname" placeholder="Your name..">

    <label for="lname">Last Name</label>
    <input type="text" id="lname" name="lastname" placeholder="Your last name..">

    <label for="country">Country</label>
    <select id="country" name="country">
      <option value="australia">Australia</option>
      <option value="canada">Canada</option>
      <option value="usa">USA</option>
    </select>

    <label for="subject">Subject</label>
    <textarea id="subject" name="subject" placeholder="Write something.." style="height:200px"></textarea>

    <input type="submit" value="Submit">

  </form>
</div>
---

4. Use certain HTML elements to display the following in a HTML page.

- Programming Language
  - JavaScript
    1. Angular
    2. React
    3. Vue.js

---

5. Create an element that helps you to open the https://google.com in separate new tab.

 an anchor ( <a> ) element 

6. In the form, add two radio buttons with grouping them for employee type(Salaried and own business)

--- <label for="employee_type">Employee Type :</label>
            <input type="radio" name="sal">Salaried</input>
            <input type="radio" name="self">Self employed</input>
</div>
</form>

7. Design form shown in the link (http://evc-cit.info/cit040/formguide/card_0.png)

---<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="form.css">
    <title>Document</title>
</head>
<body>
    <div class="container">
    <form action="https:\\google.com" method="GET">
        <p>Yes! I want to subscribe to  <i>Mag-O-Zine</i></p>
        <div id="l1">
            <input type="text" placeholder="First name"/>
            <input type="text" placeholder="last name"/>
        </div>
        <div id="l2">
            <input type="text" placeholder="Address"/>
        </div>
        <div id="l3">
            <input type="text" placeholder="City"/>
            <input type="text" placeholder="State"/>
            <input type="number" placeholder="Zip"/>
        </div>
        <div id="l4">
            <label for="subscription">Subscribe for :</label>
            <input type="checkbox"/>1 year($19.95) 
            <input type="checkbox"/>2 years($35.00)
        </div>
        <div id="l5">
            Send me more information about:
            <br>
            <input type="checkbox"/>Computer-Zine 
            <br>
            <input type="checkbox"/>Fishing-Zine 
            <br>
            <input type="checkbox"/>Cat-O-Zine   
        </div>
    </form>
    </div> 
</body>
</html>
 body{
    background-color: black;
    color: black;
}
.container{
    border: 2px solid rgb(252, 239, 239);
    margin: 300px auto;    
    max-width: max-content;
    display: flex;
    flex-direction: row;
    justify-items: center;
    
}
div, div > input{
    padding: 0.5rem;
}

p{
    background-color: red;
    color: rgb(248, 244, 244);
    font-family: cursive;
    margin: auto;
    padding: 0.5rem;
    display: flex;
    justify-content: center;
}
form{
    background-color: rgb(248, 244, 244);
}

.l1{
    min-width: 50%;
}
.l2{
    min-width: 100%;
}


8. Use the table tag to design given image [Click here](https://www.bapugraphics.com/assets/img/port_upload_dir/table-4.jpg).
html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
    td, th{
        min-width: 115px;
    }
    </style>
    <title>Tables</title>
</head>
<body>
    <table border="5" bordercolor="green">
        <tr>
            <th>State of Health</th>
            <th colspan="2">Fasting Value
                <table>
                    <tr>
                        <th colspan="1">Minimum</th>
                        <th colspan="1">Maximum</th>
                    </tr>
                </table>    
            </th>
            <th colspan="1">After eating
                <table>
                    <tr>
                        <td>2 hours after eating</td>
                    </tr>
                </table>
            </th>
        </tr>
        <tr>
            <td>Healthy</td>
            <td>70</td>
            <td>100</td>
            <td>Less than 140</td>
        </tr>
        <tr>
            <td>Pre-Diabetes</td>
            <td>101</td>
            <td>126</td>
            <td>140 to 200</td>
        </tr>
        <tr>
            <td>Diabetes</td>
            <td>More than 126</td>
            <td>N/A</td>
            <td>More than 200</td>
        </tr>    
    </table>
</body>
</html>

---

9. Write HTML input tags snippet to show default values for all Form elements.
<body>
    <form action="https:\\google.com" method="GET">
        <label for="first_name">First Name : </label>
        <input type="text" placeholder="First Name" value="first"/>
        <br>
        <label for="last_name">Last Name : </label>
        <input type="text" placeholder="Last Name" value="last"/>
        <br>
        <label for="DOB">DOB : </label>
        <input type="date" placeholder="Date of birth" value="01/01/2999"/>
        <br>
        <label for="Address">Address : </label>
        <textarea cols="30" rows="5" name="address_details" placeholder="Enter your full address here"></textarea>
        <button name="submit">Submit the form</button>
        <br>
        <div>
            <label for="employee_type">Employee Type :</label>
            <input type="radio" name="sal">Salaried</input>
            <input type="radio" name="self">Self employed</input>
        </div>
    </form>
</body>
---

10. In your, HTML page add the below line and Highlight it without using any CSS.

- "HTML & CSS is awesome"

---<div>
    <mark>HTML & CSS is awesome</mark>
 </div>

11. Create an HTML page, which should contain all types of input elements.

 <div>
        <ul>Types of Inputs
            <li><input type="button" value="button"/></li>
            <li>Checkbox<input type="checkbox" value=""/></li>
            <li>Color<input type="color"/></li>
            <li>Date<input type="date"/></li>
            <li>datetime<input type="datetime"/></li>
            <li>datetime-local<input type="datetime-local"/></li>
            <li>email<input type="email"/></li>
            <li>file<input type="file"/></li>
            <li>image<input type="image"/></li>
            <li>hidden<input type="hidden"/></li>
            <li>month<input type="month"/></li>
            <li>password<input type="password"/></li>
            <li>radio:<input type="radio"/></li>
            <li>reset<input type="reset"/></li>
            <li>range<input type="range"/></li>
            <li>search<input type="search"/></li>
            <li>text<input type="text"/></li>
            <li>url<input type="url"/></li>
            <li>week<input type="week"/></li>
            <li>tel<input type="tel"/></li>
        </ul>
    </div>
   
