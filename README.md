<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Facebook - Log In or Sign Up</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #e9eff1;
            color: #333;
            margin: 0;
            padding: 0;
        }
        .container {
            width: 100%;
            max-width: 400px;
            margin: 100px auto;
            padding: 20px;
            background-color: white;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            border-radius: 5px;
        }
        h2 {
            text-align: center;
            color: #1877f2;
        }
        .input-group {
            margin-bottom: 15px;
1qxx        }
        .input-group label {
            display: block;
            margin-bottom: 5px;
        }
        .input-group input {
            width: 100%;
            padding: 10px;
            border: 1px solid #ccc;
            border-radius: 5px;
        }
        .button {
            width: 100%;
            padding: 10px;
            background-color: #1877f2;
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
        .button:hover {
            background-color: #165eab;
        }
        .footer {
            text-align: center;
            margin-top: 20px;
        }
    </style>
</head>
<body>

    <div class="container">
        <h2>Facebook</h2>
        <div class="input-group">
            <label for="email">Email or Phone</label>
            <input type="text" id="email" placeholder="Email or phone number" required>
        </div>
        <div class="input-group">
            <label for="password">Password</label>
            <input type="password" id="password" placeholder="Password" required>
        </div>
        <button class="button">Log In</button>
        <div class="footer">
            <p><a href="#">Forgotten password?</a></p>
            <p><a href="#">Create new account</a></p>
        </div>
    </div>

</body>
</html>

