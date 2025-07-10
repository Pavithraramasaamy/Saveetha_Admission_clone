# Saveetha_Admission_clone
## Date:09-07-2025

## Objective:
To design a landing page clone of Saveetha Engineering College’s Admission Enquiry form using HTML and CSS. This activity reinforces skills in layout design, form creation, user input handling, responsive structure, and visual styling based on a real-world example.

## Tasks:
#### 1. Analyze the Landing Page Layout:
Observe the split-screen layout with a promotional section on the left and a form on the right.

Note the use of background images, text styling, and branding elements.

#### 2. Create the HTML Structure:
Use semantic tags like ```<section>, <header>, <form>, and <footer>``` to organize content.

Structure the form with input fields such as name, email, phone, password, city, state, course, specialization, captcha, and checkbox.

#### 3. Add Form Functionality:
Include appropriate input types (text, email, tel, password, select, etc.) with placeholders and labels.

Use the <button> element for the "APPLY NOW" action.

#### 4. Apply CSS Styling:
Implement a split layout using flexbox or grid.

Style the form elements with padding, shadows, background colors, and rounded borders.

Include hover effects and button transitions to match the original look.

#### 5. Incorporate Images and Branding:
Add the institution logo and use matching fonts and colors.

Place a background image or blurred overlay behind the form content if needed.

#### 6. Ensure Responsiveness:
Make sure the page adapts to different screen sizes using media queries.

Maintain readability and layout integrity on both desktop and mobile.

## HTML Code:
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Saveetha Engineering College Admission</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>

  <div class="form-container">
    <h2>Admissions Open 2025</h2>

    <form>
      <input type="text" placeholder="Enter Name *" required>
      <input type="email" placeholder="Enter Email Address *" required>

      <div class="phone-group">
        <select>
          <option>+91</option>
        </select>
        <input type="tel" placeholder="Enter Mobile Number *" required>
      </div>

      <input type="password" placeholder="Any Password of Your Choice *" required>

      <div class="two-cols">
        <input type="text" placeholder="State *" required>
        <input type="text" placeholder="City *" required>
      </div>

      <div class="two-cols">
        <input type="text" placeholder="Course *" required>
        <input type="text" placeholder="Specialization *" required>
      </div>

      <div class="captcha">
        <span class="captcha-text">X9ZT2K</span>
        <input type="text" placeholder="Enter text as shown *" required>
      </div>

      <button type="submit" class="submit-btn">APPLY NOW ➤</button>

      <p class="login-link">
        Already have an Account? <a href="#">Login</a><br>
        <a href="#">Resend Verification Email</a>
      </p>
    </form>
  </div>

</body>
</html>

```
## CSS Code:

```

body {
  height: 100vh;
  margin: 0;
  font-family: Arial, sans-serif;
  background-image: url('saveetha.jpg');
  background-size: cover;
  background-position: center;
  background-repeat: no-repeat;
  display: flex;
  justify-content: flex-end; 
  align-items: center;
  padding-right: 5%; 
}

.form-container {
  background-color: rgba(0, 0, 0, 0.6); 
  padding: 30px;
  border-radius: 12px;
  max-width: 400px;
  width: 100%;
  color: white;
  box-shadow: 0 0 15px rgba(0, 0, 0, 0.5);
}

h2 {
  text-align: center;
  margin-bottom: 20px;
  color: #fff;
}

input, select {
  width: 100%;
  padding: 10px;
  margin: 8px 0;
  border-radius: 6px;
  border: none;
  box-sizing: border-box;
}

.phone-group {
  display: flex;
  gap: 10px;
}

.two-cols {
  display: flex;
  gap: 10px;
}

.captcha {
  display: flex;
  gap: 10px;
  margin: 10px 0;
}

.captcha-text {
  background: #fff;
  color: #000;
  padding: 8px;
  border-radius: 5px;
  font-weight: bold;
}

.checkbox {
  margin: 10px 0;
  font-size: 13px;
}

.submit-btn {
  width: 100%;
  background-color: #f9b43a;
  color: black;
  padding: 12px;
  font-weight: bold;
  border: none;
  border-radius: 6px;
  margin-top: 10px;
  cursor: pointer;
}

.login-link {
  text-align: center;
  font-size: 14px;
  margin-top: 10px;
}

.login-link a {
  color: #f9b43a;
  text-decoration: none;
}

@media (max-width: 768px) {
  .form-container {
    margin: 20px;
  }
}
```
## Output:

![image](https://github.com/user-attachments/assets/c5570eaf-b9c0-43c7-b820-bf2555bc1de4)


## Result:
A landing page clone of Saveetha Engineering College’s Admission Enquiry form using HTML and CSS is designed successfully.
