# Valentine
For Afsara ❤️
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Afsara, Will You Be My Valentine?</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="container">
        <h1>💖 Hey Afsara! 💖</h1>
        <p class="intro">I made this just for you, to show you how much you mean to me! 💕</p>

        <div class="template" id="template1">
            <h2>1. My Heart Beats for You ❤️</h2>
            <p>Afsara, every time I think of you, my heart skips a beat. You make my life brighter every single day!</p>
        </div>

        <div class="template" id="template2">
            <h2>2. You’re My Sunshine ☀️</h2>
            <p>Whenever you smile, Afsara, it feels like the sun just came out. You make everything better!</p>
        </div>

        <div class="template" id="template3">
            <h2>3. I Love Your Laugh 😄</h2>
            <p>Your laughter is my favorite sound in the whole world. I could listen to it forever, Afsara.</p>
        </div>

        <div class="template" id="template4">
            <h2>4. You’re My Favorite Adventure 🌍</h2>
            <p>Being with you is like exploring the most beautiful places, even if we’re just sitting at home. Every moment with you is magical!</p>
        </div>

        <div class="template" id="template5">
            <h2>5. Afsara, You Inspire Me 🌸</h2>
            <p>Everything you do is amazing. Your kindness, your strength, your heart—Afsara, you inspire me to be a better person every day.</p>
        </div>

        <div class="template" id="template6">
            <h2>6. I Think About You Constantly 💭</h2>
            <p>No matter what I’m doing, you’re always on my mind, Afsara. You are my everything.</p>
        </div>

        <div class="template" id="template7">
            <h2>7. You Make Ordinary Moments Special ✨</h2>
            <p>Even the simplest things become unforgettable with you. Afsara, life with you is pure magic.</p>
        </div>

        <div class="template" id="template8">
            <h2>8. I’m Grateful for You 🙏</h2>
            <p>Thank you for being the most wonderful part of my life, Afsara. I cherish every memory we make together.</p>
        </div>

        <div class="template" id="template9">
            <h2>9. You’re My Forever Valentine 💘</h2>
            <p>I want to laugh with you, cry with you, dream with you, and love you forever, Afsara. Will you be my Valentine?</p>
        </div>

        <div class="template" id="template10">
            <h2>10. A Little Surprise 🎉</h2>
            <p>Click the heart below to see a special message just for you! 💌</p>
            <button id="heartBtn">💖 Click Me 💖</button>
            <p id="surprise" style="display:none;">Afsara, I LOVE YOU more than words can say! Will you be my Valentine? 💕</p>
        </div>
    </div>

    <script src="script.js"></script>
</body>
</html>
body {
    font-family: 'Comic Sans MS', cursive, sans-serif;
    background: linear-gradient(to right, #ff9a9e, #fad0c4);
    color: #fff;
    text-align: center;
    padding: 20px;
}

.container {
    max-width: 800px;
    margin: auto;
}

h1 {
    font-size: 3em;
    margin-bottom: 10px;
}

h2 {
    margin-top: 30px;
    font-size: 2em;
    color: #ffe0e0;
}

p {
    font-size: 1.2em;
    line-height: 1.5em;
    margin: 10px 0;
}

button {
    font-size: 1.5em;
    padding: 10px 20px;
    margin-top: 15px;
    border: none;
    border-radius: 10px;
    cursor: pointer;
    background-color: #ff6f91;
    color: #fff;
    transition: transform 0.2s;
}

button:hover {
    transform: scale(1.1);
}

.template {
    background-color: rgba(255, 255, 255, 0.1);
    margin: 20px 0;
    padding: 20px;
    border-radius: 15px;
}
const heartBtn = document.getElementById("heartBtn");
const surprise = document.getElementById("surprise");

heartBtn.addEventListener("click", () => {
    surprise.style.display = "block";
    heartBtn.style.display = "none";
    document.body.style.background = "linear-gradient(to right, #ff758c, #ff7eb3)";
    alert("Afsara, I love you endlessly! 💖");
});
