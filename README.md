<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Happy Rose Day, Alku🥰</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            background-color: #f9f9f9;
            padding: 20px;
        }
        .roses {
            display: flex;
            justify-content: center;
            gap: 20px;
            margin-bottom: 20px;
        }
        .rose {
            width: 150px;
            height: auto;
        }
        #message {
            display: none;
            margin-top: 20px;
            font-size: 18px;
            line-height: 1.6;
        }
        button {
            background-color: #ff69b4;
            color: white;
            border: none;
            padding: 10px 20px;
            font-size: 16px;
            cursor: pointer;
            border-radius: 5px;
        }
        button:hover {
            background-color: #ff1493;
        }
    </style>
</head>
<body>
    <h1>Happy Rose Day, Alku🥰</h1>
    <div class="roses">
        <img src="https://example.com/white-rose.jpg" alt="White Rose" class="rose"> <!-- Replace with actual white rose image URL -->
        <img src="https://example.com/red-rose.jpg" alt="Red Rose" class="rose"> <!-- Replace with actual red rose image URL -->
    </div>
    <p>Click OK to open your special message!</p>
    <button onclick="showMessage()">Click OK</button>
    <div id="message">
        <p>Your smile lights up my world like the first bloom of a rose--bright, beautiful, and full of joy. And your eyes? They're like deep, captivating petals that draw me in every time I look at you.</p>
        <p>Alku, you mean the world to me, and my love for you grows stronger every day, just like these roses in full bloom. You're my everything, and I cherish every moment with you.</p>
        <p>I may not be the most handsome boy you've met, or the smartest. But I promise I'll be that boy you can always talk to, the boy you can trust, and I'll always be the boy who will stand by your side and love you no matter what happens.</p>
        <p>With all my love,<br>Shubh</p>
    </div>
    <script>
        function showMessage() {
            document.getElementById('message').style.display = 'block';
        }
    </script>
</body>
</html>
