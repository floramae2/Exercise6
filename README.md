<!--<!DOCTYPE html>-->
<html>
<head>
    <meta charset="UTF-8">
    <title>Registration Form</title>
    <style>
        
        body {
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            min-height: 100vh; 
            margin: 0;
            background-color: rgba(22, 199, 223, 0.938);
        }

        
        form {
            text-align: center;
        }

       
        .input-group {
            display: flex;
            align-items: center;
            margin: 1em auto; 
        }

        label, input {
            margin-right: 0.5em;
        }

        button {
            display: block;
            margin: 1em auto; 
            padding: 0.5em; 
        }
    </style>
</head>
<body>
    <form>
        <div class="input-group">
            <label for="username">Username:</label>
            <input type="text" id="username" name="username" placeholder="username">
        </div>
        <div class="input-group">
            <label for="password">Password:</label>
            <input type="password" id="password" name="password" placeholder="password">
        </div>
        <button type="submit">Register</button>
    </form>
</body>
</html>
