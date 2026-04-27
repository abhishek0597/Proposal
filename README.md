<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Valentine Proposal 💖</title>
<style>
    *{
        margin:0;
        padding:0;
        box-sizing:border-box;
    }

    body {
        height: 100vh;
        display: flex;
        justify-content: center;
        align-items: center;
        background: linear-gradient(135deg, #ff9a9e, #fad0c4, #ffdde1);
        font-family: Arial, sans-serif;
        overflow: hidden;
    }

    .container {
        text-align: center;
        padding: 40px;
        border-radius: 25px;
        background: rgba(255,255,255,0.15);
        backdrop-filter: blur(10px);
        box-shadow: 0 8px 30px rgba(0,0,0,0.2);
        z-index: 2;
    }

    .top-text {
        background: #ff4d6d;
        color: white;
        padding: 15px 25px;
        border-radius: 20px;
        font-size: 32px;
        font-weight: bold;
        display: inline-block;
        margin-bottom: 20px;
        box-shadow: 0 5px 15px rgba(0,0,0,0.2);
    }

    h1 {
        color: white;
        font-size: 48px;
        margin: 12px 0;
        text-shadow: 2px 2px 10px rgba(0,0,0,0.2);
    }

    .buttons {
        margin-top: 25px;
        position: relative;
    }

    button {
        padding: 15px 35px;
        margin: 10px;
        border: none;
        border-radius: 15px;
        font-size: 24px;
        cursor: pointer;
        font-weight: bold;
        transition: 0.3s ease;
    }

    .yes {
        background: #ff1744;
        color: white;
        box-shadow: 0 4px 15px rgba(255, 23, 68, 0.5);
    }

    .yes:hover {
        transform: scale(1.08);
    }

    .no {
        background: #222;
        color: white;
        position: absolute;
    }

    .heart {
        position: absolute;
        font-size: 25px;
        animation: float linear infinite;
        opacity: 0.8;
    }

    @keyframes float {
        from {
            transform: translateY(100vh) scale(0.8);
            opacity: 1;
        }
        to {
            transform: translateY(-100vh) scale(1.3);
            opacity: 0;
        }
    }

    @media (max-width:600px){
        h1{
            font-size:32px;
        }
        .top-text{
            font-size:22px;
        }
        button{
            font-size:18px;
            padding:12px 24px;
        }
    }
</style>
</head>
<body>

<div class="container">
    <div class="top-text">Single rehna hai kya 😜</div>
    <h1>Riya Katariya💕</h1>
    <h1>Will you be my Valentine?</h1>

    <div class="buttons">
        <button class="yes" onclick="yesClick()">Yes 💖</button>
        <button class="no" id="noBtn">No 😉</button>
    </div>
</div>

<script>
    const noBtn = document.getElementById("noBtn");

    noBtn.addEventListener("mouseover", () => {
        const x = Math.random() * (window.innerWidth - 120);
        const y = Math.random() * (window.innerHeight - 70);
        noBtn.style.left = x + "px";
        noBtn.style.top = y + "px";
    });

    function yesClick() {
        document.body.innerHTML = `
            <div style="display:flex;justify-content:center;align-items:center;height:100vh;background:linear-gradient(135deg,#ff758c,#ff7eb3);font-family:Arial;">
                <h1 style="color:white;font-size:60px;text-align:center;">
                    Yayyy ❤️🥰<br>Best Decision Ever 💍✨
                </h1>
            </div>
        `;
    }

    function createHeart() {
        const heart = document.createElement("div");
        heart.classList.add("heart");
        heart.innerHTML = "❤️";
        heart.style.left = Math.random() * 100 + "vw";
        heart.style.animationDuration = (3 + Math.random() * 5) + "s";
        heart.style.fontSize = (20 + Math.random() * 20) + "px";
        document.body.appendChild(heart);

        setTimeout(() => {
            heart.remove();
        }, 8000);
    }

    setInterval(createHeart, 300);
</script>

</body>
</html>
