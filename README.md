<!--
**Carl-Johnsons/Carl-Johnsons** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
<!-- <p align="left"> <img src="https://komarev.com/ghpvc/?username=Carl-Johnsons&label=Profile%20views&color=0e75b6&style=flat" alt="carl-johnsons" /> </p> -->
<style>
.cool-border {
  position: relative;
  border-radius: 12px;
  overflow:hidden;
background: radial-gradient(circle at top left, #3B82F6, #9333EA);
  z-index: 0;
}

.cool-border::before {
  content: '';
  position: absolute;
  inset: 0;
  padding: 2px; /* thickness of border */
  background: linear-gradient(135deg, #6EE7B7, #3B82F6, #9333EA);
  border-radius: inherit;
  -webkit-mask:
    linear-gradient(#fff 0 0) content-box,
    linear-gradient(#fff 0 0);
  -webkit-mask-composite: xor;
          mask-composite: exclude;
  z-index: -1;
}

.neon-img {
  width: 100%;
  height: 100%;
  object-fit: cover;
  mask-image: linear-gradient(to left, rgba(0, 0, 0, 1) 50%, rgba(0, 0, 0, 0) 100%); /* This creates the fade effect */
  -webkit-mask-image: linear-gradient(to left, rgba(0, 0, 0, 1) 50%, rgba(0, 0, 0, 0) 100%); /* For Safari */
}

.neon-bg-container {
  position: relative;
  width: 100%;
  height: 100%;
}

.neon-bg-container::before {
  content: '';
  position: absolute;
  inset: 0;
  background: radial-gradient(circle at top left, #3B82F6, #9333EA);
  opacity: 0.5; /* Neon glow effect */
  z-index: 1;
}

.neon-bg-container::after {
  content: '';
  position: absolute;
  inset: 0;
  background: transparent;
  mask-image: url('data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy533NyLm9yZy/IF0iPgo8cmVjdCB4PSIwIiB5PSIwIiB3aWR0aD0iMTAwIiBoZWlnaHQ9IjEwMCIgZmlsbD0ibm9uZSIgLz4gCjwvc3ZnPg==');
  animation: particle-fade 1s ease-in-out forwards;
  z-index: 2;
}

.particle-container {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  pointer-events: none;
  z-index: 2;
}

.particle {
  position: absolute;
  width: 10px;
  height: 10px;
  background: #9333EA; /* Particle Color */
  opacity: 0;
  animation: particle-fade 3s ease-in-out infinite;
}

.particle:nth-child(1)  { top: 12%; left: 13%; animation-delay: 1.2s; }
.particle:nth-child(2)  { top: 74%; left: 20%; animation-delay: 2.8s; }
.particle:nth-child(3)  { top: 40%; left: 35%; animation-delay: 5.1s; }
.particle:nth-child(4)  { top: 65%; left: 18%; animation-delay: 0.4s; }
.particle:nth-child(5)  { top: 23%; left: 42%; animation-delay: 3.3s; }
.particle:nth-child(6)  { top: 80%; left: 25%; animation-delay: 6.9s; }
.particle:nth-child(7)  { top: 37%; left: 12%; animation-delay: 0.7s; }
.particle:nth-child(8)  { top: 55%; left: 47%; animation-delay: 2.1s; }
.particle:nth-child(9)  { top: 31%; left: 50%; animation-delay: 1.9s; }
.particle:nth-child(10) { top: 68%; left: 33%; animation-delay: 4.5s; }
.particle:nth-child(11) { top: 90%; left: 29%; animation-delay: 6.2s; }
.particle:nth-child(12) { top: 18%; left: 39%; animation-delay: 1.5s; }
.particle:nth-child(13) { top: 50%; left: 20%; animation-delay: 0.9s; }
.particle:nth-child(14) { top: 72%; left: 14%; animation-delay: 7.1s; }
.particle:nth-child(15) { top: 35%; left: 45%; animation-delay: 3.6s; }

@keyframes particle-fade {
  0% {
    opacity: 1;
    transform: translateX(0) scale(1);
  }
  100% {
    opacity: 0;
    transform: translateX(-150px) scale(0);
  }
}
</style>

<div style="display:flex; justify-content:center;align-items: center;">
<img src="./assets/wallpaper.gif" />
</div>

<h2 align="left"
style="
  font-family: 'Orbitron', sans-serif;
  background: linear-gradient(90deg, #5ee6ff, #a259ff);
  background-clip: text;
  -webkit-background-clip: text;
  color: transparent;
  -webkit-text-fill-color: transparent;
  text-shadow: 0 0 6px #6bc3ff;
"
>Main skills:</h2>
<div class="cool-border" style="
  display: flex;
  flex-direction: row-reverse;
  justify-content: space-between;
">
<div style="flex:2;">
<div class="neon-bg-container">
  <img src="./assets/vertical-neon.gif" class="neon-img" alt="Background Image" />
  <div class="particle-container">
    <!-- Square Particles -->
    <div class="particle"></div>
    <div class="particle"></div>
    <div class="particle"></div>
    <div class="particle"></div>
    <div class="particle"></div>
    <div class="particle"></div>
    <div class="particle"></div>
    <div class="particle"></div>
    <div class="particle"></div>
    <div class="particle"></div>
    <div class="particle"></div>
    <div class="particle"></div>
    <div class="particle"></div>
    <div class="particle"></div>
    <div class="particle"></div>
  </div>
</div>
</div>
<div style="
  padding: 1rem;
  flex: 1;
  display:flex;
  flex-direction: column;
  justify-content: center;
  "> 
  <h4
  style="
    font-family: 'Orbitron', sans-serif;
    background: linear-gradient(90deg, #89f0ff, #d988ff);
    background-clip: text;
    -webkit-background-clip: text;
    color: transparent;
    -webkit-text-fill-color: transparent;
    text-shadow: 0 0 4px #a8e0ff;
  ">Back-end (preferred)</h4>
  <div>
    <a href="https://www.w3schools.com/cs/" target="_blank" rel="noreferrer"> 
      <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/csharp/csharp-original.svg" alt="csharp" width="40" height="40"/>
    </a>
    <a href="https://dotnet.microsoft.com/" target="_blank" rel="noreferrer"> 
      <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/dot-net/dot-net-original-wordmark.svg" alt="dotnet" width="40" height="40"/> 
    </a>
  </div>
  <h4
  style="
    font-family: 'Orbitron', sans-serif;
    background: linear-gradient(90deg, #89f0ff, #d988ff);
    background-clip: text;
    -webkit-background-clip: text;
    color: transparent;
    -webkit-text-fill-color: transparent;
    text-shadow: 0 0 4px #a8e0ff;
  ">Front-end:</h4>
  <div>
    <a href="https://reactjs.org/" target="_blank" rel="noreferrer">
      <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original-wordmark.svg" alt="react" width="40" height="40"/>
    </a>
  <a href="https://expo.dev/" target="_blank" rel="noreferrer">
    <img src="./assets/expo.svg" alt="expo" width="40" height="40"/>
  </a>
  </div>

  <h4
  style="
    font-family: 'Orbitron', sans-serif;
    background: linear-gradient(90deg, #89f0ff, #d988ff);
    background-clip: text;
    -webkit-background-clip: text;
    color: transparent;
    -webkit-text-fill-color: transparent;
    text-shadow: 0 0 4px #a8e0ff;
  "
  >DevOps:</h4>
  <div>
  
  <a href="https://www.docker.com/" target="_blank" rel="noreferrer"> 
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/docker/docker-original-wordmark.svg" alt="docker" width="40" height="40"/> 
  </a>
  <a href="https://nginx.org/">
    <img src="https://www.myqnap.org/wp-content/uploads/nginx-3628948-3030173-1.png" alt="nginx" width="40"/>
  </a>
  <a href="https://developer.hashicorp.com/consul">
    <img src="./assets/consul.svg" alt="consul" width="40"/>
  </a>
  <a href="https://www.dotenv.org/">
    <img src="./assets/env.svg" alt="dotenv" width="40"/>
  </a>
  </div>
  <h4
  style="
    font-family: 'Orbitron', sans-serif;
    background: linear-gradient(90deg, #89f0ff, #d988ff);
    background-clip: text;
    -webkit-background-clip: text;
    color: transparent;
    -webkit-text-fill-color: transparent;
    text-shadow: 0 0 4px #a8e0ff;
  "
  >Database:</h4>
  <div>
  <a href="https://www.mongodb.com/" target="_blank" rel="noreferrer"> 
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mongodb/mongodb-original-wordmark.svg" alt="mongodb" width="40" height="40"/> 
  </a>
  <a href="https://www.microsoft.com/en-us/sql-server" target="_blank" rel="noreferrer">
    <img src="https://www.svgrepo.com/show/303229/microsoft-sql-server-logo.svg" alt="mssql" width="40" height="40"/> 
  </a>
  <a href="https://www.postgresql.org/">
    <img src="https://www.postgresql.org/media/img/about/press/elephant.png" alt="postgresql" width="40"/>
  </a>
  </div>
</div>
</div>
<h2 align="left"
style="
  font-family: 'Orbitron', sans-serif;
  background: linear-gradient(90deg, #5ee6ff, #a259ff);
  background-clip: text;
  -webkit-background-clip: text;
  color: transparent;
  -webkit-text-fill-color: transparent;
  text-shadow: 0 0 6px #6bc3ff;
"
>Cool-looking achievements 🔥:</h2>
<p align="center"> <a href="https://github.com/ryo-ma/github-profile-trophy"><img
width="300" src="https://github-profile-trophy.vercel.app/?username=carl-johnsons&theme=darkhub&row=2&column=3" alt="carl-johnsons" /></a>

<img width="335" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Carl-Johnsons&hide=css,html&theme=aura&layout=donut&hide_border=true" alt="carl-johnsons" />
</p>

<p align="center">
<img width="350" src="https://github-readme-stats.vercel.app/api?username=carl-johnsons&show_icons=true&locale=en&theme=aura&hide_border=true" alt="carl-johnsons" />

<img width="370" src="https://github-readme-streak-stats.herokuapp.com/?user=carl-johnsons&theme=aura&hide_border=true" alt="carl-johnsons" />
</p>

<h2
  style="
    font-family: 'Orbitron', sans-serif;
    background: linear-gradient(90deg, #89f0ff, #d988ff);
    background-clip: text;
    -webkit-background-clip: text;
    color: transparent;
    -webkit-text-fill-color: transparent;
    text-shadow: 0 0 4px #a8e0ff;
  "
>How to reach me:</h2>

- 📫 **ducnlt.it@gmail.com**
- 📫 [Linkedln](https://www.linkedin.com/in/nguy%E1%BB%85n-l%C3%AA-t%C3%A0i-%C4%91%E1%BB%A9c-92a790305/)
