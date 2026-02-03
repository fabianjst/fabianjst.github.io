<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Be My Valentine?</title>
    <!-- Importing a cute handwritten font -->
    <link href="https://fonts.googleapis.com/css2?family=Pacifico&family=Nunito:wght@400;700&display=swap" rel="stylesheet">
    <style>
        :root {
            --primary-color: #ff4d6d;
            --secondary-color: #ff8fa3;
            --bg-color: #fff0f3;
            --text-color: #590d22;
        }

        body {
            margin: 0;
            padding: 0;
            height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            background-color: var(--bg-color);
            background-image: radial-gradient(circle, #ffccd5 10%, transparent 11%), radial-gradient(circle, #ffccd5 10%, transparent 11%);
            background-size: 20px 20px;
            background-position: 0 0, 10px 10px;
            font-family: 'Nunito', sans-serif;
            overflow: hidden;
            flex-direction: column;
        }

        /* Floating Hearts Background Animation */
        .bg-heart {
            position: absolute;
            color: rgba(255, 77, 109, 0.2);
            font-size: 2rem;
            animation: float 6s infinite linear;
            z-index: -1;
            user-select: none;
        }

        @keyframes float {
            0% { transform: translateY(110vh) rotate(0deg); opacity: 1; }
            100% { transform: translateY(-10vh) rotate(360deg); opacity: 0; }
        }

        .card {
            background: rgba(255, 255, 255, 0.9);
            padding: 3rem;
            border-radius: 20px;
            box-shadow: 0 10px 25px rgba(255, 77, 109, 0.2);
            text-align: center;
            max-width: 90%;
            width: 400px;
            position: relative;
            z-index: 10;
            transition: transform 0.3s ease;
            backdrop-filter: blur(5px);
            border: 2px solid white;
        }

        h1 {
            font-family: 'Pacifico', cursive;
            color: var(--primary-color);
            font-size: 2.5rem;
            margin-bottom: 1rem;
            line-height: 1.2;
        }

        p {
            color: var(--text-color);
            font-size: 1.1rem;
            margin-bottom: 2rem;
        }

        .gif-container {
            margin-bottom: 1.5rem;
            height: 150px;
            display: flex;
            align-items: center;
            justify-content: center;
        }
        
        /* Using an emoji/svg instead of external image to ensure it loads */
        .cute-bear {
            font-size: 6rem;
            animation: bounce 2s infinite;
        }

        @keyframes bounce {
            0%, 100% { transform: translateY(0); }
            50% { transform: translateY(-10px); }
        }

        .btn-group {
            display: flex;
            justify-content: center;
            gap: 20px;
            position: relative; /* relative for the No button to position initially */
            min-height: 60px; /* Space for buttons */
        }

        button {
            padding: 12px 30px;
            font-size: 1.2rem;
            border: none;
            border-radius: 50px;
            cursor: pointer;
            font-family: 'Nunito', sans-serif;
            font-weight: 700;
            transition: transform 0.2s, box-shadow 0.2s;
        }

        .btn-yes {
            background-color: var(--primary-color);
            color: white;
            box-shadow: 0 4px 15px rgba(255, 77, 109, 0.4);
        }

        .btn-yes:hover {
            transform: scale(1.1);
            background-color: #ff3355;
            box-shadow: 0 6px 20px rgba(255, 77, 109, 0.6);
        }

        .btn-no {
            background-color: #fff;
            color: var(--text-color);
            border: 2px solid var(--secondary-color);
            box-shadow: 0 4px 10px rgba(0,0,0,0.05);
            /* Important for the movement logic */
            position: absolute; 
            /* Start positioned relatively within the flex gap using margins or let JS handle it. 
               We'll position it relatively via JS initially or let it flow then switch to fixed. 
               For simplicity, we'll let it flow normally first. 
            */
            position: static;
        }

        /* Success Message Styling */
        .success-container {
            display: none; /* Hidden by default */
            flex-direction: column;
            align-items: center;
            justify-content: center;
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: var(--bg-color);
            z-index: 100;
            text-align: center;
        }

        .success-title {
            font-family: 'Pacifico', cursive;
            color: var(--primary-color);
            font-size: 4rem;
            margin-bottom: 20px;
            animation: popIn 0.5s ease-out;
        }

        .success-message {
            font-size: 1.5rem;
            color: var(--text-color);
            max-width: 600px;
            padding: 0 20px;
        }

        @keyframes popIn {
            0% { transform: scale(0); opacity: 0; }
            80% { transform: scale(1.1); opacity: 1; }
            100% { transform: scale(1); }
        }

        /* Confetti Canvas */
        #confetti-canvas {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            pointer-events: none;
            z-index: 999;
        }

        @media (max-width: 600px) {
            .card {
                padding: 2rem;
                width: 85%;
            }
            h1 { font-size: 2rem; }
            .cute-bear { font-size: 5rem; }
        }
    </style>
