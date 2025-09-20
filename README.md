<!-- Typing SVG Animation -->
<!-- Save this as header.svg -->
<svg xmlns="http://www.w3.org/2000/svg" width="800" height="200" viewBox="0 0 800 200" preserveAspectRatio="xMidYMid meet">
  <defs>
    <!-- gradient for text -->
    <linearGradient id="g" x1="0" x2="1" y1="0" y2="1">
      <stop offset="0%" stop-color="#F75C7E"/>
      <stop offset="40%" stop-color="#FF8A5B"/>
      <stop offset="70%" stop-color="#F7D154"/>
      <stop offset="100%" stop-color="#6EE7B7"/>
    </linearGradient>

    <!-- soft shadow -->
    <filter id="shadow" x="-20%" y="-20%" width="140%" height="140%">
      <feDropShadow dx="0" dy="6" stdDeviation="8" flood-color="#000" flood-opacity="0.15"/>
    </filter>

    <!-- clipping rects we animate for typing -->
    <clipPath id="clip1"><rect id="r1" x="0" y="0" width="0" height="40"></rect></clipPath>
    <clipPath id="clip2"><rect id="r2" x="0" y="0" width="0" height="32"></rect></clipPath>
    <clipPath id="clip3"><rect id="r3" x="0" y="0" width="0" height="32"></rect></clipPath>

    <!-- subtle floating blobs -->
    <radialGradient id="blobGrad"><stop offset="0%" stop-color="#fff" stop-opacity="0.8"/><stop offset="100%" stop-color="#fff" stop-opacity="0"/></radialGradient>
  </defs>

  <!-- background (transparent for README) -->
  <rect width="100%" height="100%" fill="transparent"/>

  <!-- decorative floating blobs -->
  <g transform="translate(620,30)">
    <circle r="18" fill="#F75C7E" opacity="0.18">
      <animate attributeName="cy" values="0;6;0" dur="4s" repeatCount="indefinite"/>
    </circle>
    <circle r="28" cx="40" cy="40" fill="#6EE7B7" opacity="0.12">
      <animateTransform attributeName="transform" attributeType="XML"
        type="translate" values="0 0; -6 3; 0 0" dur="5s" repeatCount="indefinite"/>
    </circle>
  </g>

  <!-- Main text group -->
  <g font-family="Fira Code, 'Courier New', monospace" filter="url(#shadow)" fill="url(#g)" text-anchor="start">
    <!-- Line 1 -->
    <g clip-path="url(#clip1)" transform="translate(40,60)">
      <text x="0" y="0" font-size="28" font-weight="700">
        Hi 👋, I'm Srinivas Chodagiri
      </text>
    </g>
    <!-- Line 2 -->
    <g clip-path="url(#clip2)" transform="translate(40,110)"  >
      <text x="0" y="0" font-size="20" font-weight="600">
        Python Full Stack Developer • AI & ML Enthusiast
      </text>
    </g>
    <!-- Line 3 -->
    <g clip-path="url(#clip3)" transform="translate(40,145)">
      <text x="0" y="0" font-size="18" font-weight="500">
        Passionate Web Developer · Always Learning New Things 💡
      </text>
    </g>

    <!-- blinking cursor placed after the first line's end; its x animates slightly to follow -->
    <rect id="cursor" x="360" y="38" width="8" height="20" rx="2" fill="#111">
      <animate attributeName="opacity" values="1;0;1" dur="1s" repeatCount="indefinite"/>
      <!-- small horizontal wiggle to match typing pace -->
      <animateTransform attributeName="transform" type="translate" values="0 0;2 0;0 0" dur="0.6s" repeatCount="indefinite" />
    </rect>
  </g>

  <!-- Typing animations: animate clip widths to reveal text -->
  <animate
    xlink:href="#r1"
    attributeName="width"
    from="0" to="520"
    dur="2.4s"
    begin="0s"
    fill="freeze"
    calcMode="paced"/>

  <animate
    xlink:href="#r2"
    attributeName="width"
    from="0" to="650"
    dur="2.8s"
    begin="2.6s"
    fill="freeze"
    calcMode="paced"/>

  <animate
    xlink:href="#r3"
    attributeName="width"
    from="0" to="700"
    dur="2.8s"
    begin="5.6s"
    fill="freeze"
    calcMode="paced"/>

  <!-- subtle appearance for cursor after line 1 finishes -->
  <animate
    xlink:href="#cursor"
    attributeName="x"
    from="360" to="730"
    dur="2.8s"
    begin="5.6s"
    fill="freeze"
    calcMode="linear"/>

  <!-- gentle shimmer across the gradient to make it lively -->
  <rect x="-200" y="0" width="1200" height="200" fill="url(#g)" opacity="0.06">
    <animateTransform attributeName="transform" type="translate" values="-200 0;200 0;-200 0" dur="6s" repeatCount="indefinite"/>
  </rect>

  <!-- small footer note (optional, non-animated) -->
  <text x="40" y="189" font-size="11" fill="#666">Open to work • Projects: Python, Web, ML</text>
