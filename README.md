<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>DarkoTHC Messaging</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            background-color: #333333;
        }
        .container {
            text-align: center;
            background: #171717;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }
        input {
            padding: 10px;
            font-size: 16px;
            margin-bottom: 10px;
        }
        button {
            padding: 10px 15px;
            font-size: 16px;
            background-color: #007bff;
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
        button:hover {
            background-color: #0056b3;
        }
        .message {
            margin-top: 15px;
            font-size: 18px;
            white-space: pre-line;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>DarkoTHC Messaging</h1>
        <input type="password" id="passwordInput" placeholder="Enter password">
        <br>
        <button onclick="checkPassword()">Submit</button>
        <div class="message" id="message"></div>
    </div>
</body>
