---
title: Organization Chart
permalink: /our-story/organization-chart/
variant: markdown
description: ""
image: /images/YCKLogo.svg
third_nav_title: Our Staff
---
<div class="yck-component">
    <div class="bg-decoration">✨</div>
    <div class="bg-decoration">🌟</div>
    <div class="bg-decoration">💫</div>
    <div class="bg-decoration">⭐</div>
    <div class="bg-decoration">🔮</div>
    <div class="redirect-container">
        <div class="corner-decoration">✨</div>
        <div class="corner-decoration">🌟</div>
        <div class="corner-decoration">💫</div>
        <div class="corner-decoration">⭐</div>
        <div class="magic-icon">🚀</div>
        <h1>Magical Journey</h1>
        <p class="subtitle">
            Looking for the Organization Chart?.<br>
            Well ... It's now here ... <a href="https://staging-lite.d3o5f2eggdqz6.amplifyapp.com/our-family/our-staff/organisation-chart/">Organisation Chart</a>
        </p>
        <div class="progress-container">
            <div class="progress-bar"></div>
        </div>
        <div class="loading-dots">
            <div class="dot"></div>
            <div class="dot"></div>
            <div class="dot"></div>
        </div>
        <div class="countdown">
            Redirecting in 5 seconds...
        </div>
    </div>
</div>