</svg>
<!-- Waving Hand GIF -->
<h1 align="center">Hi there! <img src="https://raw.githubusercontent.com/MartinHeinz/MartinHeinz/master/wave.gif" width="40"></h1>
<h3 align="center">🚀 Aspiring AI/ML Engineer | Python Full Stack Developer | Web Enthusiast</h3>

---

### 🌟 About Me
- 🎓 B.Tech in **Computer Science (AI & ML)** – KIET Kakinada  
- 💡 Passionate about **Python Full Stack Development & AI-driven applications**  
- 🔭 Worked on **Fake Job Post Detection using NLP** (Python, TF-IDF, Random Forest)  
- 🌱 Currently enhancing skills in **Python Full Stack & Machine Learning**  
- 💬 Ask me about **Python, AI/ML, Flask, Django, SQL, Web Development**  
- ⚡ Fun fact: *Coding + Coffee = Happiness ☕💻*  

---

### 🔗 Connect with Me
<p align="center">
<a href="mailto:Chodagirisrinivas2@gmail.com"><img src="https://img.shields.io/badge/-Email-D14836?style=for-the-badge&logo=gmail&logoColor=white"></a>
<a href="https://www.linkedin.com/in/srinivas-chodagiri-306750246/"><img src="https://img.shields.io/badge/-LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"></a>
<a href="https://github.com/Srini612"><img src="https://img.shields.io/badge/-GitHub-181717?style=for-the-badge&logo=github&logoColor=white"></a>
</p>

---

### 🛠️ Tech Stack
<p align="center">
<img src="https://skillicons.dev/icons?i=python,html,css,javascript,bootstrap,mysql,flask,django,git,github,vscode&perline=6" />
</p>

---

### 📚 Certifications
- 🐍 Python Programming – EDYST  
- 🤖 Foundations of Modern Machine Learning – IIIT Hyderabad  
- 🌐 HTML & CSS – Infosys Springboard  

---

### 💼 Internships
- 🔹 **Flask Framework Intern – IIIT Hyderabad**  
   - Built RESTful APIs & deployed backend solutions.  
- 🔹 **Web Development Intern – Eduskills**  
   - Developed responsive & interactive web pages (HTML, CSS, JS).  

---

### 🚀 Projects
- 🧑‍💻 **Fake Job Post Detection (Python, NLP, ML)**  
- 🎨 **Personal Portfolio Website (HTML, CSS, JS)**  
- 🍔 **Burger King & KFC Clone Websites (HTML, CSS)**  

---

### 📊 GitHub Stats
<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Srini612&show_icons=true&theme=radical" height="150"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Srini612&layout=compact&theme=radical" height="150"/>
</p>

---

### 🔥 Streak Stats
<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=Srini612&theme=radical" alt="streak" />
</p>

---

### ⚡ Fun Animations
<p align="center">
  <img src="https://raw.githubusercontent.com/abhisheknaiidu/abhisheknaiidu/master/code.gif" width="400" alt="coding animation"/>
</p>

---

### 💡 Quote
<p align="center">
<i>"Code is like humor. When you have to explain it, it’s bad."</i>
</p>

<!--
**Srini612/Srini612** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

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
