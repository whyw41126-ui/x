<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Programmed Love - Complete Reveal & Loop</title>
    <style>
        body {
            margin: 0;
            background-color: black;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            overflow: hidden;
            perspective: 1000px;
        }

        .container {
            position: relative;
            transform-style: preserve-3d;
            transform: rotateY(-10deg) rotateX(5deg);
        }

        .i_love_you_word {
            position: absolute;
            font-family: 'Segoe UI', Arial, sans-serif;
            font-size: 14px;
            font-weight: 900;
            white-space: nowrap;
            left: 50%;
            top: 50%;
            transform: translate3d(var(--x), var(--y), 0px);
            opacity: 0; 
        }

        .i_love_you_word.base {
            animation: draw-once 0.8s ease-out forwards;
        }

        .i_love_you_word.glow {
            color: #ffffff;
            text-shadow: 0 0 15px #ff4d6d, 0 0 30px #ff4d6d, 0 0 45px #ff4d6d;
            animation: continuous-glow 4s infinite linear;
        }

        @keyframes draw-once {
            0% {
                opacity: 0;
                color: #ffffff;
                transform: translate3d(var(--x), var(--y), -30px) scale(0.7);
                text-shadow: none;
            }
            50% {
                opacity: 1;
                color: #ffffff;
                text-shadow: 0 0 15px #ff4d6d, 0 0 25px #ff4d6d;
                transform: translate3d(var(--x), var(--y), 10px) scale(1.15);
            }
            100% {
                opacity: 1;
                color: #ff4d6d;
                text-shadow: 0 0 8px #ff4d6d;
                transform: translate3d(var(--x), var(--y), 0px) scale(1);
            }
        }

        @keyframes continuous-glow {
            0% {
                opacity: 0;
                transform: translate3d(var(--x), var(--y), 0px) scale(1);
            }
            4% {
                opacity: 1;
                transform: translate3d(var(--x), var(--y), 12px) scale(1.1);
            }
            8% {
                opacity: 0;
                transform: translate3d(var(--x), var(--y), 0px) scale(1);
            }
            100% {
                opacity: 0;
                transform: translate3d(var(--x), var(--y), 0px) scale(1);
            }
        }
    </style>
</head>
<body>

    <div class="container" id="heart-container"></div>

    <script>
        const container = document.getElementById('heart-container');
        const wordsCount = 80; 
        const introDrawTime = 5; 
        const loopDuration = 4; 

        for (let i = 0; i < wordsCount; i++) {
            const alpha = (i / wordsCount) * 2 * Math.PI;
            
            const rawX = 16 * Math.pow(Math.sin(alpha), 3);
            const rawY = -(13 * Math.cos(alpha) - 5 * Math.cos(2 * alpha) - 2 * Math.cos(3 * alpha) - Math.cos(4 * alpha));

            const finalX = rawX * 16;
            const finalY = rawY * 16;

            const baseDelay = (i / wordsCount) * introDrawTime;
            const glowDelay = (i / wordsCount) * loopDuration;

            const baseWord = document.createElement('div');
            baseWord.className = 'i_love_you_word base';
            baseWord.innerText = 'I love you';
            baseWord.style.setProperty('--x', `${finalX}px`);
            baseWord.style.setProperty('--y', `${finalY}px`);
            baseWord.style.animationDelay = `${baseDelay}s`;
            container.appendChild(baseWord);

            const glowWord = document.createElement('div');
            glowWord.className = 'i_love_you_word glow';
            glowWord.innerText = 'I love you';
            glowWord.style.setProperty('--x', `${finalX}px`);
            glowWord.style.setProperty('--y', `${finalY}px`);
            glowWord.style.animationDelay = `${introDrawTime + glowDelay}s`;
            container.appendChild(glowWord);
        }
    </script>
</body>
</html>
