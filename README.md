# Login-FLogin Form

A simple and responsive Login Form UI built using HTML and CSS. The form features a modern gradient background, centered login card, email and password fields, a forgot-password message, and a sign-up link.

Features

- 🎨 Gradient background using CSS
- 📋 Email input field
- 🔒 Password input field
- 🔑 Forgot password text
- 🚪 Login button
- 📝 Sign-up link for new members
- 📱 Basic responsive viewport configuration
- ✨ Clean and simple user interface

Technologies Used

- HTML5
- CSS3

Project Structure

Login-Form/
│
├── index.html
├── Sign up.html
└── README.md

How to Run

1. Download or clone this project.
2. Open the project folder.
3. Open "index.html" in any modern web browser.
4. The login form will be displayed.

Design

The login form uses:

- A "skyblue" to "purple" linear gradient background.
- A white login card with rounded corners.
- Centered form elements.
- A matching gradient login button.
- Simple typography and spacing for a clean appearance.

HTML Structure

The main components of the form are:

<form>
    <h1>Log In Form</h1>

    <div class="email">
        <label>Email</label>
        <input type="text" placeholder="xyz@gmail.com">
    </div>

    <div class="password">
        <label>Password</label>
        <input type="password" placeholder="abcd@gmail.com">
        <p>Forget Password ?</p>
    </div>

    <div class="login">
        <input type="button" value="Log In" id="login">
        <p>Not a Member? <a href="Sign up.html">Sign Up</a></p>
    </div>
</form>

CSS Highlights

The page background is created with:

background: linear-gradient(90deg, skyblue, purple);

The login card uses:

background-color: white;
border-radius: 10px;

The login button uses the same gradient:

background: linear-gradient(90deg, skyblue, purple);
color: white;
border: none;
border-radius: 10px;

Note

This project is currently a frontend UI only. The login button does not perform actual authentication, and the form does not send user data to a server.

For a functional login system, you would need to add JavaScript and/or a backend with authentication and database support.

License

This project is free to use for learning and personal projects.orm
