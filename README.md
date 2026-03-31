<div align="center">

<h1 class="neon">Avtomo'jiza</h1>

<p class="typing">AI Developer | Bot Builder | Minecraft Creator</p>

<p class="float">🚀 Welcome to my GitHub</p>

<p class="gradient">Coding • Creating • Dominating</p>

<div class="terminal">
  <p>> Initializing system...</p>
  <p>> Loading AI modules...</p>
  <p>> Building bots...</p>
  <p>> Status: <span class="online">ONLINE</span></p>
</div>

</div>

<style>

body {
  background: #0d1117;
}

/* NEON TEXT */
.neon {
  font-size: 50px;
  color: #0ff;
  animation: glow 1.5s ease-in-out infinite alternate;
}

@keyframes glow {
  from {
    text-shadow: 0 0 10px #0ff, 0 0 20px #0ff;
  }
  to {
    text-shadow: 0 0 25px #00f7ff, 0 0 40px #00f7ff;
  }
}

/* TYPING */
.typing {
  width: 0;
  overflow: hidden;
  white-space: nowrap;
  border-right: 3px solid #00ffcc;
  font-size: 20px;
  margin: auto;
  animation: typing 5s steps(40, end) infinite, blink 0.7s infinite;
}

@keyframes typing {
  0% { width: 0 }
  50% { width: 100% }
  100% { width: 0 }
}

@keyframes blink {
  50% { border-color: transparent }
}

/* FLOAT */
.float {
  margin-top: 20px;
  font-size: 22px;
  animation: float 3s ease-in-out infinite;
}

@keyframes float {
  0% { transform: translateY(0px); }
  50% { transform: translateY(-12px); }
  100% { transform: translateY(0px); }
}

/* GRADIENT */
.gradient {
  font-size: 26px;
  margin-top: 10px;
  background: linear-gradient(270deg, #00f7ff, #ff00ff, #00ff00);
  background-size: 600% 600%;
  -webkit-background-clip: text;
  color: transparent;
  animation: gradientMove 6s ease infinite;
}

@keyframes gradientMove {
  0% { background-position: 0% }
  50% { background-position: 100% }
  100% { background-position: 0% }
}

/* TERMINAL */
.terminal {
  margin-top: 30px;
  background: black;
  color: #00ff00;
  padding: 15px;
  width: fit-content;
  border-radius: 10px;
  font-family: monospace;
  box-shadow: 0 0 15px #00ff00;
  animation: flicker 2s infinite;
}

@keyframes flicker {
  0% { opacity: 1; }
  50% { opacity: 0.85; }
  100% { opacity: 1; }
}

.online {
  color: #00ff00;
  font-weight: bold;
  animation: blinkOnline 1s infinite;
}

@keyframes blinkOnline {
  50% { opacity: 0; }
}

</style>
