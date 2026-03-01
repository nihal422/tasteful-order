# tasteful-order
First, solve the problem. Then, write the code.
<br>
Author - nihal422
[Sign up page.html](https://github.com/user-attachments/files/25659357/Sign.up.page.html)

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sign Up Page</title>
    <style>
        /* Basic reset */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

/* Body styling */
body {
    
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background-image: url('https://images.pexels.com/photos/1103970/pexels-photo-1103970.jpeg?cs=srgb&dl=pexels-jplenio-1103970.jpg&fm=jpg'); /* Replace with your image path */
    background-size: cover;
    background-position: center;
    font-family: Arial, sans-serif;
    background-color: #4f4f6800;
    display: flex;
    justify-content: center;
    align-items: center;
    height: 90vh;
}

/* Container for sign-up form */
.signup-container {
    width: 100%;
    max-width: 400px;
    background-color: #ffffff26;
    padding: 30px;
    box-shadow: 0 4px 8px rgba(172, 157, 157, 0);
    border-radius: 8px;
}

/* Heading styling */
h2 {
    text-align: center;
    margin-bottom: 20px;
    color:  #000000b5;
}

/* Input fields styling */
.input-group {
    margin-bottom: 15px;
}

.input-group label {
    display: block;
    font-weight: bold;
    margin-bottom: 5px;
    color: #000000b5;
}

.input-group input {
    width: 100%;
    padding: 10px;
    border: 1px solid #ddd;
    border-radius: 5px;
    font-size: 14px;
    color: #333;
}

.input-group input:focus {
    border-color: #007bff;
    outline: none;
}
/* Sign-in link */
.signin-link {
    text-align: center;
    margin-top: 10px;
}

.signin-link a {
    color: #007bff;
    text-decoration: none;
}

.signin-link a:hover {
    text-decoration: underline;
}
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

/* Body styling */
body {
    font-family: Arial, sans-serif;
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
    background-color: #f4f4f9;
}
.button {
    width: 100%;
    padding: 10px;
    background-color: #007bff;
    color: #fff;
    border: none;
    border-radius: 5px;
    font-size: 16px;
    cursor: pointer;
}

.button {
    background-color: #0056b3;
}
    </style>
</head>
<body>
    <div class="signup-container">
        <div class="signup-form">
            <h2>Sign Up</h2>
            <form action="signup_process.php" method="POST">
                <div class="input-group">
                    <label for="username">Username:</label>
                    <input type="text" id="username" name="username" required>
                </div>
                <div class="input-group">
                    <label for="email">Email:</label>
                    <input type="email" id="email" name="email" >
                </div>
                <div class="input-group">
                    <label for="password">Password:</label>
                    <input type="password" id="password" name="password" required>
                </div>
                <div class="input-group">
                    <label for="confirm-password">Confirm Password:</label>
                    <input type="password" id="confirm-password" name="confirm-password" required>
                </div>
                <button class="button">SUBMIT</button>
            </form>
            <div class="signin-link">
                <p>Already have an account? <a href="C:\Users\Shari\OneDrive\Desktop\vs codes\codes\log in page.html">Log in</a></p>
            </div>
        </div>
    </div>
</body>
</html>