<style>
body  {
    font-family: 'SF Pro Display', -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif;
    background: linear-gradient(135deg, #667eea 0%, #764ba2 50%, #f093fb 100%) !important;
    background-size: 400% 400%;
    min-height: 100vh;
    display: flex;
    align-items: center;
    justify-content: center;
    overflow: hidden;
    position: relative;
    animation: gradientShift 8s ease infinite;
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

@keyframes gradientShift {
    0% {
        background-position: 0% 50%;
    }

    50% {
        background-position: 100% 50%;
    }

    100% {
        background-position: 0% 50%;
    }
}

/* Floating background elements */
body .bg-decoration {
    position: absolute;
    opacity: 0.1;
    animation: float 6s ease-in-out infinite;
    pointer-events: none;
}

body .bg-decoration:nth-child(1) {
    top: 10%;
    left: 10%;
    font-size: 4rem;
    animation-delay: 0s;
}

body .bg-decoration:nth-child(2) {
    top: 20%;
    right: 15%;
    font-size: 3rem;
    animation-delay: -2s;
}

body .bg-decoration:nth-child(3) {
    bottom: 20%;
    left: 20%;
    font-size: 5rem;
    animation-delay: -4s;
}

body .bg-decoration:nth-child(4) {
    bottom: 30%;
    right: 10%;
    font-size: 3.5rem;
    animation-delay: -1s;
}

body .bg-decoration:nth-child(5) {
    top: 50%;
    left: 5%;
    font-size: 2.5rem;
    animation-delay: -3s;
}

@keyframes float {

    0%,
    100% {
        transform: translateY(0px) rotate(0deg);
    }

    33% {
        transform: translateY(-30px) rotate(120deg);
    }

    66% {
        transform: translateY(30px) rotate(240deg);
    }
}

/* Main container */
body .redirect-container {
    text-align: center;
    color: white;
    z-index: 10;
    max-width: 600px;
    padding: 60px 40px;
    background: rgba(255, 255, 255, 0.15);
    backdrop-filter: blur(20px);
    border-radius: 30px;
    border: 2px solid rgba(255, 255, 255, 0.3);
    box-shadow:
        0 20px 40px rgba(0, 0, 0, 0.1),
        inset 0 1px 0 rgba(255, 255, 255, 0.2);
    animation: slideUp 1s ease-out, pulse 3s ease-in-out infinite 2s;
    position: relative;
}

@keyframes slideUp {
    from {
        opacity: 0;
        transform: translateY(50px) scale(0.9);
    }

    to {
        opacity: 1;
        transform: translateY(0) scale(1);
    }
}

@keyframes pulse {

    0%,
    100% {
        transform: scale(1);
        box-shadow:
            0 20px 40px rgba(0, 0, 0, 0.1),
            inset 0 1px 0 rgba(255, 255, 255, 0.2);
    }

    50% {
        transform: scale(1.02);
        box-shadow:
            0 25px 50px rgba(0, 0, 0, 0.15),
            inset 0 1px 0 rgba(255, 255, 255, 0.3);
    }
}

/* Magical icon */
body .magic-icon {
    font-size: 5rem;
    margin-bottom: 2rem;
    display: inline-block;
    animation: bounce 2s infinite, rotate 8s linear infinite;
}

@keyframes bounce {

    0%,
    20%,
    50%,
    80%,
    100% {
        transform: translateY(0) rotate(var(--rotation, 0deg));
    }

    40% {
        transform: translateY(-25px) rotate(var(--rotation, 0deg));
    }

    60% {
        transform: translateY(-15px) rotate(var(--rotation, 0deg));
    }
}

@keyframes rotate {
    from {
        --rotation: 0deg;
    }

    to {
        --rotation: 360deg;
    }
}

body h1 {
    font-size: 3.5rem;
    font-weight: 800;
    margin-bottom: 1.5rem;
    background: linear-gradient(135deg, #fff 0%, #f0f0f0 50%, #fff 100%);
    background-size: 200% 200%;
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
    background-clip: text;
    animation: shimmer 3s ease-in-out infinite;
    text-shadow: 0 0 30px rgba(255, 255, 255, 0.5);
}

@keyframes shimmer {

    0%,
    100% {
        background-position: 0% 50%;
    }

    50% {
        background-position: 100% 50%;
    }
}

body .subtitle {
    font-size: 1.3rem;
    margin-bottom: 3rem;
    opacity: 0.95;
    line-height: 1.6;
    animation: fadeInUp 1s ease-out 0.5s both;
}

@keyframes fadeInUp {
    from {
        opacity: 0;
        transform: translateY(20px);
    }

    to {
        opacity: 0.95;
        transform: translateY(0);
    }
}

/* Progress bar */
.yck-component .progress-container {
    width: 100%;
    height: 12px;
    background: rgba(255, 255, 255, 0.2);
    border-radius: 6px;
    overflow: hidden;
    margin-bottom: 2rem;
    position: relative;
    animation: fadeInUp 1s ease-out 1s both;
}

body .progress-bar {
    height: 100%;
    background: linear-gradient(90deg,
        #00f5ff 0%,
        #00d4ff 25%,
        #0099ff 50%,
        #00d4ff 75%,
        #00f5ff 100%);
    background-size: 200% 100%;
    border-radius: 6px;
    animation:
        loading 5s ease-in-out forwards,
        shimmerBar 2s linear infinite;
    box-shadow:
        0 0 20px rgba(0, 149, 255, 0.6),
        inset 0 1px 0 rgba(255, 255, 255, 0.3);
}

@keyframes loading {
    0% {
        width: 0%;
    }

    100% {
        width: 100%;
    }
}

@keyframes shimmerBar {
    0% {
        background-position: -200% 0;
    }

    100% {
        background-position: 200% 0;
    }
}

/* Loading dots */
body .loading-dots {
    display: flex;
    justify-content: center;
    gap: 12px;
    margin-top: 1.5rem;
    animation: fadeInUp 1s ease-out 1.5s both;
}

body .dot {
    width: 16px;
    height: 16px;
    background: linear-gradient(135deg, #fff, #e0e0e0);
    border-radius: 50%;
    animation: pulseDot 1.8s infinite ease-in-out;
    box-shadow: 0 0 15px rgba(255, 255, 255, 0.4);
}

body .dot:nth-child(1) {
    animation-delay: 0s;
}

body .dot:nth-child(2) {
    animation-delay: 0.3s;
}

body .dot:nth-child(3) {
    animation-delay: 0.6s;
}

@keyframes pulseDot {

    0%,
    100% {
        opacity: 0.4;
        transform: scale(1);
    }

    50% {
        opacity: 1;
        transform: scale(1.3);
    }
}

/* Countdown */
body .countdown {
    font-size: 1.1rem;
    margin-top: 2rem;
    opacity: 0.8;
    animation:
        fadeInUp 1s ease-out 2s both,
        countdownPulse 1s ease-in-out infinite 3s;
}

@keyframes countdownPulse {

    0%,
    100% {
        opacity: 0.8;
    }

    50% {
        opacity: 1;
        transform: scale(1.05);
    }
}

/* Corner decorations */
body .corner-decoration {
    position: absolute;
    font-size: 2rem;
    opacity: 0.3;
    animation: twinkle 2s ease-in-out infinite;
}

body .corner-decoration:nth-child(1) {
    top: -10px;
    left: -10px;
    animation-delay: 0s;
}

body .corner-decoration:nth-child(2) {
    top: -10px;
    right: -10px;
    animation-delay: 0.5s;
}

body .corner-decoration:nth-child(3) {
    bottom: -10px;
    left: -10px;
    animation-delay: 1s;
}

body .corner-decoration:nth-child(4) {
    bottom: -10px;
    right: -10px;
    animation-delay: 1.5s;
}

@keyframes twinkle {

    0%,
    100% {
        opacity: 0.3;
        transform: scale(1);
    }

    50% {
        opacity: 0.8;
        transform: scale(1.2);
    }
}

/* Responsive design */
@media (max-width: 768px) {
body .redirect-container {
        margin: 20px;
        padding: 40px 30px;
    }

body h1 {
        font-size: 2.8rem;
    }

body .magic-icon {
        font-size: 4rem;
    }

body .subtitle {
        font-size: 1.1rem;
    }
}

@media (max-width: 480px) {
body .redirect-container {
        padding: 30px 20px;
    }

body h1 {
        font-size: 2.2rem;
    }

body .magic-icon {
        font-size: 3.5rem;
    }
}
</style>