<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Valentine Proposal 💖</title>
<style>
   @import url('https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700;800&display=swap');

*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:'Poppins',sans-serif;
}

body{
    height:100vh;
    display:flex;
    justify-content:center;
    align-items:center;
    background:
    radial-gradient(circle at top left,#2d1b00,#000),
    radial-gradient(circle at bottom right,#3a2600,#000);
    overflow:hidden;
}

.container{
    width:90%;
    max-width:750px;
    text-align:center;
    padding:60px;
    background:rgba(255,255,255,0.05);
    backdrop-filter:blur(20px);
    border:1px solid rgba(255,215,0,0.15);
    border-radius:30px;
    box-shadow:
    0 0 40px rgba(255,215,0,0.08),
    0 20px 50px rgba(0,0,0,0.5);
    animation:fadeIn 1.2s ease;
}

.badge{
    display:inline-block;
    padding:10px 25px;
    border-radius:50px;
    background:rgba(255,215,0,0.1);
    color:#FFD700;
    border:1px solid rgba(255,215,0,0.2);
    font-size:15px;
    letter-spacing:2px;
    margin-bottom:25px;
}

h1{
    font-size:60px;
    font-weight:800;
    color:white;
    line-height:1.2;
}

.highlight{
    color:#FFD700;
}

.subtitle{
    color:#cfcfcf;
    font-size:18px;
    margin-top:20px;
    line-height:1.8;
}

.buttons{
    margin-top:40px;
}

button{
    padding:15px 40px;
    margin:10px;
    border:none;
    border-radius:50px;
    font-size:18px;
    font-weight:600;
    cursor:pointer;
    transition:0.4s;
}

.yes{
    background:linear-gradient(135deg,#FFD700,#FFB800);
    color:#000;
}

.yes:hover{
    transform:translateY(-5px);
    box-shadow:0 10px 30px rgba(255,215,0,0.4);
}

.no{
    background:transparent;
    border:2px solid rgba(255,255,255,0.2);
    color:white;
}

.no:hover{
    background:rgba(255,255,255,0.08);
}

.glow{
    position:absolute;
    width:500px;
    height:500px;
    background:#FFD700;
    filter:blur(250px);
    opacity:0.08;
    border-radius:50%;
    z-index:-1;
}

@keyframes fadeIn{
    from{
        opacity:0;
        transform:translateY(30px);
    }
    to{
        opacity:1;
        transform:translateY(0);
    }
}

@media(max-width:768px){

    .container{
        padding:40px 25px;
    }

    h1{
        font-size:38px;
    }

    .subtitle{
        font-size:16px;
    }

    button{
        width:100%;
        max-width:250px;
    }
}
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
<div class="glow"></div>

<div class="container">

    <div class="badge">
        SPECIAL MOMENT ✨
    </div>

    <h1>
        Anshi,<br>
        <span class="highlight">Will You Be Mine Forever?</span>
    </h1>

    <p class="subtitle">
        Every beautiful memory becomes more meaningful because of you.
        Today I just want to ask one simple question.
    </p>

    <div class="buttons">
        <button class="yes">Yes ❤️</button>
        <button class="no">No 😅</button>
    </div>

</div>

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
