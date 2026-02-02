# valentine.html
<style> * { box-sizing: border-box; font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", sans-serif; } body { margin: 0; min-height: 100vh; background: linear-gradient(135deg, #ff758c, #ff7eb3); display: flex; align-items: center; justify-content: center; color: #4a148c; } .container { background: green; padding: 40px; border-radius: 20px; width: 100%; max-width: 420px; text-align: center; box-shadow: 0 25px 60px rgba(0,0,0,0.25); position: relative; overflow: hidden; } h1 { margin-top: 0; font-size: 28px; } p { color: #555; margin-bottom: 25px; } .buttons { display: flex; justify-content: center; gap: 15px; margin-top: 20px; position: relative; height: 60px; } button { padding: 14px 26px; font-size: 16px; border: none; border-radius: 30px; cursor: pointer; transition: transform 0.15s ease; position: absolute; } button:hover { transform: scale(1.05); } .yes { background: #ff4d6d; color: white; left: 50%; transform: translateX(-110%); } .no { background: #eee; color: #444; left: 50%; transform: translateX(10%); } footer { margin-top: 30px; font-size: 12px; color: #aaa; } </style>
Valentine Proposal 💖
This page was built with care, confidence, and a very important question.

<h2> adrianna Will you be my Valentine?</h2>

<div class="buttons">
  <button class="yes" onclick="sayYes()">Yes 💕</button>
  <button class="no" id="noBtn">No</button>
</div>

<footer>
  Built with ❤️ · Deployed with courage
</footer>
<script> const noBtn = document.getElementById("noBtn"); const container = document.querySelector(".container"); noBtn.addEventListener("mouseenter", () => { const containerRect = container.getBoundingClientRect(); const btnRect = noBtn.getBoundingClientRect(); const maxX = containerRect.width - btnRect.width; const maxY = containerRect.height - btnRect.height; const x = Math.random() * maxX; const y = Math.random() * maxY; noBtn.style.left = `${x}px`; noBtn.style.top = `${y}px`; }); function sayYes() { document.body.innerHTML = `

🥰 It’s a date.
Thank you see you on the 14th im not done 😉. now playing:what you heard - brent faiyaz

<iframe style="border-radius:12px" src="https://open.spotify.com/embed/track/1mS3J3K1Y6v6jQxOZ9YFJZ?utm_source=generator&autoplay=1" width="300" height="80" frameborder="0" allow="autoplay; clipboard-write; encrypted-media; fullscreen; picture-in-picture" ></iframe>
`; } </script>
