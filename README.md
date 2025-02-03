<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title> Valentine's Day</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            text-align: center;
            background-color: #ffdde1;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
            overflow: hidden;
        }
        h1 {
            color: #d63384;
            font-size: 2.5em;
            margin-bottom: 20px;
        }
        .btn-container {
            position: relative;
        }
        button {
            font-size: 1.2em;
            padding: 10px 20px;
            margin: 10px;
            border: none;
            cursor: pointer;
            border-radius: 5px;
            transition: 0.3s;
        }
        .yes {
            background-color: #ff4081;
            color: white;
        } 
        .no{
            background-color: #333;
            color: white;
            position: absolute;
            left: 50%;
            transform: translateX(-50%);
        }
  .yes:hover{ 
  background-color: #d81b60;
            }
   <style/>
<head/>
<body>
    <h1>Will you be my Valentine Lamar? ❤️<h1/>
    <div class="btn-container">
        <button class="yes" onclick="sayYes()">Yes</button>
        <button class="no" onmouseover="moveNo()">No</button
                                                      <div/>

  <script>
        function sayYes() {
            alert("Yay! 💖 Can't wait to celebrate with you!");
        }

        function moveNo() {
            let button = document.querySelector('.no');
            let x = Math.random() * (window.innerWidth - button.offsetWidth);
            let y = Math.random() * (window.innerHeight - button.offsetHeight);
            button.style.left = `${x}px`;
            button.style.top = `${y}px`;
        }
   <script/>
<body/>
<html/>
