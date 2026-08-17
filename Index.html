<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no, viewport-fit=cover">
<meta name="theme-color" content="#fff0f6">

<meta name="apple-mobile-web-app-capable" content="yes">
<meta name="apple-mobile-web-app-status-bar-style" content="black-translucent">
<meta name="mobile-web-app-capable" content="yes">
<meta name="screen-orientation" content="portrait">

<title>Happy Birthday Jyoti ✨</title>

<style>
/* =========================================================
   GLOBAL RESET & FULLSCREEN RESPONSIVE BASE
========================================================= */
*, *::before, *::after {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    -webkit-tap-highlight-color: transparent;
    user-select: none;
    -webkit-user-select: none;
}

html, body {
    width: 100%;
    height: 100%;
    overflow: hidden;
    font-family: "Segoe UI", Roboto, -apple-system, BlinkMacSystemFont, sans-serif;
    background: radial-gradient(circle at 10% 10%, #ffe4f0 0%, transparent 40%),
                radial-gradient(circle at 90% 15%, #e8dcff 0%, transparent 40%),
                radial-gradient(circle at 50% 90%, #fff1d6 0%, transparent 45%),
                linear-gradient(135deg, #fff5fa 0%, #fbf4ff 50%, #fffaf2 100%);
    color: #4a364d;
}

.app {
    width: 100%;
    height: 100vh;
    height: 100dvh;
    position: relative;
    display: flex;
    flex-direction: column;
    overflow: hidden;
}

#confettiCanvas {
    position: fixed;
    top: 0;
    left: 0;
    width: 100vw;
    height: 100vh;
    pointer-events: none !important;
    z-index: 9998;
}

/* Ambient Floating Glow Blobs */
.ambient-bg {
    position: absolute;
    inset: 0;
    overflow: hidden;
    pointer-events: none !important;
    z-index: 0;
}

.ambient-blob {
    position: absolute;
    border-radius: 50%;
    filter: blur(clamp(35px, 7vw, 60px));
    opacity: 0.6;
    pointer-events: none !important;
    animation: blobFloat 9s ease-in-out infinite alternate;
}

.ambient-blob.b1 { width: clamp(180px, 30vw, 320px); height: clamp(180px, 30vw, 320px); background: #ffc2df; top: -10%; left: -10%; }
.ambient-blob.b2 { width: clamp(200px, 32vw, 340px); height: clamp(200px, 32vw, 340px); background: #dbc7ff; right: -10%; top: 15%; animation-delay: -3s; }
.ambient-blob.b3 { width: clamp(160px, 26vw, 280px); height: clamp(160px, 26vw, 280px); background: #ffe19e; bottom: -10%; left: 10%; animation-delay: -5s; }
.ambient-blob.b4 { width: clamp(150px, 24vw, 260px); height: clamp(150px, 24vw, 260px); background: #c7f8df; bottom: 8%; right: 4%; animation-delay: -7s; }

@keyframes blobFloat {
    0% { transform: translateY(0) scale(1); }
    100% { transform: translateY(clamp(15px, 3vh, 30px)) scale(1.08); }
}

.decor-icon {
    position: absolute;
    pointer-events: none !important;
    opacity: 0.5;
    font-size: clamp(16px, 3vw, 24px);
    animation: decorFloat 4.5s ease-in-out infinite alternate;
    z-index: 1;
}
.di1 { left: 6%; top: 8%; animation-delay: 0s; }
.di2 { right: 8%; top: 12%; animation-delay: 1.2s; }
.di3 { left: 8%; bottom: 14%; animation-delay: 2.2s; }
.di4 { right: 6%; bottom: 10%; animation-delay: 1.8s; }

@keyframes decorFloat {
    0% { transform: translateY(0) rotate(0deg); }
    100% { transform: translateY(-14px) rotate(14deg); }
}

/* Floating Top Controls */
.top-controls {
    position: absolute;
    top: max(10px, env(safe-area-inset-top));
    right: max(12px, env(safe-area-inset-right));
    z-index: 9999;
    display: flex;
    gap: 8px;
}

.control-btn {
    width: clamp(34px, 8vw, 40px);
    height: clamp(34px, 8vw, 40px);
    border-radius: 50%;
    background: rgba(255, 255, 255, 0.92);
    border: 1px solid rgba(240, 140, 180, 0.4);
    box-shadow: 0 4px 12px rgba(180, 100, 140, 0.18);
    font-size: clamp(13px, 3.5vw, 16px);
    display: flex;
    align-items: center;
    justify-content: center;
    cursor: pointer;
    backdrop-filter: blur(10px);
    transition: transform 0.2s;
}
.control-btn:active { transform: scale(0.9); }

/* =========================================================
   PAGE CONTAINER & ROUTER
========================================================= */
.pages {
    position: relative;
    z-index: 2;
    flex: 1;
    width: 100%;
    height: 100%;
    overflow: hidden;
    touch-action: pan-y;
}

.page {
    position: absolute;
    inset: 0;
    width: 100%;
    height: 100%;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    text-align: center;
    padding: max(15px, env(safe-area-inset-top)) max(14px, env(safe-area-inset-right)) max(75px, calc(env(safe-area-inset-bottom) + 65px)) max(14px, env(safe-area-inset-left));
    opacity: 0;
    visibility: hidden;
    transform: translateX(60px) scale(0.95);
    pointer-events: none !important;
    transition: opacity 0.45s cubic-bezier(0.2, 0.8, 0.2, 1), transform 0.45s cubic-bezier(0.2, 0.8, 0.2, 1), visibility 0.45s;
    overflow-y: auto;
    scrollbar-width: none;
}
.page::-webkit-scrollbar { display: none; }

.page.active {
    opacity: 1;
    visibility: visible;
    transform: translateX(0) scale(1);
    pointer-events: auto !important;
}

.page.prev-exit {
    transform: translateX(-60px) scale(0.95);
    opacity: 0;
    visibility: hidden;
    pointer-events: none !important;
}

/* Typography & Badges */
.page-badge {
    display: inline-flex;
    align-items: center;
    justify-content: center;
    height: clamp(26px, 4.5vh, 32px);
    padding: 0 clamp(10px, 3vw, 16px);
    margin-bottom: clamp(4px, 1.2vh, 8px);
    border-radius: 50px;
    background: #fff0f7;
    border: 1px solid rgba(240, 140, 180, 0.3);
    color: #b82b6b;
    font-size: clamp(10px, 2.6vw, 12.5px);
    font-weight: 800;
    box-shadow: 0 4px 12px rgba(220, 100, 150, 0.12);
    pointer-events: none;
}

.page-title {
    font-family: "Brush Script MT", "Segoe Script", cursive;
    font-size: clamp(26px, 6.2vw, 44px);
    line-height: 1.15;
    font-weight: 700;
    color: #a8235c;
    text-shadow: 0 4px 14px rgba(185, 78, 123, 0.18);
    margin-bottom: clamp(2px, 0.8vh, 5px);
    pointer-events: none;
}

.page-subtitle {
    font-size: clamp(11px, 2.5vw, 13.5px);
    color: #6d5569;
    font-weight: 700;
    letter-spacing: 0.3px;
    margin-bottom: clamp(4px, 1.2vh, 10px);
    pointer-events: none;
}

.cute-btn {
    border: none;
    outline: none;
    padding: clamp(9px, 2.2vh, 13px) clamp(22px, 5vw, 34px);
    border-radius: 50px;
    background: linear-gradient(135deg, #f43f85 0%, #d946ef 50%, #8b5cf6 100%);
    color: white;
    font-size: clamp(12.5px, 3vw, 15.5px);
    font-weight: 800;
    cursor: pointer;
    box-shadow: 0 8px 22px rgba(217, 70, 239, 0.35);
    transition: transform 0.2s cubic-bezier(0.34, 1.56, 0.64, 1), box-shadow 0.2s ease;
    pointer-events: auto !important;
}
.cute-btn:active { transform: scale(0.94); }

/* Floating Navigation Bar */
.navigation {
    position: absolute;
    z-index: 1000;
    left: 0;
    right: 0;
    bottom: 0;
    width: 100%;
    padding: 8px 16px max(10px, env(safe-area-inset-bottom));
    display: flex;
    align-items: center;
    justify-content: center;
    gap: clamp(8px, 2.5vw, 16px);
    background: rgba(255, 255, 255, 0.9);
    border-top: 1px solid rgba(255, 255, 255, 0.95);
    backdrop-filter: blur(16px);
    -webkit-backdrop-filter: blur(16px);
}

.nav-button {
    width: clamp(36px, 7.5vw, 42px);
    height: clamp(36px, 7.5vw, 42px);
    border: none;
    border-radius: 50%;
    background: #fff;
    color: #b82b6b;
    font-size: clamp(17px, 4vw, 22px);
    display: flex;
    align-items: center;
    justify-content: center;
    cursor: pointer;
    box-shadow: 0 4px 14px rgba(160, 110, 150, 0.18);
    transition: transform 0.2s ease, background 0.2s ease;
}
.nav-button:hover { background: #fff0f7; }
.nav-button:disabled { opacity: 0.3; cursor: not-allowed; }

.dots { display: flex; align-items: center; justify-content: center; gap: clamp(4px, 1.2vw, 8px); }
.dot {
    width: clamp(6px, 1.5vw, 8px);
    height: clamp(6px, 1.5vw, 8px);
    border: none;
    border-radius: 50%;
    background: #d9c9dd;
    cursor: pointer;
    transition: all 0.3s cubic-bezier(0.2, 0.8, 0.2, 1);
}
.dot.active {
    width: clamp(18px, 4.5vw, 24px);
    border-radius: 20px;
    background: linear-gradient(90deg, #f43f85, #8b5cf6);
}

/* =========================================================
   PAGE 1: 3D CARD TILT & SHIMMER EFFECT
========================================================= */
.p1-wrap {
    width: min(94vw, 440px);
    margin: auto 0;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    position: relative;
    z-index: 5;
    perspective: 1000px;
}

.p1-hero-card {
    position: relative;
    width: 100%;
    padding: clamp(18px, 3.5vh, 32px) clamp(14px, 3.5vw, 22px);
    border-radius: clamp(22px, 4.5vw, 32px);
    background: rgba(255, 255, 255, 0.9);
    border: 2px solid rgba(255, 255, 255, 0.95);
    box-shadow: 0 20px 50px rgba(200, 110, 160, 0.22);
    backdrop-filter: blur(20px);
    display: flex;
    flex-direction: column;
    align-items: center;
    overflow: hidden;
    transition: transform 0.3s cubic-bezier(0.2, 0.8, 0.2, 1);
}

.p1-avatar-box {
    position: relative;
    width: clamp(70px, 16vw, 95px);
    height: clamp(70px, 16vw, 95px);
    margin: clamp(2px, 0.8vh, 6px) 0 clamp(6px, 1.8vh, 12px);
    display: flex;
    align-items: center;
    justify-content: center;
    pointer-events: none;
}

.p1-avatar-aura {
    position: absolute;
    inset: -4px;
    border-radius: 50%;
    background: linear-gradient(135deg, #ff80b0, #c084fc, #60a5fa);
    filter: blur(8px);
    opacity: 0.75;
    animation: p1AuraPulse 2.8s infinite alternate ease-in-out;
}
@keyframes p1AuraPulse {
    0% { transform: scale(0.92); opacity: 0.55; }
    100% { transform: scale(1.1); opacity: 0.9; }
}

.p1-avatar-circle {
    position: relative;
    width: 100%;
    height: 100%;
    border-radius: 50%;
    background: linear-gradient(135deg, #ffffff 0%, #ffe4f0 100%);
    border: 3px solid rgba(255, 255, 255, 0.95);
    display: flex;
    align-items: center;
    justify-content: center;
    font-size: clamp(32px, 7.5vw, 44px);
    box-shadow: 0 10px 20px rgba(180, 70, 120, 0.2);
    animation: p1AvatarBob 3s ease-in-out infinite alternate;
}
@keyframes p1AvatarBob {
    0% { transform: translateY(0) rotate(0deg); }
    100% { transform: translateY(-6px) rotate(4deg); }
}

.p1-floating-tag {
    position: absolute;
    display: inline-flex;
    align-items: center;
    padding: clamp(3px, 0.8vh, 5px) clamp(6px, 1.8vw, 10px);
    border-radius: 50px;
    background: rgba(255, 255, 255, 0.95);
    border: 1px solid rgba(244, 114, 182, 0.35);
    box-shadow: 0 6px 14px rgba(160, 50, 100, 0.12);
    font-size: clamp(8.5px, 2.2vw, 10.5px);
    font-weight: 800;
    color: #9d174d;
    white-space: nowrap;
    pointer-events: none;
    animation: p1TagFloat 3.5s ease-in-out infinite alternate;
}
.p1-tag-left { left: 4%; top: 8%; animation-delay: 0s; }
.p1-tag-right { right: 4%; top: 12%; animation-delay: 1.5s; }

@keyframes p1TagFloat {
    0% { transform: translateY(0) rotate(-2deg); }
    100% { transform: translateY(-8px) rotate(2deg); }
}

.p1-title-gradient {
    font-family: "Brush Script MT", "Segoe Script", cursive;
    font-size: clamp(28px, 7vw, 46px);
    font-weight: 800;
    line-height: 1.15;
    background: linear-gradient(90deg, #e11d48 0%, #c026d3 50%, #7c3aed 100%);
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
    pointer-events: none;
}

.p1-desc {
    font-size: clamp(11.5px, 3vw, 14.5px);
    line-height: 1.55;
    color: #5c4558;
    font-weight: 600;
    margin: clamp(4px, 1.2vh, 10px) 0 clamp(10px, 2vh, 18px);
    text-align: center;
    pointer-events: none;
}

.p1-start-btn {
    position: relative;
    overflow: hidden;
    pointer-events: auto !important;
}
.p1-start-btn::after {
    content: "";
    position: absolute;
    top: 0; left: -100%;
    width: 60%; height: 100%;
    background: linear-gradient(90deg, transparent, rgba(255,255,255,0.45), transparent);
    transform: skewX(-25deg);
    animation: p1BtnShine 3.2s infinite ease-in-out;
}
@keyframes p1BtnShine {
    0%, 60% { left: -100%; }
    100% { left: 200%; }
}

/* =========================================================
   PAGE 2: CANDLE CAKE & DYNAMIC WARM LIGHTING
========================================================= */
.p2-container {
    width: 100%;
    max-width: 420px;
    margin: auto 0;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    position: relative;
}

.p2-cake-wrap {
    width: clamp(210px, 58vw, 270px);
    height: clamp(190px, 30vh, 245px);
    position: relative;
    display: flex;
    align-items: flex-end;
    justify-content: center;
    margin: clamp(2px, 0.8vh, 6px) 0 clamp(6px, 1.6vh, 14px);
    pointer-events: auto;
}

.p2-glow {
    position: absolute;
    width: clamp(130px, 38vw, 180px);
    height: clamp(130px, 38vw, 180px);
    top: 5px;
    left: 50%;
    transform: translateX(-50%);
    border-radius: 50%;
    background: radial-gradient(circle, rgba(255, 215, 80, 0.4), transparent 70%);
    filter: blur(14px);
    animation: p2Pulse 1s infinite alternate ease-in-out;
    pointer-events: none;
}
@keyframes p2Pulse { from { transform: translateX(-50%) scale(0.9); opacity: 0.6; } to { transform: translateX(-50%) scale(1.15); opacity: 1; } }

.p2-cake {
    position: relative;
    width: clamp(150px, 42vw, 190px);
    height: clamp(125px, 20vh, 160px);
    margin-bottom: clamp(14px, 2.5vh, 22px);
    transform-origin: center bottom;
    pointer-events: none;
}

.p2-lower {
    position: absolute;
    bottom: 0;
    width: 100%;
    height: 48%;
    border-radius: 12px 12px 22px 22px;
    background: linear-gradient(90deg, #b85d43, #e59a73 40%, #c56a4b);
    box-shadow: inset 0 6px 10px rgba(255,255,255,0.2), 0 8px 16px rgba(90,45,40,0.2);
}

.p2-upper {
    position: absolute;
    bottom: 42%;
    width: 100%;
    height: 38%;
    border-radius: 50% 50% 16px 16px;
    background: linear-gradient(90deg, #cf7654, #eba079 40%, #bb5d43);
}

.p2-cream-top {
    position: absolute;
    bottom: 60%;
    left: 50%;
    transform: translateX(-50%);
    width: 103%;
    height: 28%;
    border-radius: 50%;
    background: radial-gradient(ellipse, #ffffff 40%, #ffe4ee 100%);
    box-shadow: 0 4px 10px rgba(180,120,140,0.2);
    z-index: 5;
}

.p2-drip {
    position: absolute;
    background: #ffffff;
    border-radius: 0 0 16px 16px;
    z-index: 6;
}
.p2-d1 { width: 11%; height: 20%; left: 18%; bottom: 50%; }
.p2-d2 { width: 13%; height: 28%; left: 44%; bottom: 46%; }
.p2-d3 { width: 11%; height: 18%; right: 18%; bottom: 52%; }

.p2-candle {
    position: absolute;
    bottom: 80%;
    left: 50%;
    transform: translateX(-50%);
    width: clamp(13px, 3.2vw, 17px);
    height: clamp(40px, 7.5vh, 55px);
    border-radius: 5px;
    background: repeating-linear-gradient(-45deg, #ffffff 0px, #ffffff 6px, #f39abc 6px, #f39abc 12px);
    box-shadow: 0 4px 8px rgba(80,50,60,0.2);
    z-index: 10;
}

.p2-wick-rope {
    position: absolute;
    top: -12px;
    left: 50%;
    transform: translateX(-50%);
    width: 3.5px;
    height: 14px;
    border-radius: 2px;
    background: linear-gradient(to top, #36292b 0%, #1f1416 70%, #ff5e3a 100%);
    z-index: 12;
}

.p2-flame {
    position: absolute;
    top: -40px;
    left: 50%;
    transform: translateX(-50%);
    width: clamp(16px, 4vw, 22px);
    height: clamp(26px, 4.8vh, 36px);
    border-radius: 50% 50% 45% 45%;
    background: radial-gradient(ellipse at 50% 75%, #ffffff 0%, #fff799 25%, #ffd000 50%, #ff5100 85%);
    box-shadow: 0 0 12px #ffe600, 0 0 25px #ff7b00;
    animation: p2Flicker 0.15s infinite alternate;
    transition: opacity 0.3s ease, transform 0.3s ease;
    z-index: 14;
}
@keyframes p2Flicker {
    0% { transform: translateX(-50%) rotate(-3deg) scale(1); }
    100% { transform: translateX(-50%) rotate(3deg) scale(1.06, 0.95); }
}

.p2-smoke-box {
    position: absolute;
    top: -16px;
    left: 50%;
    transform: translateX(-50%);
    width: 1px;
    height: 1px;
    pointer-events: none;
    z-index: 15;
}

.p2-smoke-puff {
    position: absolute;
    border-radius: 50%;
    background: radial-gradient(circle, rgba(175, 175, 175, 0.75) 0%, rgba(210, 210, 210, 0.35) 55%, transparent 75%);
    opacity: 0;
}

.blown .p2-smoke-puff.sm1 { width: 18px; height: 18px; animation: smokeFloat1 2.5s cubic-bezier(0.1, 0.6, 0.3, 1) forwards; }
.blown .p2-smoke-puff.sm2 { width: 24px; height: 24px; animation: smokeFloat2 2.8s 0.2s cubic-bezier(0.1, 0.6, 0.3, 1) forwards; }
.blown .p2-smoke-puff.sm3 { width: 32px; height: 32px; animation: smokeFloat3 3.2s 0.45s cubic-bezier(0.1, 0.6, 0.3, 1) forwards; }

@keyframes smokeFloat1 {
    0% { opacity: 0.85; transform: translate(-50%, 0) scale(0.4); }
    40% { opacity: 0.5; transform: translate(calc(-50% + 12px), -35px) scale(1.4); }
    100% { opacity: 0; transform: translate(calc(-50% - 15px), -80px) scale(2.8); }
}
@keyframes smokeFloat2 {
    0% { opacity: 0.8; transform: translate(-50%, 0) scale(0.5); }
    40% { opacity: 0.45; transform: translate(calc(-50% - 14px), -45px) scale(1.6); }
    100% { opacity: 0; transform: translate(calc(-50% + 20px), -100px) scale(3.2); }
}
@keyframes smokeFloat3 {
    0% { opacity: 0.75; transform: translate(-50%, 0) scale(0.5); }
    50% { opacity: 0.35; transform: translate(calc(-50% + 16px), -55px) scale(2); }
    100% { opacity: 0; transform: translate(calc(-50% - 10px), -125px) scale(4); }
}

.p2-plate {
    position: absolute;
    bottom: 8px;
    width: clamp(170px, 48vw, 220px);
    height: clamp(18px, 3.8vh, 26px);
    border-radius: 50%;
    background: linear-gradient(to bottom, #ffffff, #dcdce2);
    box-shadow: 0 8px 18px rgba(80,60,70,0.18);
    pointer-events: none;
}

.blown .p2-flame { opacity: 0; transform: translateX(-50%) scale(0.05); }
.blown .p2-glow { opacity: 0; }

.p2-action-area {
    min-height: 65px;
    width: 100%;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    position: relative;
    z-index: 10;
}

.p2-wish-card {
    background: rgba(255, 255, 255, 0.94);
    padding: clamp(8px, 1.8vh, 12px) clamp(14px, 3.5vw, 22px);
    border-radius: 20px;
    border: 2px solid rgba(240, 110, 160, 0.35);
    box-shadow: 0 10px 28px rgba(180, 100, 140, 0.18);
    color: #9d174d;
    font-size: clamp(12px, 3vw, 14.5px);
    font-weight: 800;
    line-height: 1.5;
    opacity: 0;
    transform: translateY(12px) scale(0.92);
    transition: opacity 0.45s cubic-bezier(0.2, 0.8, 0.2, 1), transform 0.45s cubic-bezier(0.2, 0.8, 0.2, 1);
    display: none;
    pointer-events: none;
}
.p2-wish-card.show {
    display: block;
    opacity: 1;
    transform: translateY(0) scale(1);
}

/* =========================================================
   PAGE 3: 3D TEDDY & SPRING UNBOXING
========================================================= */
.p3-scene {
    width: min(92vw, 360px);
    height: clamp(210px, 34vh, 265px);
    position: relative;
    margin: 2px 0 clamp(4px, 1.2vh, 10px);
    pointer-events: auto;
}

.p3-balloon {
    position: absolute;
    width: clamp(36px, 8.5vw, 46px);
    height: clamp(46px, 10.5vw, 58px);
    border-radius: 50% 50% 48% 48%;
    cursor: pointer;
    z-index: 12;
    box-shadow: inset -7px -9px 15px rgba(0,0,0,0.18), inset 8px 8px 12px rgba(255,255,255,0.4), 0 8px 18px rgba(90,60,80,0.2);
    transform-origin: center bottom;
    pointer-events: auto !important;
}
.p3-balloon .p3-b-shine {
    position: absolute;
    width: 25%;
    height: 38%;
    left: 20%;
    top: 15%;
    border-radius: 50%;
    background: linear-gradient(135deg, rgba(255,255,255,0.95), transparent 70%);
    transform: rotate(25deg);
    pointer-events: none;
}
.p3-balloon::before {
    content: "";
    position: absolute;
    bottom: -4px;
    left: 50%;
    transform: translateX(-50%);
    width: 8px;
    height: 5px;
    background: inherit;
    border-radius: 2px 2px 4px 4px;
    pointer-events: none;
}
.p3-balloon::after {
    content: "";
    position: absolute;
    width: 1px;
    height: 50px;
    background: rgba(140, 140, 140, 0.6);
    left: 50%;
    top: 100%;
    pointer-events: none;
}

.p3-b1 { left: 6%; top: 10%; background: radial-gradient(circle at 35% 25%, #ffb8d0 0%, #ed5c91 80%); animation: p3Float 3.2s infinite ease-in-out; }
.p3-b2 { right: 6%; top: 6%; background: radial-gradient(circle at 35% 25%, #c8eeff 0%, #4facfe 80%); animation: p3Float 3.6s 0.5s infinite ease-in-out; }
.p3-b3 { left: 24%; top: 0%; background: radial-gradient(circle at 35% 25%, #ebd7ff 0%, #9a66ea 80%); animation: p3Float 3.4s 1s infinite ease-in-out; }

@keyframes p3Float { 0%, 100% { transform: translateY(0) rotate(-3deg); } 50% { transform: translateY(-8px) rotate(4deg); } }

.p3-balloon.popped {
    animation: pPopAnim 0.3s ease-out forwards;
    pointer-events: none !important;
}
@keyframes pPopAnim {
    0% { transform: scale(1); opacity: 1; }
    50% { transform: scale(1.4); opacity: 0.8; }
    100% { transform: scale(1.8); opacity: 0; }
}

.p3-gift {
    position: absolute;
    width: clamp(110px, 30vw, 138px);
    height: clamp(88px, 22vw, 110px);
    left: 50%;
    bottom: 8px;
    transform: translateX(-50%);
    z-index: 10;
    pointer-events: none;
}
.p3-box-body {
    position: absolute;
    width: 100%;
    height: 80%;
    bottom: 0;
    border-radius: 8px;
    background: linear-gradient(90deg, #ff78a9, #ff9fc1 50%, #ed6699);
    box-shadow: 0 12px 24px rgba(180,70,120,0.22);
}
.p3-box-body::after {
    content: "";
    position: absolute;
    width: clamp(15px, 3.8vw, 20px);
    height: 100%;
    left: 50%;
    transform: translateX(-50%);
    background: linear-gradient(90deg, #ffd66e, #ffe8a4, #f6c451);
}

.p3-lid {
    position: absolute;
    width: calc(100% + 12px);
    height: clamp(20px, 4.5vw, 26px);
    left: 50%;
    top: 4px;
    transform: translateX(-50%);
    border-radius: 6px;
    background: linear-gradient(90deg, #ff75a7, #ffb0cb, #ed6598);
    box-shadow: 0 5px 12px rgba(160, 60, 100, 0.25);
    z-index: 20;
    transition: transform 1s cubic-bezier(0.2, 0.8, 0.2, 1), opacity 0.8s;
}
.p3-lid::after {
    content: "";
    position: absolute;
    width: clamp(15px, 3.8vw, 20px);
    height: 100%;
    left: 50%;
    transform: translateX(-50%);
    background: #ffd66e;
}

.p3-teddy {
    position: absolute;
    width: clamp(65px, 16vw, 80px);
    height: clamp(80px, 20vw, 98px);
    left: 50%;
    bottom: 22px;
    transform: translateX(-50%) translateY(75px) scale(0.4);
    opacity: 0;
    z-index: 7;
    transition: transform 1.2s cubic-bezier(0.34, 1.56, 0.64, 1), opacity 0.5s ease;
    pointer-events: none;
}

.p3-teddy-ear {
    position: absolute;
    width: 22px;
    height: 22px;
    border-radius: 50%;
    background: #bd7c5a;
    top: 2px;
}
.p3-teddy-ear.left { left: 4px; }
.p3-teddy-ear.right { right: 4px; }
.p3-teddy-ear::after {
    content: "";
    position: absolute;
    inset: 4px;
    border-radius: 50%;
    background: #e8ad92;
}

.p3-teddy-head {
    position: absolute;
    width: 54px;
    height: 50px;
    left: 50%;
    top: 8px;
    transform: translateX(-50%);
    border-radius: 50%;
    background: radial-gradient(circle at 35% 30%, #e0a382 0%, #b87352 100%);
    box-shadow: 0 4px 10px rgba(90, 45, 30, 0.2);
    z-index: 2;
}

.p3-teddy-eye {
    position: absolute;
    width: 5px;
    height: 7px;
    border-radius: 50%;
    background: #2b1713;
    top: 20px;
}
.p3-teddy-eye.left { left: 15px; }
.p3-teddy-eye.right { right: 15px; }
.p3-teddy-eye::after { content: ""; position: absolute; width: 2px; height: 2px; background: #fff; border-radius: 50%; top: 1px; left: 1px; }

.p3-teddy-muzzle {
    position: absolute;
    width: 22px;
    height: 16px;
    border-radius: 50%;
    background: #f2c7b3;
    left: 50%;
    bottom: 6px;
    transform: translateX(-50%);
}
.p3-teddy-nose {
    position: absolute;
    width: 6px;
    height: 4px;
    border-radius: 50%;
    background: #422019;
    left: 50%;
    top: 3px;
    transform: translateX(-50%);
}

.p3-teddy-body {
    position: absolute;
    width: 48px;
    height: 42px;
    left: 50%;
    bottom: 0;
    transform: translateX(-50%);
    border-radius: 45% 45% 35% 35%;
    background: linear-gradient(135deg, #d89673, #b8714f);
    z-index: 1;
}

.p3-teddy-arm {
    position: absolute;
    width: 15px;
    height: 30px;
    border-radius: 50%;
    background: #bd7856;
    top: 38px;
    z-index: 3;
}
.p3-teddy-arm.left { left: 2px; transform: rotate(24deg); }
.p3-teddy-arm.right { right: 2px; transform: rotate(-24deg); }

.p3-teddy-heart {
    position: absolute;
    left: 50%;
    top: 42px;
    transform: translateX(-50%);
    font-size: 16px;
    z-index: 4;
}

.p3-flower {
    position: absolute;
    width: 28px;
    height: 28px;
    left: 50%;
    bottom: 30px;
    opacity: 0;
    z-index: 8;
    pointer-events: none;
    transform: translateX(-50%) translateY(40px) scale(0.3);
    transition: transform 1.2s cubic-bezier(0.15, 0.9, 0.25, 1), opacity 0.5s ease;
}
.p3-flower.f1 { margin-left: -50px; color: #ff5287; }
.p3-flower.f2 { margin-left: 50px; color: #a855f7; transition-delay: 0.1s; }
.p3-flower.f3 { margin-left: -75px; color: #3b82f6; transition-delay: 0.2s; }
.p3-flower.f4 { margin-left: 75px; color: #10b981; transition-delay: 0.25s; }

.opened .p3-lid { transform: translateX(-50%) translateX(70px) rotate(28deg); opacity: 0; }
.opened .p3-teddy { opacity: 1; transform: translateX(-50%) translateY(-50px) scale(1); }
.opened .p3-flower { opacity: 1; transform: translateX(-50%) translateY(-45px) scale(1.1); }

.p3-btn-group {
    display: flex;
    justify-content: center;
    align-items: center;
    gap: clamp(8px, 3vw, 14px);
    margin-top: clamp(4px, 1.2vh, 10px);
    width: 100%;
    z-index: 20;
}
.p3-btn {
    min-width: clamp(90px, 22vw, 115px);
    padding: clamp(8px, 1.8vh, 11px) clamp(14px, 3.5vw, 22px);
    border: none;
    border-radius: 30px;
    font-size: clamp(12.5px, 3vw, 14.5px);
    font-weight: 700;
    cursor: pointer;
    transition: transform 0.2s, box-shadow 0.2s;
    pointer-events: auto !important;
}
.p3-btn.yes { color: white; background: linear-gradient(135deg, #f47ca8, #d75ce0); box-shadow: 0 8px 20px rgba(220,90,160,0.28); }
.p3-btn.no { color: #5e708b; background: linear-gradient(135deg, #e7f6ff, #dcecff); box-shadow: 0 8px 20px rgba(100,150,200,0.18); }
.p3-no-msg { margin-top: 6px; font-size: clamp(12px, 2.8vw, 14.5px); font-weight: 700; color: #d95b83; opacity: 0; transform: translateY(6px); transition: 0.3s; pointer-events: none; }
.p3-no-msg.show { opacity: 1; transform: translateY(0); }

/* =========================================================
   PAGE 4: NEON POP BALLOONS & WORD REVEAL
========================================================= */
.p4-area {
    position: relative;
    width: min(94vw, 540px);
    height: clamp(240px, 38vh, 340px);
    margin: auto 0;
}

.p4-balloon {
    position: absolute;
    width: clamp(44px, 10.5vw, 70px);
    height: clamp(56px, 13.5vw, 88px);
    border-radius: 50% 50% 48% 48%;
    cursor: pointer;
    z-index: 10;
    box-shadow: inset -8px -10px 16px rgba(0,0,0,0.16), inset 8px 8px 12px rgba(255,255,255,0.45), 0 10px 20px rgba(90,60,90,0.2);
    transform-origin: center bottom;
    transition: transform 0.2s ease;
    pointer-events: auto !important;
}
.p4-balloon .p4-b-shine {
    position: absolute;
    width: 26%;
    height: 38%;
    left: 20%;
    top: 14%;
    border-radius: 50%;
    background: linear-gradient(135deg, rgba(255,255,255,0.95), transparent 70%);
    transform: rotate(25deg);
    pointer-events: none;
}
.p4-balloon::before {
    content: "";
    position: absolute;
    bottom: -4px;
    left: 50%;
    transform: translateX(-50%);
    width: 8px;
    height: 5px;
    background: inherit;
    border-radius: 2px 2px 4px 4px;
    pointer-events: none;
}
.p4-balloon::after {
    content: "";
    position: absolute;
    width: 1.5px;
    height: clamp(40px, 7vh, 58px);
    background: linear-gradient(to bottom, rgba(120,120,130,0.7), rgba(120,120,130,0.1));
    left: 50%;
    top: 100%;
    transform: translateX(-50%);
    pointer-events: none;
}

.p4-b1 { left: 6%; top: 4%; background: radial-gradient(circle at 35% 25%, #ffb6ce 0%, #ec4885 80%); animation: p4Float1 3.2s infinite ease-in-out; }
.p4-b2 { right: 6%; top: 4%; background: radial-gradient(circle at 35% 25%, #c6f0ff 0%, #38bdf8 80%); animation: p4Float2 3.5s 0.4s infinite ease-in-out; }
.p4-b3 { left: 6%; bottom: 8%; background: radial-gradient(circle at 35% 25%, #eed8ff 0%, #a855f7 80%); animation: p4Float1 3.4s 0.8s infinite ease-in-out; }
.p4-b4 { right: 6%; bottom: 8%; background: radial-gradient(circle at 35% 25%, #fff2be 0%, #eab308 80%); animation: p4Float2 3.6s 1.2s infinite ease-in-out; }

@keyframes p4Float1 { 0%, 100% { transform: translateY(0) rotate(-3deg); } 50% { transform: translateY(-10px) rotate(3deg); } }
@keyframes p4Float2 { 0%, 100% { transform: translateY(0) rotate(3deg); } 50% { transform: translateY(-12px) rotate(-3deg); } }

.p4-balloon.popped {
    animation: pPopAnim 0.3s ease-out forwards;
    pointer-events: none !important;
}

.p4-word-card {
    position: absolute;
    display: inline-flex;
    align-items: center;
    justify-content: center;
    min-width: clamp(60px, 15vw, 80px);
    padding: clamp(5px, 1.2vh, 7px) clamp(10px, 2.5vw, 16px);
    border-radius: 20px;
    background: rgba(255, 255, 255, 0.94);
    border: 2px solid rgba(230, 130, 170, 0.4);
    box-shadow: 0 8px 20px rgba(180, 80, 130, 0.2);
    font-family: "Segoe UI", Roboto, sans-serif;
    font-size: clamp(15px, 3.8vw, 22px);
    font-weight: 800;
    color: #b82b6b;
    letter-spacing: 0.5px;
    opacity: 0;
    transform: scale(0.4) translateY(10px);
    transition: opacity 0.45s cubic-bezier(0.18, 0.85, 0.25, 1), transform 0.5s cubic-bezier(0.18, 0.85, 0.25, 1);
    z-index: 5;
    pointer-events: none;
}
.p4-word-card.show {
    opacity: 1;
    transform: scale(1) translateY(0);
}

.p4-w1 { left: 8%; top: 30%; }
.p4-w2 { right: 8%; top: 30%; }
.p4-w3 { left: 8%; bottom: 30%; }
.p4-w4 { right: 8%; bottom: 30%; }

.p4-final {
    position: absolute;
    inset: 0;
    display: flex;
    align-items: center;
    justify-content: center;
    text-align: center;
    opacity: 0;
    transform: scale(0.2);
    pointer-events: none !important;
    transition: opacity 0.8s cubic-bezier(0.2, 0.8, 0.2, 1), transform 1s cubic-bezier(0.2, 0.8, 0.2, 1);
    z-index: 20;
}
.p4-final.show {
    opacity: 1;
    transform: scale(1);
}

.p4-final-card {
    background: rgba(255, 255, 255, 0.95);
    padding: clamp(14px, 3vh, 24px) clamp(18px, 4vw, 32px);
    border-radius: 28px;
    border: 2px solid rgba(240, 110, 160, 0.45);
    box-shadow: 0 16px 45px rgba(190, 70, 130, 0.25);
    pointer-events: none;
}
.p4-final-text {
    font-family: "Brush Script MT", "Segoe Script", cursive;
    font-size: clamp(26px, 6.5vw, 44px);
    font-weight: 800;
    line-height: 1.2;
    background: linear-gradient(90deg, #e11d48, #c026d3, #2563eb);
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
    pointer-events: none;
}

/* =========================================================
   PAGE 5: FALLING PETALS & ROSE BOUQUET
========================================================= */
.p5-area {
    position: relative;
    width: min(94vw, 550px);
    height: clamp(260px, 40vh, 360px);
    margin: auto 0;
    display: flex;
    align-items: center;
    justify-content: center;
    pointer-events: none;
}

.p5-petals-box {
    position: absolute;
    inset: 0;
    pointer-events: none;
    overflow: hidden;
}

.p5-petal {
    position: absolute;
    width: 12px;
    height: 14px;
    background: radial-gradient(circle at 30% 30%, #ff80a0, #e63956);
    border-radius: 50% 0 50% 50%;
    opacity: 0;
}
.page.active .p5-petal {
    animation: p5PetalDrift 5s infinite linear;
}
.p5-petal:nth-child(1) { left: 15%; animation-delay: 0.2s; }
.p5-petal:nth-child(2) { left: 45%; animation-delay: 1.8s; }
.p5-petal:nth-child(3) { left: 75%; animation-delay: 0.9s; }
.p5-petal:nth-child(4) { left: 88%; animation-delay: 2.7s; }

@keyframes p5PetalDrift {
    0% { transform: translateY(-20px) rotate(0deg); opacity: 0.8; }
    100% { transform: translateY(380px) rotate(360deg); opacity: 0; }
}

.p5-bouquet {
    width: clamp(170px, 38vw, 280px);
    height: auto;
    object-fit: contain;
    filter: drop-shadow(0 16px 22px rgba(70, 40, 60, 0.25));
    animation: p5Float 4s ease-in-out infinite;
    z-index: 5;
    pointer-events: none;
}
@keyframes p5Float { 
    0%, 100% { transform: translateY(0) rotate(0deg); } 
    50% { transform: translateY(-8px) rotate(1.4deg); } 
}

.p5-compliment-card {
    position: absolute;
    display: inline-flex;
    align-items: center;
    justify-content: center;
    padding: clamp(5px, 1vh, 9px) clamp(8px, 2.2vw, 14px);
    background: rgba(255, 255, 255, 0.94);
    border-radius: 20px;
    border: 1.5px solid rgba(235, 120, 165, 0.35);
    box-shadow: 0 8px 20px rgba(130, 50, 90, 0.14);
    color: #9d2159;
    font-family: "Segoe UI", Roboto, sans-serif;
    font-size: clamp(10.5px, 2.5vw, 14px);
    font-weight: 800;
    letter-spacing: 0.2px;
    white-space: nowrap;
    opacity: 0;
    transform: scale(0.45) translateY(14px);
    transition: opacity 0.5s cubic-bezier(0.18, 0.85, 0.25, 1), transform 0.55s cubic-bezier(0.18, 0.85, 0.25, 1);
    z-index: 25;
    pointer-events: none;
}
.p5-compliment-card.show {
    opacity: 1;
    transform: scale(1) translateY(0);
}

.p5-c1 { left: 2%; top: 6%; }
.p5-c2 { right: 2%; top: 10%; }
.p5-c3 { left: 0%; top: 42%; }
.p5-c4 { right: 0%; top: 46%; }
.p5-c5 { left: 4%; bottom: 4%; }
.p5-c6 { right: 4%; bottom: 4%; }

/* =========================================================
   PAGE 6: VINTAGE POLAROID GALLERY
========================================================= */
.p6-gallery-box {
    position: relative;
    width: min(88vw, 420px);
    height: clamp(240px, 46vh, 390px);
    margin: auto 0;
    display: flex;
    justify-content: center;
    align-items: center;
    touch-action: pan-y;
}

.p6-card {
    position: absolute;
    inset: 0;
    padding: clamp(5px, 1.2vw, 8px);
    border-radius: 24px;
    background: rgba(255, 255, 255, 0.95);
    border: 1px solid rgba(255, 255, 255, 0.95);
    box-shadow: 0 16px 40px rgba(100, 70, 110, 0.16);
    opacity: 0;
    transform: translateX(60px) rotate(2deg) scale(0.95);
    transition: opacity 0.5s ease, transform 0.55s cubic-bezier(0.2, 0.8, 0.2, 1);
    display: flex;
    flex-direction: column;
    pointer-events: none;
}
.p6-card.active { opacity: 1; transform: translateX(0) rotate(-1.5deg) scale(1); pointer-events: auto; }

.p6-img-wrap {
    width: 100%;
    flex: 1;
    min-height: 0;
    overflow: hidden;
    border-radius: 18px;
    background: #f5edf3;
    pointer-events: none;
}
.p6-img-wrap img { width: 100%; height: 100%; object-fit: cover; pointer-events: none; }

.p6-caption {
    flex: 0 0 clamp(38px, 7vh, 48px);
    display: flex;
    align-items: center;
    justify-content: center;
    text-align: center;
    padding: 4px 8px;
    color: #a64f76;
    font-size: clamp(10.5px, 2.6vw, 13.5px);
    font-weight: 600;
    pointer-events: none;
}

.p6-nav-btn {
    position: absolute;
    top: 50%;
    transform: translateY(-50%);
    width: clamp(32px, 7.5vw, 40px);
    height: clamp(32px, 7.5vw, 40px);
    border: none;
    border-radius: 50%;
    background: rgba(255,255,255,0.92);
    color: #bd5c83;
    font-size: clamp(16px, 3.8vw, 22px);
    cursor: pointer;
    z-index: 40;
    box-shadow: 0 6px 16px rgba(90,60,90,0.15);
    pointer-events: auto;
}
.p6-nav-btn.prev { left: -10px; }
.p6-nav-btn.next { right: -10px; }

/* =========================================================
   PAGE 7: 3D ENVELOPE & LETTER
========================================================= */
.p7-scene {
    position: relative;
    width: min(92vw, 400px);
    height: clamp(260px, 42vh, 380px);
    perspective: 1400px;
    margin: auto 0;
    display: flex;
    align-items: center;
    justify-content: center;
}

.p7-envelope {
    position: absolute;
    bottom: 12px;
    left: 50%;
    transform: translateX(-50%);
    width: min(80vw, 310px);
    aspect-ratio: 310 / 205;
    cursor: pointer;
    z-index: 30;
    filter: drop-shadow(0 18px 28px rgba(80, 45, 70, 0.22));
    transition: transform 0.6s cubic-bezier(0.2, 0.8, 0.2, 1);
    pointer-events: auto;
}

.p7-env-back {
    position: absolute;
    inset: 0;
    border-radius: 12px;
    background: linear-gradient(135deg, #f7e6ec 0%, #edd3df 100%);
    box-shadow: inset 0 0 15px rgba(180, 110, 135, 0.2);
    z-index: 1;
}

.p7-env-body {
    position: absolute;
    inset: 0;
    border-radius: 12px;
    background: linear-gradient(145deg, #fffdfd 0%, #fff0f5 50%, #ffdbe7 100%);
    border: 1px solid rgba(210, 140, 165, 0.4);
    box-shadow: inset 0 2px 4px rgba(255, 255, 255, 0.9), 0 12px 30px rgba(80, 45, 70, 0.18);
    overflow: hidden;
    z-index: 20;
}

.p7-fold-left {
    position: absolute;
    left: 0;
    bottom: 0;
    width: 60%;
    height: 65%;
    background: linear-gradient(145deg, #ffeef3, #ffd5e4);
    clip-path: polygon(0 0, 100% 100%, 0 100%);
    z-index: 22;
}

.p7-fold-right {
    position: absolute;
    right: 0;
    bottom: 0;
    width: 60%;
    height: 65%;
    background: linear-gradient(215deg, #ffeef3, #ffd5e4);
    clip-path: polygon(100% 0, 100% 100%, 0 100%);
    z-index: 22;
}

.p7-fold-bottom {
    position: absolute;
    left: 0;
    right: 0;
    bottom: 0;
    height: 52%;
    background: linear-gradient(to top, #ffd0e0, #ffeaf1);
    clip-path: polygon(0 100%, 50% 0, 100% 100%);
    z-index: 23;
}

.p7-flap {
    position: absolute;
    left: 0;
    top: 0;
    width: 100%;
    height: 58%;
    background: linear-gradient(160deg, #ffffff 0%, #fff2f6 50%, #ffd8e5 100%);
    clip-path: polygon(0 0, 100% 0, 50% 100%);
    transform-origin: top center;
    transition: transform 1.1s cubic-bezier(0.18, 0.85, 0.25, 1);
    z-index: 40;
    filter: drop-shadow(0 4px 6px rgba(130, 60, 90, 0.15));
}
.p7-flap::before {
    content: "";
    position: absolute;
    inset: 0;
    background: linear-gradient(135deg, rgba(255, 255, 255, 0.8), transparent 60%);
}

.p7-seal {
    position: absolute;
    left: 50%;
    top: 52%;
    transform: translate(-50%, -50%);
    width: clamp(34px, 9vw, 44px);
    height: clamp(34px, 9vw, 44px);
    border-radius: 50%;
    background: radial-gradient(circle at 35% 28%, #fff4be 0%, #e6b84d 40%, #a67316 90%);
    border: 3px solid #f6d878;
    box-shadow: 0 6px 14px rgba(110, 65, 10, 0.35);
    display: flex;
    align-items: center;
    justify-content: center;
    color: #fff9e0;
    font-size: clamp(15px, 3.8vw, 19px);
    z-index: 50;
    transition: opacity 0.45s ease, transform 0.5s ease;
}

.p7-card {
    position: absolute;
    left: 50%;
    bottom: 30px;
    width: min(76vw, 280px);
    min-height: clamp(165px, 26vh, 220px);
    padding: clamp(12px, 2.5vh, 18px) clamp(10px, 2.5vw, 16px);
    border-radius: 20px;
    background: linear-gradient(150deg, #ffffff 0%, #fffbfd 60%, #fff5f8 100%);
    box-shadow: 0 20px 50px rgba(80, 45, 75, 0.28);
    border: 2px solid rgba(230, 140, 175, 0.4);
    text-align: center;
    opacity: 0;
    transform: translateX(-50%) translateY(70px) scale(0.65);
    z-index: 10;
    transition: transform 1.2s cubic-bezier(0.15, 0.9, 0.25, 1), opacity 0.6s ease;
    pointer-events: none;
}

.p7-card-header {
    display: flex;
    align-items: center;
    justify-content: center;
    margin-bottom: 3px;
}
.p7-card-heart {
    font-size: clamp(15px, 3.8vw, 19px);
    animation: p7Heartbeat 1.6s infinite ease-in-out;
}
@keyframes p7Heartbeat { 0%, 100% { transform: scale(1); } 50% { transform: scale(1.2); } }

.p7-card h3 {
    font-family: Georgia, "Times New Roman", serif;
    font-size: clamp(15px, 3.8vw, 20px);
    font-weight: 700;
    color: #ad2863;
    line-height: 1.25;
}

.p7-card p {
    font-family: "Segoe UI", Roboto, sans-serif;
    font-size: clamp(10.5px, 2.5vw, 13px);
    font-weight: 600;
    line-height: 1.5;
    color: #4b3e4a;
    margin-top: 4px;
    text-align: center;
}

.p7-card-sig {
    font-family: "Brush Script MT", "Segoe Script", cursive;
    font-size: clamp(15px, 3.6vw, 20px);
    font-weight: 700;
    color: #c03875;
    margin-top: 6px;
}

.p7-typing::after {
    content: "";
    display: inline-block;
    width: 2px;
    height: 1em;
    margin-left: 2px;
    vertical-align: -2px;
    background: #b84e78;
    animation: p7Blink 0.6s infinite;
}
@keyframes p7Blink { 0%, 50% { opacity: 1; } 51%, 100% { opacity: 0; } }

.p7-scene.open .p7-card {
    opacity: 1;
    transform: translateX(-50%) translateY(-85px) scale(1);
    z-index: 50;
    pointer-events: auto;
}
.p7-scene.open .p7-flap { transform: rotateX(180deg); z-index: 5; }
.p7-scene.open .p7-seal { opacity: 0; transform: translate(-50%, -50%) scale(0.3); }
.p7-scene.open .p7-envelope { transform: translateX(-50%) translateY(26px) scale(0.96); }

.p7-toggle-btn {
    margin-top: 4px;
    font-size: clamp(11px, 2.6vw, 12.5px);
    padding: clamp(7px, 1.5vh, 9px) clamp(16px, 3.5vw, 22px);
    z-index: 60;
    pointer-events: auto;
}

/* =========================================================
   PAGE 8: GRAND FINALE CAKE
========================================================= */
.p8-container {
    width: 100%;
    max-width: 440px;
    margin: auto 0;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    position: relative;
}

.p8-scene {
    position: relative;
    width: min(92vw, 360px);
    height: clamp(210px, 32vh, 260px);
    display: flex;
    align-items: center;
    justify-content: center;
    margin-top: 3px;
    pointer-events: auto;
}

.p8-gift {
    position: absolute;
    bottom: 12px;
    width: clamp(130px, 38vw, 185px);
    aspect-ratio: 185 / 140;
    cursor: pointer;
    z-index: 30;
    filter: drop-shadow(0 18px 28px rgba(180, 70, 110, 0.25));
    transition: transform 1s cubic-bezier(0.2, 0.8, 0.2, 1), opacity 0.65s ease;
    pointer-events: auto !important;
}
.p8-gift:hover { transform: scale(1.03); }

.p8-gift-body {
    position: absolute;
    inset: 0;
    border-radius: 12px;
    background: linear-gradient(135deg, #ff85b3 0%, #f45b96 60%, #db3b7b 100%);
    box-shadow: inset 0 3px 6px rgba(255, 255, 255, 0.4);
    border: 2px solid rgba(255, 255, 255, 0.6);
    overflow: hidden;
}

.p8-gift-ribbon-v {
    position: absolute;
    left: 50%;
    top: 0; bottom: 0;
    width: clamp(16px, 4vw, 22px);
    transform: translateX(-50%);
    background: linear-gradient(90deg, #ffd000, #fff2a8, #e5b000);
}

.p8-gift-ribbon-h {
    position: absolute;
    top: 50%;
    left: 0; right: 0;
    height: clamp(16px, 4vw, 22px);
    transform: translateY(-50%);
    background: linear-gradient(180deg, #ffd000, #fff2a8, #e5b000);
}

.p8-gift-bow {
    position: absolute;
    left: 50%;
    top: -18px;
    transform: translateX(-50%);
    font-size: clamp(28px, 7vw, 38px);
    z-index: 35;
}

.p8-cake-wrap {
    position: absolute;
    bottom: 6px;
    width: clamp(170px, 44vw, 220px);
    height: clamp(155px, 25vh, 205px);
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: flex-end;
    cursor: pointer;
    z-index: 20;
    transform: translateY(70px) scale(0.65);
    opacity: 0;
    pointer-events: none;
    transition: transform 1.2s cubic-bezier(0.15, 0.9, 0.25, 1), opacity 0.7s ease;
}

.p8-ambient-light {
    position: absolute;
    width: clamp(130px, 35vw, 165px);
    height: clamp(130px, 35vw, 165px);
    top: 0px;
    left: 50%;
    transform: translateX(-50%);
    border-radius: 50%;
    background: radial-gradient(circle, rgba(255, 205, 70, 0.38), transparent 70%);
    filter: blur(16px);
    animation: p2Pulse 1s infinite alternate ease-in-out;
    pointer-events: none;
}

.p8-cake {
    position: relative;
    width: clamp(140px, 36vw, 180px);
    height: clamp(115px, 18vh, 145px);
    margin-bottom: clamp(12px, 2.2vh, 18px);
    pointer-events: none;
}

.p8-cake-lower {
    position: absolute;
    bottom: 0;
    width: 100%;
    height: 48%;
    border-radius: 14px 14px 24px 24px;
    background: linear-gradient(90deg, #88432a 0%, #ba6d4b 35%, #9d5032 70%, #76341d 100%);
}

.p8-cake-upper {
    position: absolute;
    bottom: 42%;
    width: 100%;
    height: 38%;
    border-radius: 50% 50% 16px 16px;
    background: linear-gradient(90deg, #a65434, #d98863 35%, #b5603d 75%, #914223 100%);
}

.p8-cake-top-cream {
    position: absolute;
    bottom: 60%;
    left: 50%;
    transform: translateX(-50%);
    width: 103%;
    height: 28%;
    border-radius: 50%;
    background: radial-gradient(ellipse at center, #ffffff 30%, #ffedf4 75%, #ffd6e6 100%);
    z-index: 5;
}

.p8-drip {
    position: absolute;
    background: #ffffff;
    border-radius: 0 0 16px 16px;
    z-index: 6;
}
.p8-d1 { width: 11%; height: 20%; left: 18%; bottom: 50%; }
.p8-d2 { width: 13%; height: 28%; left: 44%; bottom: 46%; }
.p8-d3 { width: 11%; height: 18%; right: 18%; bottom: 52%; }

.p8-candle {
    position: absolute;
    bottom: 80%;
    left: 50%;
    transform: translateX(-50%);
    width: clamp(13px, 3.2vw, 17px);
    height: clamp(40px, 7.5vh, 55px);
    border-radius: 5px;
    background: repeating-linear-gradient(-45deg, #ffffff 0px, #ffffff 6px, #f43f85 6px, #f43f85 13px);
    z-index: 10;
}

.p8-wick-rope {
    position: absolute;
    top: -12px;
    left: 50%;
    transform: translateX(-50%);
    width: 3.5px;
    height: 14px;
    border-radius: 2px;
    background: linear-gradient(to top, #36292b 0%, #1f1416 70%, #ff5e3a 100%);
    z-index: 12;
}

.p8-flame {
    position: absolute;
    top: -40px;
    left: 50%;
    transform: translateX(-50%);
    width: clamp(16px, 4vw, 22px);
    height: clamp(26px, 4.8vh, 36px);
    border-radius: 50% 50% 45% 45%;
    background: radial-gradient(ellipse at 50% 75%, #ffffff 0%, #fff693 25%, #ffc800 50%, #ff4d00 85%);
    box-shadow: 0 0 14px #ffe600, 0 0 28px #ff7b00;
    animation: p2Flicker 0.15s infinite alternate;
    transition: opacity 0.35s ease, transform 0.35s ease;
    z-index: 14;
}

.p8-smoke-box {
    position: absolute;
    top: -16px;
    left: 50%;
    transform: translateX(-50%);
    width: 1px;
    height: 1px;
    pointer-events: none;
    z-index: 15;
}

.p8-smoke-puff {
    position: absolute;
    border-radius: 50%;
    background: radial-gradient(circle, rgba(175, 175, 175, 0.8) 0%, rgba(210, 210, 210, 0.35) 55%, transparent 75%);
    opacity: 0;
}

.p8-cake-wrap.blown .p8-smoke-puff.sm1 { width: 18px; height: 18px; animation: smokeFloat1 2.5s cubic-bezier(0.1, 0.6, 0.3, 1) forwards; }
.p8-cake-wrap.blown .p8-smoke-puff.sm2 { width: 24px; height: 24px; animation: smokeFloat2 2.8s 0.2s cubic-bezier(0.1, 0.6, 0.3, 1) forwards; }
.p8-cake-wrap.blown .p8-smoke-puff.sm3 { width: 32px; height: 32px; animation: smokeFloat3 3.2s 0.45s cubic-bezier(0.1, 0.6, 0.3, 1) forwards; }

.p8-plate {
    position: absolute;
    bottom: 4px;
    width: clamp(160px, 44vw, 210px);
    height: clamp(18px, 3.8vh, 26px);
    border-radius: 50%;
    background: linear-gradient(to bottom, #ffffff, #e4e4ea 60%, #c5c5d0 100%);
    box-shadow: 0 8px 18px rgba(80, 50, 65, 0.2);
    pointer-events: none;
}

.p8-scene.open .p8-gift { transform: translateY(150px) scale(0.6); opacity: 0; pointer-events: none !important; }
.p8-scene.open .p8-cake-wrap { transform: translateY(0) scale(1); opacity: 1; pointer-events: auto !important; }
.p8-cake-wrap.blown .p8-flame { opacity: 0; transform: translateX(-50%) scale(0.05); }
.p8-cake-wrap.blown .p8-ambient-light { opacity: 0; }

.p8-status-card {
    background: rgba(255, 255, 255, 0.94);
    padding: clamp(7px, 1.5vh, 10px) clamp(14px, 3.5vw, 20px);
    border-radius: 24px;
    border: 2px solid rgba(230, 130, 170, 0.4);
    box-shadow: 0 8px 20px rgba(180, 80, 130, 0.16);
    color: #9d1752;
    font-family: "Segoe UI", Roboto, sans-serif;
    font-size: clamp(11.5px, 3vw, 14px);
    font-weight: 800;
    line-height: 1.4;
    margin-top: clamp(4px, 1.2vh, 8px);
    pointer-events: none;
}

.p8-replay-btn {
    margin-top: clamp(6px, 1.5vh, 10px);
    padding: clamp(8px, 1.8vh, 11px) clamp(20px, 4.5vw, 28px);
    font-size: clamp(11.5px, 2.8vw, 13.5px);
    pointer-events: auto !important;
}

/* Touch Sparkle Particles */
.touch-sparkle {
    position: absolute;
    pointer-events: none !important;
    z-index: 99999;
    font-size: clamp(14px, 3.5vw, 20px);
    animation: sparkleAnim 0.75s cubic-bezier(0.1, 0.8, 0.3, 1) forwards;
}

@keyframes sparkleAnim {
    0% { transform: translate(-50%, -50%) scale(0.4) rotate(0deg); opacity: 1; }
    100% { transform: translate(calc(-50% + var(--dx)), calc(-50% + var(--dy))) scale(1.3) rotate(var(--dr)); opacity: 0; }
}

/* Responsive Overrides */
@media (max-height: 600px) {
    .page { padding-top: 10px; padding-bottom: 60px; }
    .page-title { font-size: 24px; }
    .page-subtitle { font-size: 11px; margin-bottom: 4px; }
    .p1-avatar-box { width: 60px; height: 60px; margin: 2px 0 6px; }
    .p1-avatar-circle { font-size: 28px; }
    .p1-desc { font-size: 12px; margin: 4px 0 10px; }
    .p2-cake-wrap, .p3-scene, .p4-area, .p5-area, .p6-gallery-box, .p7-scene, .p8-scene { height: 190px; }
    .navigation { padding: 4px 10px max(6px, env(safe-area-inset-bottom)); }
    .nav-button { width: 34px; height: 34px; font-size: 16px; }
}

@media (min-width: 768px) {
    .page-title { font-size: 46px; }
    .p1-hero-card { max-width: 480px; }
    .p6-gallery-box { width: 440px; height: 420px; }
    .p7-scene { width: 460px; }
}
</style>
</head>

<body>

<div class="app">
    <!-- Fullscreen Canvas for Top-to-Bottom Confetti -->
    <canvas id="confettiCanvas"></canvas>

    <!-- Top Controls (Audio & Fullscreen) -->
    <div class="top-controls">
        <button class="control-btn" id="fsToggleBtn" onclick="toggleFullScreen()" aria-label="Toggle Fullscreen">⛶</button>
        <button class="control-btn" id="audioToggleBtn" onclick="toggleAudioMute()" aria-label="Toggle Sound">🔊</button>
    </div>

    <!-- Ambient Glow Lights Background -->
    <div class="ambient-bg">
        <div class="ambient-blob b1"></div>
        <div class="ambient-blob b2"></div>
        <div class="ambient-blob b3"></div>
        <div class="ambient-blob b4"></div>
    </div>

    <!-- Floating Background Icons -->
    <div class="decor-icon di1">✨</div>
    <div class="decor-icon di2">🌸</div>
    <div class="decor-icon di3">💖</div>
    <div class="decor-icon di4">✦</div>

    <!-- 8 Main Pages Container -->
    <main class="pages" id="pagesContainer">

        <!-- PAGE 1: INTRO PAGE -->
        <section class="page active" id="page1">
            <div class="p1-wrap">
                <div class="p1-floating-tag p1-tag-left">🎂 Special Day</div>
                <div class="p1-floating-tag p1-tag-right">✨ Made for You</div>

                <div class="p1-hero-card" id="p1Card">
                    <div class="page-badge">✨ Birthday Celebration ✨</div>
                    
                    <div class="p1-avatar-box">
                        <div class="p1-avatar-aura"></div>
                        <div class="p1-avatar-circle">👑</div>
                    </div>

                    <h1 class="p1-title-gradient">Happy Birthday<br>Jyoti 💕</h1>
                    
                    <p class="p1-desc">
                        Welcome to your cute 8-page birthday website! Every page holds a sweet little surprise crafted just to make you smile. ✨
                    </p>

                    <button class="cute-btn p1-start-btn" id="p1StartBtn" onclick="handleP1Start()">Let's Begin 🎀</button>
                </div>
            </div>
        </section>

        <!-- PAGE 2: CANDLE CAKE -->
        <section class="page" id="page2">
            <div class="p2-container">
                <div class="page-badge">Page 02 • Make a Wish</div>
                <h2 class="page-title">Make a Wish 🎂</h2>
                <p class="page-subtitle">Tap the button to blow out your candle ✨</p>
                
                <div class="p2-cake-wrap" id="p2Wrap">
                    <div class="p2-glow"></div>
                    <div class="p2-cake">
                        <div class="p2-candle">
                            <div class="p2-wick-rope"></div>
                            <div class="p2-flame" id="p2Flame"></div>
                            <div class="p2-smoke-box">
                                <div class="p2-smoke-puff sm1"></div>
                                <div class="p2-smoke-puff sm2"></div>
                                <div class="p2-smoke-puff sm3"></div>
                            </div>
                        </div>
                        <div class="p2-upper"></div>
                        <div class="p2-cream-top"></div>
                        <div class="p2-drip p2-d1"></div>
                        <div class="p2-drip p2-d2"></div>
                        <div class="p2-drip p2-d3"></div>
                        <div class="p2-lower"></div>
                    </div>
                    <div class="p2-plate"></div>
                </div>

                <div class="p2-action-area">
                    <button class="cute-btn" id="p2BlowBtn" onclick="blowP2Candle()">Blow Candle 🕯️</button>
                    <div class="p2-wish-card" id="p2Wish">
                        ✨ May all your sweetest dreams come true! 💕<br>Wishing you endless joy and happiness! 🎀
                    </div>
                </div>
            </div>
        </section>

        <!-- PAGE 3: SURPRISE UNBOXING -->
        <section class="page" id="page3">
            <div class="page-badge">Page 03 • Surprise</div>
            <h1 class="p3-title">Happy Birthday Jyoti 🎂</h1>
            <div class="p3-scene" id="p3Scene">
                <div class="p3-balloon p3-b1" onclick="popP3Balloon(this)">
                    <div class="p3-b-shine"></div>
                </div>
                <div class="p3-balloon p3-b2" onclick="popP3Balloon(this)">
                    <div class="p3-b-shine"></div>
                </div>
                <div class="p3-balloon p3-b3" onclick="popP3Balloon(this)">
                    <div class="p3-b-shine"></div>
                </div>

                <div class="p3-gift">
                    <div class="p3-teddy">
                        <div class="p3-teddy-ear left"></div>
                        <div class="p3-teddy-ear right"></div>
                        <div class="p3-teddy-head">
                            <div class="p3-teddy-eye left"></div>
                            <div class="p3-teddy-eye right"></div>
                            <div class="p3-teddy-muzzle">
                                <div class="p3-teddy-nose"></div>
                            </div>
                        </div>
                        <div class="p3-teddy-body"></div>
                        <div class="p3-teddy-arm left"></div>
                        <div class="p3-teddy-arm right"></div>
                        <div class="p3-teddy-heart">💗</div>
                    </div>

                    <div class="p3-flower f1">🌸</div>
                    <div class="p3-flower f2">🌷</div>
                    <div class="p3-flower f3">🌺</div>
                    <div class="p3-flower f4">🌼</div>

                    <div class="p3-box-body"></div>
                    <div class="p3-lid"></div>
                </div>
            </div>

            <div style="font-size: clamp(13px, 3.2vw, 16px); font-weight: 600; color: #67546a; margin-top: 4px;">Are you excited for what's next?</div>
            <div class="p3-btn-group">
                <button class="p3-btn yes" onclick="openP3Gift()">Yes 💕</button>
                <button class="p3-btn no" id="p3NoBtn" onclick="dodgeP3No(event)">No 🙈</button>
            </div>
            <div class="p3-no-msg" id="p3NoMsg">😭 Please Click Yes 💕</div>
        </section>

        <!-- PAGE 4: 4 BALLOONS WORD REVEAL -->
        <section class="page" id="page4">
            <div class="page-badge">Page 04 • Pop Game</div>
            <h2 class="page-title">Pop the Balloons 🎈</h2>
            <div class="page-subtitle">Tap each balloon to reveal the secret message ✨</div>
            <div class="p4-area" id="p4Area">
                <div class="p4-balloon p4-b1" onclick="popP4Balloon(this, 'p4W1')"></div>
                <div class="p4-word-card p4-w1" id="p4W1">You</div>

                <div class="p4-balloon p4-b2" onclick="popP4Balloon(this, 'p4W2')"></div>
                <div class="p4-word-card p4-w2" id="p4W2">are</div>

                <div class="p4-balloon p4-b3" onclick="popP4Balloon(this, 'p4W3')"></div>
                <div class="p4-word-card p4-w3" id="p4W3">so</div>

                <div class="p4-balloon p4-b4" onclick="popP4Balloon(this, 'p4W4')"></div>
                <div class="p4-word-card p4-w4" id="p4W4">Cute</div>

                <div class="p4-final" id="p4Final">
                    <div class="p4-final-card">
                        <div style="font-size: clamp(24px, 6vw, 32px); margin-bottom: 4px;">💖✨</div>
                        <div class="p4-final-text">You are so cute 💕</div>
                    </div>
                </div>
            </div>
        </section>

        <!-- PAGE 5: ROSE BOUQUET -->
        <section class="page" id="page5">
            <div class="page-badge">Page 05 • Flowers</div>
            <h1 class="page-title">Your Rose Bouquet 🌹</h1>
            <div class="page-subtitle">A special bouquet of words just for you ✨</div>
            <div class="p5-area">
                <div class="p5-petals-box">
                    <div class="p5-petal"></div>
                    <div class="p5-petal"></div>
                    <div class="p5-petal"></div>
                    <div class="p5-petal"></div>
                </div>
                <div class="p5-compliment-card p5-c1">✨ Absolutely Beautiful</div>
                <div class="p5-compliment-card p5-c2">💕 So Lovely</div>
                <div class="p5-compliment-card p5-c3">🌸 Sweet & Adorable</div>
                <div class="p5-compliment-card p5-c4">💖 Truly Special</div>
                <div class="p5-compliment-card p5-c5">✨ Full of Charm</div>
                <div class="p5-compliment-card p5-c6">🌹 Simply Gorgeous</div>
                <img class="p5-bouquet" src="https://pngimg.com/uploads/rose/rose_PNG648.png" alt="Rose Bouquet">
            </div>
        </section>

        <!-- PAGE 6: MOMENTS GALLERY -->
        <section class="page" id="page6">
            <div class="page-badge">Page 06 • Moments</div>
            <h1 class="page-title">Some Sweet Moments 🌸</h1>
            <div class="page-subtitle">Swipe left/right on photo to view all ✨</div>
            <div class="p6-gallery-box" id="p6Gallery">
                <button class="p6-nav-btn prev" onclick="prevP6Photo()">‹</button>
                <button class="p6-nav-btn next" onclick="nextP6Photo()">›</button>
            </div>
        </section>

        <!-- PAGE 7: 3D ENVELOPE & LETTER -->
        <section class="page" id="page7">
            <div class="page-badge">Page 07 • Special Message</div>
            <h1 class="page-title">A Letter For You 💌</h1>
            <div class="page-subtitle">Tap the envelope to open your letter ✨</div>
            
            <div class="p7-scene" id="p7Scene">
                <div class="p7-card" id="p7Card">
                    <div class="p7-card-header">
                        <span class="p7-card-heart">💖</span>
                    </div>
                    <h3 id="p7CardTitle"></h3>
                    <p id="p7CardMessage"></p>
                    <div class="p7-card-sig" id="p7CardSig"></div>
                </div>

                <div class="p7-envelope" id="p7Envelope" onclick="toggleP7Envelope()">
                    <div class="p7-env-back"></div>
                    <div class="p7-env-body">
                        <div class="p7-fold-left"></div>
                        <div class="p7-fold-right"></div>
                        <div class="p7-fold-bottom"></div>
                    </div>
                    <div class="p7-flap"></div>
                    <div class="p7-seal">♥</div>
                </div>
            </div>

            <button class="cute-btn p7-toggle-btn" id="p7Btn" onclick="toggleP7Envelope()">Open Envelope 💌</button>
        </section>

        <!-- PAGE 8: CAKE SURPRISE & REPLAY -->
        <section class="page" id="page8">
            <div class="p8-container">
                <div class="page-badge">Page 08 • Final Surprise</div>
                <h1 class="page-title">One Last Thing ✨</h1>
                <p class="page-subtitle">A special birthday wish waiting for you 🎁</p>

                <div class="p8-scene" id="p8Scene">
                    <div class="p8-gift" id="p8Gift" onclick="openP8Gift()">
                        <div class="p8-gift-body">
                            <div class="p8-gift-ribbon-v"></div>
                            <div class="p8-gift-ribbon-h"></div>
                        </div>
                        <div class="p8-gift-bow">🎀</div>
                    </div>

                    <div class="p8-cake-wrap" id="p8CakeWrap" onclick="toggleP8Candle()">
                        <div class="p8-ambient-light"></div>
                        <div class="p8-cake">
                            <div class="p8-candle">
                                <div class="p8-wick-rope"></div>
                                <div class="p8-flame" id="p8Flame"></div>
                                <div class="p8-smoke-box">
                                    <div class="p8-smoke-puff sm1"></div>
                                    <div class="p8-smoke-puff sm2"></div>
                                    <div class="p8-smoke-puff sm3"></div>
                                </div>
                            </div>
                            <div class="p8-cake-upper"></div>
                            <div class="p8-cake-top-cream"></div>
                            <div class="p8-drip p8-d1"></div>
                            <div class="p8-drip p8-d2"></div>
                            <div class="p8-drip p8-d3"></div>
                            <div class="p8-cake-lower"></div>
                        </div>
                        <div class="p8-plate"></div>
                    </div>
                </div>

                <div class="p8-status-card" id="p8Status">
                    🎁 Click the gift box to reveal your cake!
                </div>

                <button class="cute-btn p8-replay-btn" onclick="startAgainFromBeginning()">Start Again 💕</button>
            </div>
        </section>

    </main>

    <!-- Bottom Floating Navigation -->
    <nav class="navigation">
        <button class="nav-button" id="prevButton" onclick="previousPage()" aria-label="Previous Page">‹</button>
        <div class="dots" id="dotsContainer"></div>
        <button class="nav-button" id="nextButton" onclick="nextPage()" aria-label="Next Page">›</button>
    </nav>
</div>

<script>
/* =========================================================
   CANVAS CONFETTI ENGINE (STRICT TOP-TO-BOTTOM RAIN)
========================================================= */
const confettiCanvas = document.getElementById("confettiCanvas");
const cCtx = confettiCanvas.getContext("2d");
let confettiParticles = [];
let confettiAnimationId = null;

function resizeCanvas() {
    confettiCanvas.width = window.innerWidth;
    confettiCanvas.height = window.innerHeight;
}
window.addEventListener("resize", resizeCanvas);
resizeCanvas();

function launchConfetti(count = 65) {
    const colors = ["#ff4081", "#fd8a5e", "#ffd700", "#00e676", "#00b0ff", "#d946ef", "#ff80ab", "#b388ff"];
    for (let i = 0; i < count; i++) {
        confettiParticles.push({
            x: Math.random() * confettiCanvas.width,
            y: -20 - Math.random() * 80,
            w: Math.random() * 8 + 6,
            h: Math.random() * 5 + 4,
            color: colors[Math.floor(Math.random() * colors.length)],
            vx: (Math.random() - 0.5) * 1.5,
            vy: Math.random() * 3 + 2.8,
            rot: Math.random() * 360,
            vRot: (Math.random() - 0.5) * 5,
            opacity: 1,
            life: 0,
            maxLife: Math.random() * 70 + 80
        });
    }
    if (!confettiAnimationId) {
        updateConfetti();
    }
}

function updateConfetti() {
    cCtx.clearRect(0, 0, confettiCanvas.width, confettiCanvas.height);
    for (let i = confettiParticles.length - 1; i >= 0; i--) {
        const p = confettiParticles[i];
        p.life++;
        p.x += p.vx + Math.sin(p.life * 0.05) * 0.8;
        p.y += p.vy;
        p.rot += p.vRot;

        if (p.life > p.maxLife * 0.6) {
            p.opacity = Math.max(0, 1 - (p.life - p.maxLife * 0.6) / (p.maxLife * 0.4));
        }

        cCtx.save();
        cCtx.translate(p.x, p.y);
        cCtx.rotate((p.rot * Math.PI) / 180);
        cCtx.fillStyle = p.color;
        cCtx.globalAlpha = p.opacity;
        cCtx.fillRect(-p.w / 2, -p.h / 2, p.w, p.h);
        cCtx.restore();

        if (p.opacity <= 0 || p.y > confettiCanvas.height + 30) {
            confettiParticles.splice(i, 1);
        }
    }

    if (confettiParticles.length > 0) {
        confettiAnimationId = requestAnimationFrame(updateConfetti);
    } else {
        confettiAnimationId = null;
        cCtx.clearRect(0, 0, confettiCanvas.width, confettiCanvas.height);
    }
}

/* =========================================================
   PAGE 1 3D TILT EFFECT
========================================================= */
const p1Card = document.getElementById("p1Card");
if (p1Card) {
    window.addEventListener("pointermove", (e) => {
        if (currentPage !== 1) return;
        const x = (e.clientX / window.innerWidth - 0.5) * 14;
        const y = (e.clientY / window.innerHeight - 0.5) * -14;
        p1Card.style.transform = `rotateY(${x}deg) rotateX(${y}deg)`;
    });
}

/* =========================================================
   TOUCH SPARKLE PARTICLE EFFECT
========================================================= */
document.addEventListener("pointerdown", (e) => {
    if (e.target.closest(".control-btn") || e.target.closest(".nav-button")) return;
    createTouchSparkle(e.clientX, e.clientY);
});

function createTouchSparkle(x, y) {
    const symbols = ["✨", "💖", "🌸", "⭐", "💕", "✦"];
    const count = 4;
    for (let i = 0; i < count; i++) {
        const s = document.createElement("div");
        s.className = "touch-sparkle";
        s.textContent = symbols[Math.floor(Math.random() * symbols.length)];
        s.style.left = x + "px";
        s.style.top = y + "px";

        const angle = Math.random() * Math.PI * 2;
        const dist = Math.random() * 45 + 15;
        s.style.setProperty("--dx", Math.cos(angle) * dist + "px");
        s.style.setProperty("--dy", Math.sin(angle) * dist + "px");
        s.style.setProperty("--dr", (Math.random() - 0.5) * 60 + "deg");

        document.body.appendChild(s);
        setTimeout(() => s.remove(), 750);
    }
}

/* =========================================================
   FULLSCREEN API TOGGLE
========================================================= */
function toggleFullScreen() {
    const doc = window.document;
    const docEl = doc.documentElement;
    const btn = document.getElementById("fsToggleBtn");

    const requestFullScreen = docEl.requestFullscreen || docEl.mozRequestFullScreen || docEl.webkitRequestFullScreen || docEl.msRequestFullscreen;
    const cancelFullScreen = doc.exitFullscreen || doc.mozCancelFullScreen || doc.webkitExitFullscreen || doc.msExitFullscreen;

    if (!doc.fullscreenElement && !doc.mozFullScreenElement && !doc.webkitFullscreenElement && !doc.msFullscreenElement) {
        if (requestFullScreen) {
            requestFullScreen.call(docEl).then(() => {
                if (btn) btn.textContent = "✕";
            }).catch(() => {});
        }
    } else {
        if (cancelFullScreen) {
            cancelFullScreen.call(doc).then(() => {
                if (btn) btn.textContent = "⛶";
            }).catch(() => {});
        }
    }
}

document.addEventListener("fullscreenchange", () => {
    const btn = document.getElementById("fsToggleBtn");
    if (!document.fullscreenElement && btn) {
        btn.textContent = "⛶";
    }
});

/* =========================================================
   SYNTHETIC WEB AUDIO & RICH LOUDER BGM ENGINE
========================================================= */
let audioCtx = null;
let isMuted = false;
let bgmTimer = null;
let bgmStep = 0;

function getAudioContext() {
    if (!audioCtx) {
        const AudioContext = window.AudioContext || window.webkitAudioContext;
        if (AudioContext) {
            audioCtx = new AudioContext();
        }
    }
    if (audioCtx && audioCtx.state === 'suspended') {
        audioCtx.resume();
    }
    return audioCtx;
}

function triggerHaptic(duration = 20) {
    if (navigator.vibrate) {
        try { navigator.vibrate(duration); } catch(e){}
    }
}

function toggleAudioMute() {
    isMuted = !isMuted;
    const btn = document.getElementById("audioToggleBtn");
    if (btn) btn.textContent = isMuted ? "🔇" : "🔊";
    if (!isMuted) {
        getAudioContext();
        startRichBgm();
        playPopSound();
    } else {
        stopRichBgm();
    }
}

// Rich Happy Birthday Melody with Bass Chords
const hbdScore = [
    { f: 261.63, b: 130.81, d: 0.35, p: 0.42 },
    { f: 261.63, b: 130.81, d: 0.22, p: 0.25 },
    { f: 293.66, b: 146.83, d: 0.65, p: 0.70 },
    { f: 261.63, b: 130.81, d: 0.65, p: 0.70 },
    { f: 349.23, b: 174.61, d: 0.65, p: 0.70 },
    { f: 329.63, b: 164.81, d: 1.15, p: 1.25 },

    { f: 261.63, b: 130.81, d: 0.35, p: 0.42 },
    { f: 261.63, b: 130.81, d: 0.22, p: 0.25 },
    { f: 293.66, b: 146.83, d: 0.65, p: 0.70 },
    { f: 261.63, b: 130.81, d: 0.65, p: 0.70 },
    { f: 392.00, b: 196.00, d: 0.65, p: 0.70 },
    { f: 349.23, b: 174.61, d: 1.15, p: 1.25 },

    { f: 261.63, b: 130.81, d: 0.35, p: 0.42 },
    { f: 261.63, b: 130.81, d: 0.22, p: 0.25 },
    { f: 523.25, b: 261.63, d: 0.70, p: 0.75 },
    { f: 440.00, b: 220.00, d: 0.70, p: 0.75 },
    { f: 349.23, b: 174.61, d: 0.70, p: 0.75 },
    { f: 329.63, b: 164.81, d: 0.70, p: 0.75 },
    { f: 293.66, b: 146.83, d: 1.10, p: 1.20 },

    { f: 466.16, b: 233.08, d: 0.35, p: 0.42 },
    { f: 466.16, b: 233.08, d: 0.22, p: 0.25 },
    { f: 440.00, b: 220.00, d: 0.70, p: 0.75 },
    { f: 349.23, b: 174.61, d: 0.70, p: 0.75 },
    { f: 392.00, b: 196.00, d: 0.70, p: 0.75 },
    { f: 349.23, b: 174.61, d: 1.40, p: 1.80 }
];

function playRichNote(freq, bassFreq, duration) {
    if (isMuted) return;
    const ctx = getAudioContext();
    if (!ctx) return;
    try {
        const now = ctx.currentTime;
        
        const osc1 = ctx.createOscillator();
        const gain1 = ctx.createGain();
        osc1.type = "triangle";
        osc1.frequency.setValueAtTime(freq, now);
        gain1.gain.setValueAtTime(0.18, now);
        gain1.gain.exponentialRampToValueAtTime(0.001, now + duration);
        osc1.connect(gain1);
        gain1.connect(ctx.destination);
        osc1.start(now);
        osc1.stop(now + duration);

        if (bassFreq) {
            const osc2 = ctx.createOscillator();
            const gain2 = ctx.createGain();
            osc2.type = "sine";
            osc2.frequency.setValueAtTime(bassFreq, now);
            gain2.gain.setValueAtTime(0.12, now);
            gain2.gain.exponentialRampToValueAtTime(0.001, now + duration * 0.9);
            osc2.connect(gain2);
            gain2.connect(ctx.destination);
            osc2.start(now);
            osc2.stop(now + duration * 0.9);
        }
    } catch(e){}
}

function playBgmLoop() {
    if (isMuted) return;
    const note = hbdScore[bgmStep];
    playRichNote(note.f, note.b, note.d);
    bgmStep = (bgmStep + 1) % hbdScore.length;
    bgmTimer = setTimeout(playBgmLoop, note.p * 1000);
}

function startRichBgm() {
    if (bgmTimer || isMuted) return;
    playBgmLoop();
}

function stopRichBgm() {
    if (bgmTimer) {
        clearTimeout(bgmTimer);
        bgmTimer = null;
    }
}

function playPopSound() {
    if (isMuted) return;
    const ctx = getAudioContext();
    if (!ctx) return;
    try {
        const osc = ctx.createOscillator();
        const gain = ctx.createGain();
        osc.type = "sine";
        osc.frequency.setValueAtTime(420, ctx.currentTime);
        osc.frequency.exponentialRampToValueAtTime(820, ctx.currentTime + 0.07);
        gain.gain.setValueAtTime(0.2, ctx.currentTime);
        gain.gain.exponentialRampToValueAtTime(0.01, ctx.currentTime + 0.07);
        osc.connect(gain);
        gain.connect(ctx.destination);
        osc.start();
        osc.stop(ctx.currentTime + 0.07);
    } catch(e){}
}

function playBalloonPopSound() {
    triggerHaptic(30);
    if (isMuted) return;
    const ctx = getAudioContext();
    if (!ctx) return;
    try {
        const bufferSize = ctx.sampleRate * 0.08;
        const buffer = ctx.createBuffer(1, bufferSize, ctx.sampleRate);
        const data = buffer.getChannelData(0);
        for (let i = 0; i < bufferSize; i++) data[i] = Math.random() * 2 - 1;
        const noise = ctx.createBufferSource();
        noise.buffer = buffer;
        const filter = ctx.createBiquadFilter();
        filter.type = "bandpass";
        filter.frequency.setValueAtTime(1400, ctx.currentTime);
        filter.Q.setValueAtTime(3.5, ctx.currentTime);
        const gain = ctx.createGain();
        gain.gain.setValueAtTime(0.7, ctx.currentTime);
        gain.gain.exponentialRampToValueAtTime(0.01, ctx.currentTime + 0.08);
        noise.connect(filter);
        filter.connect(gain);
        gain.connect(ctx.destination);
        noise.start();
    } catch(e){}
}

function playCandleBlowSound() {
    triggerHaptic(40);
    if (isMuted) return;
    const ctx = getAudioContext();
    if (!ctx) return;
    try {
        const bufferSize = ctx.sampleRate * 0.35;
        const buffer = ctx.createBuffer(1, bufferSize, ctx.sampleRate);
        const data = buffer.getChannelData(0);
        for (let i = 0; i < bufferSize; i++) data[i] = Math.random() * 2 - 1;
        const noise = ctx.createBufferSource();
        noise.buffer = buffer;
        const filter = ctx.createBiquadFilter();
        filter.type = "lowpass";
        filter.frequency.setValueAtTime(650, ctx.currentTime);
        filter.frequency.linearRampToValueAtTime(180, ctx.currentTime + 0.35);
        const gain = ctx.createGain();
        gain.gain.setValueAtTime(0.55, ctx.currentTime);
        gain.gain.exponentialRampToValueAtTime(0.01, ctx.currentTime + 0.35);
        noise.connect(filter);
        filter.connect(gain);
        gain.connect(ctx.destination);
        noise.start();

        setTimeout(() => {
            playTone(880, 0.25, "triangle", 0.15);
            setTimeout(() => playTone(1174, 0.3, "sine", 0.15), 120);
        }, 200);
    } catch(e){}
}

function playMagicFanfare() {
    triggerHaptic(25);
    if (isMuted) return;
    const notes = [523.25, 659.25, 783.99, 1046.50, 1318.51];
    notes.forEach((freq, idx) => {
        setTimeout(() => playTone(freq, 0.3, "triangle", 0.2), idx * 75);
    });
}

function playTypewriterClick() {
    if (isMuted) return;
    const ctx = getAudioContext();
    if (!ctx) return;
    try {
        const osc = ctx.createOscillator();
        const gain = ctx.createGain();
        osc.type = "triangle";
        osc.frequency.setValueAtTime(1500 + Math.random() * 250, ctx.currentTime);
        gain.gain.setValueAtTime(0.12, ctx.currentTime);
        gain.gain.exponentialRampToValueAtTime(0.01, ctx.currentTime + 0.03);
        osc.connect(gain);
        gain.connect(ctx.destination);
        osc.start();
        osc.stop(ctx.currentTime + 0.03);
    } catch(e){}
}

function playTone(freq, duration, type = "sine", vol = 0.2) {
    if (isMuted) return;
    const ctx = getAudioContext();
    if (!ctx) return;
    try {
        const osc = ctx.createOscillator();
        const gain = ctx.createGain();
        osc.type = type;
        osc.frequency.setValueAtTime(freq, ctx.currentTime);
        gain.gain.setValueAtTime(vol, ctx.currentTime);
        gain.gain.exponentialRampToValueAtTime(0.001, ctx.currentTime + duration);
        osc.connect(gain);
        gain.connect(ctx.destination);
        osc.start();
        osc.stop(ctx.currentTime + duration);
    } catch(e){}
}

function playSwooshSound() {
    if (isMuted) return;
    playTone(320, 0.12, "triangle", 0.12);
}

/* =========================================================
   APP CONTROLLER & PAGE NAVIGATION
========================================================= */
const pages = document.querySelectorAll(".page");
const dotsContainer = document.getElementById("dotsContainer");
const prevButton = document.getElementById("prevButton");
const nextButton = document.getElementById("nextButton");
let currentPage = 1;
const totalPages = pages.length;

for (let i = 1; i <= totalPages; i++) {
    const dot = document.createElement("button");
    dot.className = "dot" + (i === 1 ? " active" : "");
    dot.setAttribute("aria-label", "Go to page " + i);
    dot.addEventListener("click", () => {
        startRichBgm();
        playPopSound();
        goToPage(i);
    });
    dotsContainer.appendChild(dot);
}

function showPage(pageNumber) {
    if (pageNumber < 1 || pageNumber > totalPages) return;
    const isNext = pageNumber > currentPage;
    
    pages.forEach((page, idx) => {
        const pageIdx = idx + 1;
        if (pageIdx === pageNumber) {
            page.classList.add("active");
            page.classList.remove("prev-exit");
        } else if (pageIdx === currentPage) {
            page.classList.remove("active");
            if (isNext) page.classList.add("prev-exit");
        } else {
            page.classList.remove("active", "prev-exit");
        }
    });

    currentPage = pageNumber;

    document.querySelectorAll(".dot").forEach((dot, idx) => {
        dot.classList.toggle("active", idx + 1 === currentPage);
    });

    prevButton.disabled = currentPage === 1;
    nextButton.disabled = currentPage === totalPages;

    if (currentPage === 5) triggerP5Compliments();
    if (currentPage === 6) initP6Gallery();
}

function goToPage(n) { showPage(n); }
function nextPage() { 
    if (currentPage < totalPages) {
        startRichBgm();
        playPopSound();
        showPage(currentPage + 1); 
    }
}
function previousPage() { 
    if (currentPage > 1) {
        startRichBgm();
        playPopSound();
        showPage(currentPage - 1); 
    }
}

function handleP1Start() {
    startRichBgm();
    playMagicFanfare();
    launchConfetti(45);
    showPage(2);
}

/* =========================================================
   TOUCH SWIPE GESTURES
========================================================= */
let startX = 0;
let startY = 0;
let isGalleryTarget = false;

document.addEventListener("touchstart", (e) => {
    startX = e.touches[0].clientX;
    startY = e.touches[0].clientY;
    isGalleryTarget = Boolean(e.target.closest("#p6Gallery"));
}, { passive: true });

document.addEventListener("touchend", (e) => {
    const endX = e.changedTouches[0].clientX;
    const endY = e.changedTouches[0].clientY;
    const diffX = startX - endX;
    const diffY = startY - endY;

    if (Math.abs(diffX) > Math.abs(diffY) && Math.abs(diffX) > 45) {
        if (isGalleryTarget && currentPage === 6) {
            playSwooshSound();
            if (diffX > 0) nextP6Photo();
            else prevP6Photo();
        } else {
            if (diffX > 0) nextPage();
            else previousPage();
        }
    }
}, { passive: true });

/* =========================================================
   PAGE 2 LOGIC (Candle Blowout & Smoke)
========================================================= */
let p2Blown = false;
function blowP2Candle() {
    if (p2Blown) return;
    p2Blown = true;
    startRichBgm();
    playCandleBlowSound();
    launchConfetti(40);

    const wrap = document.getElementById("p2Wrap");
    if (wrap) wrap.classList.add("blown");
    
    const btn = document.getElementById("p2BlowBtn");
    if (btn) {
        btn.style.opacity = "0";
        btn.style.pointerEvents = "none";
    }
    
    setTimeout(() => {
        if (btn) btn.style.display = "none";
        const wish = document.getElementById("p2Wish");
        if (wish) wish.classList.add("show");
    }, 300);
}

/* =========================================================
   PAGE 3 LOGIC (Balloons, Unboxing & Flowers)
========================================================= */
let p3Opened = false;

function popP3Balloon(balloon) {
    if (!balloon || balloon.classList.contains("popped")) return;
    balloon.classList.add("popped");
    startRichBgm();
    playBalloonPopSound();
}

function openP3Gift() {
    if (p3Opened) return;
    p3Opened = true;
    startRichBgm();
    playMagicFanfare();
    launchConfetti(55);

    const scene = document.getElementById("p3Scene");
    if (scene) scene.classList.add("opened");
    const noMsg = document.getElementById("p3NoMsg");
    if (noMsg) noMsg.classList.remove("show");
    resetP3NoBtn();

    setTimeout(() => {
        document.querySelectorAll(".p3-flower").forEach((f) => {
            f.style.transition = "opacity 0.8s ease, transform 0.8s ease";
            f.style.opacity = "0";
            f.style.transform = "translateX(-50%) translateY(-20px) scale(0.5)";
        });
    }, 2500);
}

function dodgeP3No(e) {
    e.preventDefault();
    startRichBgm();
    playPopSound();
    const btn = document.getElementById("p3NoBtn");
    const noMsg = document.getElementById("p3NoMsg");
    if (noMsg) noMsg.classList.add("show");
    
    if (btn) {
        const maxX = window.innerWidth - btn.offsetWidth - 20;
        const maxY = window.innerHeight - btn.offsetHeight - 90;
        btn.style.position = "fixed";
        btn.style.left = Math.max(15, Math.random() * maxX) + "px";
        btn.style.top = Math.max(80, Math.random() * maxY) + "px";
        btn.style.zIndex = "9999";
    }
}

function resetP3NoBtn() {
    const btn = document.getElementById("p3NoBtn");
    if (btn) {
        btn.style.position = ""; 
        btn.style.left = ""; 
        btn.style.top = "";
        btn.style.zIndex = "";
    }
}

/* =========================================================
   PAGE 4 LOGIC (4 Balloons Word Reveal)
========================================================= */
let p4Popped = 0;
function popP4Balloon(b, wordId) {
    if (!b || b.classList.contains("popped")) return;
    b.classList.add("popped");
    startRichBgm();
    playBalloonPopSound();

    setTimeout(() => {
        b.style.display = "none";
        const wCard = document.getElementById(wordId);
        if (wCard) wCard.classList.add("show");
    }, 250);

    p4Popped++;
    if (p4Popped === 4) {
        setTimeout(() => {
            playMagicFanfare();
            launchConfetti(70);
            document.querySelectorAll(".p4-word-card").forEach(w => w.classList.remove("show"));
            const finalCard = document.getElementById("p4Final");
            if (finalCard) finalCard.classList.add("show");
        }, 900);
    }
}

/* =========================================================
   PAGE 5 LOGIC (Compliments)
========================================================= */
let p5Ran = false;
function triggerP5Compliments() {
    if (p5Ran) return;
    p5Ran = true;
    const cards = document.querySelectorAll(".p5-compliment-card");
    cards.forEach((item, index) => {
        setTimeout(() => {
            playTone(550 + index * 90, 0.22, "sine", 0.12);
            item.classList.add("show");
        }, (index + 1) * 600);
    });
}

/* =========================================================
   PAGE 6 LOGIC (Sliding Gallery Carousel)
========================================================= */
const p6Photos = [
    { src:"https://i.ibb.co/Txn7ktPp/IMG-20260321-WA0087.jpg", cap: "May your day be beautiful 🌸" },
    { src: "https://images.unsplash.com/photo-1496440737103-cd596325d314?auto=format&fit=crop&w=800&q=80", cap: "Keep shining & smiling ✨" },
    { src: "https://images.unsplash.com/photo-1534528741775-53994a69daeb?auto=format&fit=crop&w=800&q=80", cap: "Happy Birthday Jyoti! 🎂💖" }
];
let p6Current = 0;
let p6Loaded = false;

function initP6Gallery() {
    if (p6Loaded) return;
    p6Loaded = true;
    const gallery = document.getElementById("p6Gallery");
    if (!gallery) return;
    p6Photos.forEach((item, i) => {
        const card = document.createElement("div");
        card.className = "p6-card" + (i === 0 ? " active" : "");
        card.id = "p6Card" + i;
        card.innerHTML = `<div class="p6-img-wrap"><img src="${item.src}" alt="Moment"></div><div class="p6-caption">${item.cap}</div>`;
        gallery.appendChild(card);
    });
}

function showP6Slide(n) {
    if (n < 0) n = p6Photos.length - 1;
    if (n >= p6Photos.length) n = 0;
    document.querySelectorAll(".p6-card").forEach((c, idx) => {
        c.classList.toggle("active", idx === n);
    });
    p6Current = n;
}
function nextP6Photo() { 
    playSwooshSound();
    showP6Slide(p6Current + 1); 
}
function prevP6Photo() { 
    playSwooshSound();
    showP6Slide(p6Current - 1); 
}

/* =========================================================
   PAGE 7 LOGIC (Enhanced 3D Envelope & Typewriter)
========================================================= */
let p7Opened = false;
let p7Timers = [];

function clearP7Timers() {
    p7Timers.forEach(t => clearTimeout(t));
    p7Timers = [];
}

function toggleP7Envelope() {
    const scene = document.getElementById("p7Scene");
    const btn = document.getElementById("p7Btn");
    
    if (!p7Opened) {
        p7Opened = true;
        clearP7Timers();
        startRichBgm();
        playMagicFanfare();
        launchConfetti(45);

        if (scene) scene.classList.add("open");
        if (btn) btn.textContent = "Close Envelope 💌";

        const t1 = setTimeout(() => {
            typeWriter("p7CardTitle", "Happy Birthday Jyoti! 🎉", 60, () => {
                const t2 = setTimeout(() => {
                    typeWriter("p7CardMessage", "May your special day bring you immense happiness, beautiful smiles, and cherished memories that last a lifetime! Keep inspiring and shining always. ✨", 28, () => {
                        const t3 = setTimeout(() => {
                            typeWriter("p7CardSig", "With lots of love 💖", 50);
                        }, 300);
                        p7Timers.push(t3);
                    });
                }, 200);
                p7Timers.push(t2);
            });
        }, 850);
        p7Timers.push(t1);

    } else {
        p7Opened = false;
        clearP7Timers();
        playPopSound();

        if (scene) scene.classList.remove("open");
        if (btn) btn.textContent = "Open Envelope 💌";

        const title = document.getElementById("p7CardTitle");
        const msg = document.getElementById("p7CardMessage");
        const sig = document.getElementById("p7CardSig");

        if (title) { title.textContent = ""; title.classList.remove("p7-typing"); }
        if (msg) { msg.textContent = ""; msg.classList.remove("p7-typing"); }
        if (sig) { sig.textContent = ""; sig.classList.remove("p7-typing"); }
    }
}

function typeWriter(id, txt, speed, cb) {
    const el = document.getElementById(id);
    if (!el) return;
    el.textContent = "";
    el.classList.add("p7-typing");
    let i = 0;
    function run() {
        if (i < txt.length) {
            el.textContent += txt.charAt(i);
            if (i % 2 === 0) playTypewriterClick();
            i++;
            const t = setTimeout(run, speed);
            p7Timers.push(t);
        } else {
            el.classList.remove("p7-typing");
            if (cb) cb();
        }
    }
    run();
}

/* =========================================================
   PAGE 8 LOGIC (Interactive 3D Gift Box, Candle & Toggle)
========================================================= */
let p8GiftOpened = false;
let p8CandleBlown = false;

function openP8Gift() {
    if (p8GiftOpened) return;
    p8GiftOpened = true;
    startRichBgm();
    playMagicFanfare();
    launchConfetti(65);

    const scene = document.getElementById("p8Scene");
    if (scene) scene.classList.add("open");

    const status = document.getElementById("p8Status");
    if (status) status.innerHTML = "🕯️ Tap the cake to blow out your candle!";
}

function toggleP8Candle() {
    if (!p8GiftOpened) return;
    const cakeWrap = document.getElementById("p8CakeWrap");
    const status = document.getElementById("p8Status");

    if (!p8CandleBlown) {
        p8CandleBlown = true;
        playCandleBlowSound();
        launchConfetti(80);
        if (cakeWrap) cakeWrap.classList.add("blown");
        if (status) status.innerHTML = "✨ Wish Made! Happy Birthday Jyoti! 💕 (Tap to relight)";
    } else {
        p8CandleBlown = false;
        playTone(587.33, 0.2, "sine");
        if (cakeWrap) cakeWrap.classList.remove("blown");
        if (status) status.innerHTML = "🕯️ Candle lit! Tap again to make another wish ✨";
    }
}

/* =========================================================
   COMPLETE REPLAY & FULL RESET (Start Again Engine)
========================================================= */
function startAgainFromBeginning() {
    playMagicFanfare();

    // 1. Reset Page 1
    const p1Btn = document.getElementById("p1StartBtn");
    if (p1Btn) {
        p1Btn.onclick = handleP1Start;
        p1Btn.style.pointerEvents = "auto";
    }

    // 2. Reset Page 2 (Candle Cake & Blow Button)
    p2Blown = false;
    const p2Wrap = document.getElementById("p2Wrap");
    if (p2Wrap) p2Wrap.classList.remove("blown");
    
    const p2BlowBtn = document.getElementById("p2BlowBtn");
    if (p2BlowBtn) {
        p2BlowBtn.style.display = "inline-block";
        p2BlowBtn.style.opacity = "1";
        p2BlowBtn.style.pointerEvents = "auto";
    }
    const p2Wish = document.getElementById("p2Wish");
    if (p2Wish) {
        p2Wish.classList.remove("show");
        p2Wish.style.display = "none";
    }

    // 3. Reset Page 3 (Gift Box, Popped Balloons & Teddy)
    p3Opened = false;
    const p3Scene = document.getElementById("p3Scene");
    if (p3Scene) p3Scene.classList.remove("opened");
    
    document.querySelectorAll("#p3Scene .p3-balloon").forEach(b => {
        b.classList.remove("popped");
        b.style.display = "";
        b.style.opacity = "";
        b.style.transform = "";
        b.style.pointerEvents = "auto";
    });
    document.querySelectorAll(".p3-flower").forEach(f => {
        f.style.transition = "";
        f.style.opacity = "";
        f.style.transform = "";
    });
    const p3NoMsg = document.getElementById("p3NoMsg");
    if (p3NoMsg) p3NoMsg.classList.remove("show");
    resetP3NoBtn();

    // 4. Reset Page 4 (Pop Balloons & Revealed Word Cards)
    p4Popped = 0;
    document.querySelectorAll("#p4Area .p4-balloon").forEach(b => {
        b.classList.remove("popped");
        b.style.display = "";
        b.style.opacity = "";
        b.style.transform = "";
        b.style.pointerEvents = "auto";
    });
    document.querySelectorAll(".p4-word-card").forEach(w => {
        w.classList.remove("show");
    });
    const p4Final = document.getElementById("p4Final");
    if (p4Final) p4Final.classList.remove("show");

    // 5. Reset Page 5 (Compliments Animation)
    p5Ran = false;
    document.querySelectorAll(".p5-compliment-card").forEach(c => {
        c.classList.remove("show");
    });

    // 6. Reset Page 6 (Photo Gallery Slider)
    if (p6Photos && p6Photos.length > 0) {
        showP6Slide(0);
    }

    // 7. Reset Page 7 (Envelope & Letter Typewriter)
    p7Opened = false;
    clearP7Timers();
    const p7Scene = document.getElementById("p7Scene");
    if (p7Scene) p7Scene.classList.remove("open");
    const p7Btn = document.getElementById("p7Btn");
    if (p7Btn) p7Btn.textContent = "Open Envelope 💌";
    
    const cardTitle = document.getElementById("p7CardTitle");
    const cardMsg = document.getElementById("p7CardMessage");
    const cardSig = document.getElementById("p7CardSig");
    if (cardTitle) { cardTitle.textContent = ""; cardTitle.classList.remove("p7-typing"); }
    if (cardMsg) { cardMsg.textContent = ""; cardMsg.classList.remove("p7-typing"); }
    if (cardSig) { cardSig.textContent = ""; cardSig.classList.remove("p7-typing"); }

    // 8. Reset Page 8 (Gift Box, Cake & Candle State)
    p8GiftOpened = false;
    p8CandleBlown = false;
    const p8Scene = document.getElementById("p8Scene");
    if (p8Scene) p8Scene.classList.remove("open");
    const p8CakeWrap = document.getElementById("p8CakeWrap");
    if (p8CakeWrap) p8CakeWrap.classList.remove("blown");
    const p8Status = document.getElementById("p8Status");
    if (p8Status) p8Status.innerHTML = "🎁 Click the gift box to reveal your cake!";

    // 9. Clear Confetti
    confettiParticles = [];
    cCtx.clearRect(0, 0, confettiCanvas.width, confettiCanvas.height);

    // 10. Smoothly Navigate Back to Page 1
    showPage(1);
}

/* Keyboard Arrow Support */
document.addEventListener("keydown", (e) => {
    if (e.key === "ArrowRight") nextPage();
    if (e.key === "ArrowLeft") previousPage();
});
</script>

</body>
</html>
