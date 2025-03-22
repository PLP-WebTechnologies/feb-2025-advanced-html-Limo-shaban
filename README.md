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
<!DOCTYPE html>
<html lang="
en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Structured HTML Page</title>
</head>
<body>
    <!-- Ordered List with Roman Numerals -->
    <h2>Ordered List</h2>
    <ol type="I">
        <li>First Item</li>
        <li>Second Item</li>
        <li>Third Item</li>
        <li>Fourth Item</li>
        <li>Fifth Item</li>
    </ol>

    <!-- External Image -->
    <h2>Image from Pexels</h2>
    <img src="https://www.pexels.com/photo/sample-image.jpg" alt="Sample Image from Pexels" width="500">

    <!-- Contacts Table -->
    <h2>Contacts</h2>
    <table border="1">
        <thead>
            <tr>
                <th>Name</th>
                <th>Address</th>
                <th>Mobile</th>
                <th>Email</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>John Doe</td>
                <td>123 Street, City</td>
                <td>+1234567890</td>
                <td>john@example.com</td>
            </tr>
            <tr>
                <td>Jane Smith</td>
                <td>456 Avenue, City</td>
                <td>+0987654321</td>
                <td>jane@example.com</td>
            </tr>
            <tr>
                <td>Michael Johnson</td>
                <td>789 Road, City</td>
                <td>+1122334455</td>
                <td>michael@example.com</td>
            </tr>
            <tr>
                <td>Emily Brown</td>
                <td>1011 Street, City</td>
                <td>+5566778899</td>
                <td>emily@example.com</td>
            </tr>
            <tr>
                <td>David Wilson</td>
                <td>1314 Avenue, City</td>
                <td>+6677889900</td>
                <td>david@example.com</td>
            </tr>
        </tbody>
    </table>

    <!-- Registration Form -->
    <h2>Registration Form</h2>
    <form>
        <!-- Name Field -->
        <label for="name">Full Name:</label>
        <input type="text" id="name" name="name" placeholder="Enter your full name" required>
        <br><br>

        <!-- Email Field -->
        <label for="email">Email:</label>
        <input type="email" id="email" name="email" placeholder="Enter your email" required>
        <br><br>

        <!-- Password Field -->
        <label for="password">Password:</label>
        <input type="password" id="password" name="password" placeholder="Enter your password" required minlength="6">
        <br><br>

        <!-- Date of Birth Field -->
        <label for="dob">Date of Birth:</label>
        <input type="date" id="dob" name="dob" required>
        <br><br>

        <!-- Dropdown Field -->
        <label for="country">Country:</label>
        <select id="country" name="country" required>
            <option value="">Select your country</option>
            <option value="kenya">Kenya</option>
            <option value="uganda">Uganda</option>
            <option value="tanzania">Tanzania</option>
        </select>
        <br><br>

        <!-- Radio Buttons -->
        <label>Gender:</label>
        <input type="radio" id="male" name="gender" value="male" required>
        <label for="male">Male</label>
        <input type="radio" id="female" name="gender" value="female" required>
        <label for="female">Female</label>
        <br><br>

        <!-- Checkboxes -->
        <label>Interests:</label>
        <input type="checkbox" id="sports" name="interests" value="sports">
        <label for="sports">Sports</label>
        <input type="checkbox" id="music" name="interests" value="music">
        <label for="music">Music</label>
        <input type="checkbox" id="reading" name="interests" value="reading">
        <label for="reading">Reading</label>
        <br><br>

        <!-- Submit Button -->
        <button type="submit">Register</button>
    </form>
</body>
</html>
Happy Coding! 💻✨
