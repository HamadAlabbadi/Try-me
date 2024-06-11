# Try-me
<!DOCTYPE html>
<html>
<head>
    <title>نموذج تسجيل</title>
    <style>
        body {
            background-color: white;
            font-family: Arial, sans-serif;
            color: black;
            margin: 0;
            padding: 20px;
        }
        form {
            max-width: 300px;
            margin: 0 auto;
            padding: 20px;
            border: 1px solid #ccc;
            border-radius: 5px;
            background-color: #f9f9f9;
        }
        label {
            display: block;
            margin-bottom: 8px;
            font-weight: bold;
        }
        input[type="email"],
        input[type="password"] {
            width: 100%;
            padding: 8px;
            margin-bottom: 10px;
            border: 1px solid #ccc;
            border-radius: 4px;
        }
        input[type="submit"] {
            width: 100%;
            padding: 10px;
            background-color: #1679AB;
            border: none;
            border-radius: 4px;
            color: white;
            font-size: 16px;
            cursor: pointer;
        }
        input[type="submit"]:hover {
            background-color: #45a049;
        }
    </style>
</head>
<body>
    <form action="your-server-endpoint" method="post">
        <label for="email">البريد الإلكتروني:</label>
        <input type="email" id="email" name="email" required>
        <br>
        <label for="password">كلمة المرور:</label>
        <input type="password" id="password" name="password" required>
        <br>
        <input type="submit" value="تسجيل">
    </form>
</body>
</html>
