# Advanced HTML5 Elements and Forms

## Objectives
Implement HTML5 images, lists, tables, forms and input types.
Use form validation attributes.
Apply multimedia elements such as audio and video.

## Instructions

- Create an index.html file.
- Add an ordered list with roman numerals
- Add an external image from pexels.com
- Add a table of 5 contacts with; name, address, mobile and emails
- Add a registration form

>[!NOTE]
>  The registration form should have:
>- Name, email, password, and date fields.
>- A dropdown, radio buttons, and checkboxes.
>- Proper labels and placeholders.
>- Required fields and validation attributes.
>- Ensure proper indentation and commenting.
 
# Tasks
- Create a well-structured HTML5 document.
- Ensure semantic correctness.

Happy Coding! 💻✨



<!DOCTYPE html>
<html >
<head>
    <title>assignment</title>
</head>
<body>
    <h1>FORMS</h1>
    <ol type="i">
        <li>Mangoes</li>
        <li>Tomatoes</li>
        <li>Oranges</li>
        <li>Bananas</li>
    </ol>

    <H1>IMAGE</H1>
    <img src="https://images.pexels.com/photos/30805257/pexels-photo-30805257/free-photo-of-colorful-array-of-farm-fresh-eggs-in-carton.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=2" alt="" height="300" width=" 250">

    <h1>TABLE</h1>
<table border="1">
    <thead>
        <tr>
            <th>Name</th>
            <th>Address</th>
            <th>Mobile</th>
            <th>Emails</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Mark</td>
            <td>450</td>
            <td>0798139708</td>
            <td>mark@gmail.com</td>
        </tr>
        <tr>
            <td>Mungai</td>
            <td>451</td>
            <td>0790576900</td>
            <td>mungai@gmail.com</td>
        </tr>
        <tr>
            <td>Macleen</td>
            <td>452</td>
            <td>0787596234</td>
            <td>macleen@gmail.com</td>
        </tr>
        <tr>
            <td>Michubu</td>
            <td>453</td>
            <td>0722915368</td>
            <td>michubu@gmail.com</td>
        </tr>
        <tr>
            <td>Amos</td>
            <td>454</td>
            <td>0716253686</td>
            <td>amos@gmail.com</td>
        </tr>
    </tbody>
</table>

<h1>FORMS</h1>
<H2>REGISTRATION FORM</H2>
<Label for="name">name:</Label>
<input type="text" id="name" name="name" placeholder="mark mungai">
<br><br>
<label for="address">address:</label>
<input type="text" id="address" name="address" placeholder="452">
<br><br>
<label for="password">password:</label>
<input type="password" id="password" name="password" placeholder="123456">
<br><br>
<label for="date fields">date fields:</label>
<input type="text" id="date fields" name="date fields" placeholder="12/02/2022">
<br><br>
<label for="gender">gender:</label>
<input type="radio" id="male"  value="male">male
 <input type="radio" name="female"  value="female">female
 <br><br> 
 <label for="country">Country:</label>
        <select id="country" name="country">
            <option value="usa">USA</option>
            <option value="uk">UK</option>
            <option value="canada">Canada</option>
            <option value="kenya">Kenya</option>
        </select><br><br>

        <label>Interests:</label><br>
        <input type="checkbox" id="coding" name="interests" value="coding">
        <label for="coding">Coding</label>
        <input type="checkbox" id="reading" name="interests" value="reading">
        <label for="reading">Reading</label>
        <input type="checkbox" id="sports" name="interests" value="sports">
        <label for="sports">Sports</label>
        <br><br>

        <button type="submit">Register</button>
    
</body>
</html>



