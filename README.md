# 🔐 Login & Sign Up Form

This project contains a **Login Form** and a **Sign Up Form** created using **HTML5 and CSS3**.

Both pages use a modern gradient background, centered forms, and simple navigation between the Login and Sign Up pages.

## 🌐 Project Overview

The project consists of two web pages:

1. **Login Page**
2. **Sign Up Page**

Users can navigate between the two pages using the links provided in each form.

## ✨ Features

### 🔑 Login Form

The Login page contains:

* Email or Phone input
* Password input
* Forgot Password text
* Login button
* Sign Up navigation link
* Gradient background
* Centered login card
* Rounded corners

### 📝 Sign Up Form

The Sign Up page contains:

* First Name
* Last Name
* Gender selection
* Date of Birth
* Mobile Number
* Email
* Confirm Email
* Password
* Confirm Password
* Terms and Conditions checkbox
* Sign Up button
* Login navigation link

## 🎨 Design

The pages use a **linear gradient** background:

```css
background: linear-gradient(90deg, skyblue, purple);
```

The form is displayed in the center of the page using **Flexbox**:

```css
display: flex;
align-items: center;
justify-content: center;
```

The form has a white background with rounded corners:

```css
background-color: white;
border-radius: 10px;
```

## 🛠️ Technologies Used

* HTML5
* CSS3
* Flexbox
* Linear Gradient
* HTML Forms
* Input Fields
* Radio Buttons
* Checkbox
* Navigation Links

## 📁 Project Structure

```text
Login-SignUp/
│
├── assignment-10.html
├── SignUp.html
└── README.md
```

> You can rename the HTML files according to your project requirements.

## 🔗 Page Navigation

The Login page contains a link to the Sign Up page:

```html
<a href="SignUp.html">Sign Up</a>
```

The Sign Up page contains a link back to the Login page:

```html
<a href="assignment-10.html">LOGIN</a>
```

This allows users to move between both pages.

## 📋 Login Form Structure

```text
┌─────────────────────────────┐
│         LOGIN FORM          │
│                             │
│ Email or Phone              │
│ ┌─────────────────────────┐ │
│ │ xyz@gmail.com           │ │
│ └─────────────────────────┘ │
│                             │
│ Password                    │
│ ┌─────────────────────────┐ │
│ │ ********                │ │
│ └─────────────────────────┘ │
│                             │
│ Forgot Password ?           │
│                             │
│ ┌─────────────────────────┐ │
│ │          LOGIN          │ │
│ └─────────────────────────┘ │
│                             │
│ Not a Member? Sign Up       │
└─────────────────────────────┘
```

## 📋 Sign Up Form Structure

```text
┌─────────────────────────────┐
│           Sign Up           │
│                             │
│ First Name                  │
│ Last Name                   │
│ Gender                      │
│ Date Of Birth               │
│ Mobile No                   │
│ Email                       │
│ Confirm Email               │
│ Password                    │
│ Confirm Password            │
│                             │
│ ☐ Terms And Conditions      │
│                             │
│ ┌─────────────────────────┐ │
│ │         Sign Up         │ │
│ └─────────────────────────┘ │
│                             │
│ Already a Member? LOGIN     │
└─────────────────────────────┘
```

## 🚀 How to Run

1. Create a folder for the project.
2. Save the Login page as `assignment-10.html`.
3. Save the Sign Up page as `SignUp.html`.
4. Keep both HTML files in the **same folder**.
5. Open `assignment-10.html` in a web browser.
6. Click **Sign Up** to open the registration page.
7. Click **LOGIN** to return to the Login page.

## 🎯 Learning Objectives

This project helps in understanding:

* Creating HTML forms
* Different types of input fields
* Radio buttons and checkboxes
* Password fields
* HTML page navigation
* CSS Flexbox
* CSS gradients
* Form styling
* Margins and padding
* Border radius
* Basic responsive viewport setup

## ⚠️ Note

This project currently demonstrates the **front-end design only**. The Login and Sign Up buttons do not connect to a database or perform real authentication.

For a functional authentication system, a backend and database would need to be added.

## 👨‍💻 Author

Created as an **HTML & CSS practice project** for learning form design and webpage navigation.