</head>
<body>

    <!-- Floating background hearts generated by JS -->
    <div id="bg-hearts-container"></div>

    <div class="card" id="mainCard">
        <div class="gif-container">
            <div class="cute-bear">🐻❤️</div>
        </div>
        <h1>Will you be my Valentine?</h1>
        <p>It would make me the happiest person in the world!</p>
        
        <div class="btn-group">
            <button class="btn-yes" id="yesBtn">Yes!</button>
            <button class="btn-no" id="noBtn">No</button>
        </div>
    </div>

    <!-- Success Screen -->
    <div class="success-container" id="successScreen">
        <div class="cute-bear" style="font-size: 8rem; margin-bottom: 20px;">🥰💖🎉</div>
        <div class="success-title">YAY!!!</div>
        <p class="success-message">Best decision ever! I love you so much! ❤️</p>
    </div>

    <canvas id="confetti-canvas"></canvas>

    <script>
        // --- Logic for the "No" button escaping ---
        const noBtn = document.getElementById('noBtn');
        const yesBtn = document.getElementById('yesBtn');
        const mainCard = document.getElementById('mainCard');
        const successScreen = document.getElementById('successScreen');
        const bgContainer = document.getElementById('bg-hearts-container');

        const moveButton = () => {
            // Get viewport dimensions
            const containerRect = document.body.getBoundingClientRect();
            const btnRect = noBtn.getBoundingClientRect();

            // Calculate max positions to keep button fully visible
            const maxLeft = containerRect.width - btnRect.width;
            const maxTop = containerRect.height - btnRect.height;

            // Generate random position
            const newLeft = Math.floor(Math.random() * maxLeft);
            const newTop = Math.floor(Math.random() * maxTop);

            // Apply new position
            // We switch to fixed positioning so it can go anywhere on screen
            noBtn.style.position = 'fixed';
            noBtn.style.left = `${newLeft}px`;
            noBtn.style.top = `${newTop}px`;
            
            // Add a little rotation for fun
            const randomRot = Math.floor(Math.random() * 40) - 20;
            noBtn.style.transform = `rotate(${randomRot}deg)`;
        };

        // Trigger move on hover (desktop)
        noBtn.addEventListener('mouseover', moveButton);
        
        // Trigger move on touch (mobile) - prevents tapping
        noBtn.addEventListener('touchstart', (e) => {
            e.preventDefault(); // Prevent click
            moveButton();
        });
        
        // Just in case they manage to click it
        noBtn.addEventListener('click', (e) => {
            e.preventDefault();
            moveButton();
        });

        // --- Logic for the "Yes" button ---
        yesBtn.addEventListener('click', () => {
            // Hide the question card
            mainCard.style.display = 'none';
            // Show success screen
            successScreen.style.display = 'flex';
            // Start Confetti
            startConfetti();
        });


        // --- Background Floating Hearts ---
        function createHearts() {
            const heart = document.createElement('div');
            heart.classList.add('bg-heart');
            heart.innerHTML = '❤️';
            heart.style.left = Math.random() * 100 + 'vw';
            heart.style.animationDuration = Math.random() * 3 + 4 + 's'; // 4-7s
            heart.style.fontSize = Math.random() * 20 + 20 + 'px';
            
            bgContainer.appendChild(heart);

            // Remove after animation
            setTimeout(() => {
                heart.remove();
            }, 7000);
        }

        setInterval(createHearts, 500);


        // --- Confetti Logic (Simple Implementation) ---
        const canvas = document.getElementById('confetti-canvas');
        const ctx = canvas.getContext('2d');
        let particles = [];
        let animationId;

        function resizeCanvas() {
            canvas.width = window.innerWidth;
            canvas.height = window.innerHeight;
        }
        window.addEventListener('resize', resizeCanvas);
        resizeCanvas();

        class Particle {
            constructor() {
                this.x = Math.random() * canvas.width;
                this.y = Math.random() * canvas.height - canvas.height;
                this.size = Math.random() * 10 + 5;
                this.speedY = Math.random() * 3 + 2;
                this.speedX = (Math.random() - 0.5) * 2;
                this.color = `hsl(${Math.random() * 360}, 100%, 70%)`;
                this.rotation = Math.random() * 360;
                this.rotationSpeed = (Math.random() - 0.5) * 10;
            }
            update() {
                this.y += this.speedY;
                this.x += this.speedX;
                this.rotation += this.rotationSpeed;
                if (this.y > canvas.height) {
                    this.y = -20;
                    this.x = Math.random() * canvas.width;
                }
            }
            draw() {
                ctx.save();
                ctx.translate(this.x, this.y);
                ctx.rotate(this.rotation * Math.PI / 180);
                ctx.fillStyle = this.color;
                ctx.fillRect(0, 0, this.size, this.size);
                ctx.restore();
            }
        }

        function startConfetti() {
            for (let i = 0; i < 150; i++) {
                particles.push(new Particle());
            }
            animateConfetti();
        }

        function animateConfetti() {
            ctx.clearRect(0, 0, canvas.width, canvas.height);
            particles.forEach(p => {
                p.update();
                p.draw();
            });
            animationId = requestAnimationFrame(animateConfetti);
        }

    </script>
</body>
</html>
