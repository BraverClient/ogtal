# ogtal
/ogtal-core-system/
  - README.md
  - docs/
      - concept_overview.md
      - feature_list.md
  - src/
      - core/
          - geometryEngine.js
          - codeFlowVisualizer.js
          - networkHub.js
      - ui/
          - 3dCityScene.vue
          - colorThemeSwitcher.vue
          - controlsPanel.vue
      - assets/
          - textures/
          - icons/
          - sounds/
            
Intricate digital core, high-geometry network, interwoven code streams, advanced software interface, glowing circuits, cloud data transfer, polished metallic surfaces, cosmic technology, distributed computing, vibrant energy flows, metallic textures, starfield backdrop, computer script overlay.  
Cyberpunk cityscape, glowing skyscrapers, flying vehicles, neon-lit streets, atmospheric perspective, dynamic viewing angles, interactive energy pulses, customizable color themes, reflections, ultra-detailed, cinematic, 8k.
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Digital Octal Core System</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link href="https://fonts.googleapis.com/css?family=Orbitron:700&display=swap" rel="stylesheet">
  <style>
    body {
      margin: 0;
      padding: 0;
      background: linear-gradient(180deg, #101020 80%, #2efeff 100%);
      font-family: 'Orbitron', Arial, sans-serif;
      color: #fff;
      overflow: hidden;
      min-height: 100vh;
    }
    .digital-core {
      position: absolute;
      left: 50%;
      top: 35%;
      transform: translate(-50%, -50%);
      width: 340px;
      height: 340px;
      background: radial-gradient(circle at 50% 50%, #00fff7 40%, #190033 100%);
      border-radius: 50%;
      box-shadow: 0 0 80px 30px #33fff6, 0 0 10px #fff;
      display: flex;
      align-items: center;
      justify-content: center;
      z-index: 10;
      border: 4px solid #0ff;
      animation: pulse 2s infinite alternate;
    }
    @keyframes pulse {
      0% { box-shadow: 0 0 80px 10px #33fff6, 0 0 10px #fff; }
      100% { box-shadow: 0 0 120px 40px #fff, 0 0 40px #0ff; }
    }
    .core-code {
      font-size: 1.15em;
      color: #fff;
      text-shadow: 0 0 8px #0ff, 0 0 1px #fff;
      font-family: 'Fira Mono', 'Consolas', monospace;
      text-align: center;
      max-width: 85%;
      opacity: 0.85;
      letter-spacing: 0.08em;
      line-height: 1.25;
      user-select: none;
    }
    .cityscape {
      position: absolute;
      bottom: 0;
      left: 0;
      width: 100vw;
      height: 38vh;
      background: linear-gradient(180deg, transparent 60%, #170033 100%);
      z-index: 2;
      display: flex;
      align-items: flex-end;
      overflow: hidden;
    }
    .building {
      width: 40px;
      min-width: 18px;
      height: 120px;
      margin: 0 9px;
      background: linear-gradient(180deg, #0ff 30%, #3f0099 100%);
      border-radius: 4px 4px 8px 8px;
      box-shadow: 0 0 30px 8px #0ff, 0 0 3px #fff;
      position: relative;
      animation: flicker 3s infinite alternate;
    }
    .building:nth-child(odd) {
      height: 70px;
      background: linear-gradient(180deg, #ff00cc 30%, #330066 100%);
      box-shadow: 0 0 26px 5px #ff00cc, 0 0 3px #fff;
      animation-delay: 0.8s;
    }
    .building:nth-child(even) {
      height: 95px;
      background: linear-gradient(180deg, #00ffea 40%, #1a0033 100%);
      box-shadow: 0 0 24px 6px #00ffea, 0 0 2px #fff;
      animation-delay: 1.2s;
    }
    @keyframes flicker {
      0% { filter: brightness(1.05) blur(0.4px);}
      100% { filter: brightness(1.3) blur(1.5px);}
    }
    .flying-vehicle {
      position: absolute;
      left: -60px;
      bottom: 120px;
      width: 55px;
      height: 12px;
      background: linear-gradient(90deg, #0ff 50%, #ff00cc 100%);
      border-radius: 10px 6px 10px 6px;
      box-shadow: 0 0 15px 6px #0ff, 0 0 4px #fff;
      animation: fly 8s linear infinite;
    }
    .flying-vehicle::after {
      content: "";
      position: absolute;
      right: -18px;
      top: 3px;
      width: 15px;
      height: 3px;
      background: linear-gradient(90deg, #fff, #0ff 90%);
      border-radius: 2px;
      opacity: 0.6;
      filter: blur(2px);
    }
    @keyframes fly {
      0% { left: -60px; bottom: 120px;}
      100% { left: 105vw; bottom: 185px;}
    }
    .ui-panel {
      position: absolute;
      top: 28px;
      right: 40px;
      background: rgba(20, 0, 60, 0.85);
      border: 1.5px solid #0ff;
      border-radius: 12px;
      box-shadow: 0 0 18px 1px #0ff;
      padding: 16px 24px 12px 24px;
      z-index: 20;
      display: flex;
      flex-direction: column;
      gap: 10px;
    }
    .ui-panel label, .ui-panel button {
      color: #0ff;
      font-size: 1.1em;
      font-weight: bold;
      letter-spacing: 0.
