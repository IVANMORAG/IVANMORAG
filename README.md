<div align="center" style="margin: 20px;">
  <svg width="800" height="400" viewBox="0 0 800 400" xmlns="http://www.w3.org/2000/svg" style="background: #0d1117; border: 4px double #0ff; box-shadow: 0 0 30px #f0f, 0 0 60px #0ff;">
    <!-- Definiciones de filtros -->
    <defs>
      <!-- Filtro neón cyan -->
      <filter id="neon" x="-20%" y="-20%" width="140%" height="140%">
        <feGaussianBlur stdDeviation="5" result="blur" />
        <feFlood flood-color="#00ffff" result="color" />
        <feComposite in="color" in2="blur" operator="in" result="glow" />
        <feMerge>
          <feMergeNode in="glow" />
          <feMergeNode in="SourceGraphic" />
        </feMerge>
      </filter>
      <!-- Filtro neón rosa -->
      <filter id="neon-pink" x="-20%" y="-20%" width="140%" height="140%">
        <feGaussianBlur stdDeviation="5" result="blur" />
        <feFlood flood-color="#ff00ff" result="color" />
        <feComposite in="color" in2="blur" operator="in" result="glow" />
        <feMerge>
          <feMergeNode in="glow" />
          <feMergeNode in="SourceGraphic" />
        </feMerge>
      </filter>
      <!-- Filtro para líneas neón cyan -->
      <filter id="neon-cyan" x="-20%" y="-20%" width="140%" height="140%">
        <feGaussianBlur stdDeviation="3" result="blur" />
        <feFlood flood-color="#00ffff" result="color" />
        <feComposite in="color" in2="blur" operator="in" result="glow" />
        <feMerge>
          <feMergeNode in="glow" />
          <feMergeNode in="SourceGraphic" />
        </feMerge>
      </filter>
    </defs>
    
    <!-- Fondo y cuadrícula cyberpunk -->
    <rect width="100%" height="100%" fill="#0d1117" />
    <!-- Cuadrícula horizontal -->
    <g>
      <line x1="0" y1="50" x2="800" y2="50" stroke="rgba(0, 255, 255, 0.2)" stroke-width="0.5" />
      <line x1="0" y1="100" x2="800" y2="100" stroke="rgba(0, 255, 255, 0.2)" stroke-width="0.5" />
      <line x1="0" y1="150" x2="800" y2="150" stroke="rgba(0, 255, 255, 0.2)" stroke-width="0.5" />
      <line x1="0" y1="200" x2="800" y2="200" stroke="rgba(0, 255, 255, 0.2)" stroke-width="0.5" />
      <line x1="0" y1="250" x2="800" y2="250" stroke="rgba(0, 255, 255, 0.2)" stroke-width="0.5" />
      <line x1="0" y1="300" x2="800" y2="300" stroke="rgba(0, 255, 255, 0.2)" stroke-width="0.5" />
      <line x1="0" y1="350" x2="800" y2="350" stroke="rgba(0, 255, 255, 0.2)" stroke-width="0.5" />
    </g>
    <!-- Cuadrícula vertical -->
    <g>
      <line x1="100" y1="0" x2="100" y2="400" stroke="rgba(0, 255, 255, 0.2)" stroke-width="0.5" />
      <line x1="200" y1="0" x2="200" y2="400" stroke="rgba(0, 255, 255, 0.2)" stroke-width="0.5" />
      <line x1="300" y1="0" x2="300" y2="400" stroke="rgba(0, 255, 255, 0.2)" stroke-width="0.5" />
      <line x1="400" y1="0" x2="400" y2="400" stroke="rgba(0, 255, 255, 0.2)" stroke-width="0.5" />
      <line x1="500" y1="0" x2="500" y2="400" stroke="rgba(0, 255, 255, 0.2)" stroke-width="0.5" />
      <line x1="600" y1="0" x2="600" y2="400" stroke="rgba(0, 255, 255, 0.2)" stroke-width="0.5" />
      <line x1="700" y1="0" x2="700" y2="400" stroke="rgba(0, 255, 255, 0.2)" stroke-width="0.5" />
    </g>
    
    <!-- Líneas decorativas neón -->
    <path d="M 50,50 L 750,50 L 750,350 L 50,350 Z" fill="none" stroke="#fff" stroke-width="2" filter="url(#neon-cyan)" />
    <path d="M 100,100 L 700,100 L 700,300 L 100,300 Z" fill="none" stroke="#fff" stroke-width="2" filter="url(#neon-cyan)" />
    
    <!-- Textos con efectos neón -->
    <text x="400" y="130" text-anchor="middle" font-family="Arial, sans-serif" font-weight="bold" font-size="60" fill="#fff" filter="url(#neon)">IVÁN MORA</text>
    <text x="400" y="200" text-anchor="middle" font-family="Arial, sans-serif" font-weight="bold" font-size="30" fill="#fff" filter="url(#neon-pink)">DESARROLLADOR FULL STACK</text>
    <text x="400" y="270" text-anchor="middle" font-family="Arial, sans-serif" font-weight="bold" font-size="24" fill="#fff" filter="url(#neon)">SISTEMAS COMPUTACIONALES</text>
    
    <!-- Elementos decorativos -->
    <circle cx="150" cy="330" r="10" fill="none" stroke="#ff00ff" filter="url(#neon-pink)" />
    <circle cx="650" cy="330" r="10" fill="none" stroke="#00ffff" filter="url(#neon)" />
    <rect x="100" y="310" width="600" height="2" fill="#ff00ff" filter="url(#neon-pink)" />
  </svg>
</div>

<div align="center" style="margin: 20px;">
  <p style="color: #ff0; font-size: 1.5em; text-shadow: 0 0 10px #ff0;">💥🌟 LOADING CHAOS MODE 🌟💥</p>
</div>

---

<div align="center" style="margin: 40px;">
  <h2 style="color: #ff0; font-size: 3em; text-shadow: 0 0 15px #ff0, 3px 3px 0 #f0f, -3px -3px 0 #0ff;">🌩️ CÓDIGO EN MIS VENAS</h2>
  <div style="background: linear-gradient(45deg, #1a1a1a, #2a2a2a); padding: 25px; border: 4px solid #f0f; box-shadow: 0 0 25px #f0f, 0 0 50px #0ff; border-radius: 20px; max-width: 800px; color: #ccc; transform: skew(-8deg);">
    <p>⚡️ <span style="color: #0ff; text-shadow: 0 0 5px #0ff;">Hackeando:</span> React, Spring Boot, AWS 🦠</p>
    <p>💥 <span style="color: #0ff; text-shadow: 0 0 5px #0ff;">Misión:</span> Crear tech que explote mentes 🚀</p>
    <p>🌀 <span style="color: #0ff; text-shadow: 0 0 5px #0ff;">Mantra:</span> <i>"El código es arte, los bugs son galaxias"</i> 🌌</p>
  </div>
</div>

---

<div align="center" style="margin: 40px;">
  <h2 style="color: #ff0; font-size: 3em; text-shadow: 0 0 15px #ff0, 3px 3px 0 #f0f, -3px -3px 0 #0ff;">🛠 ARSENAL NEON</h2>
  <table style="border: 4px double #0ff; box-shadow: 0 0 25px #0ff, 0 0 50px #f0f, 0 0 75px #ff0; background: #1a1a1a; color: #ccc; border-radius: 20px; width: 95%; max-width: 1000px; transform: rotate(-5deg);">
    <tr style="background: linear-gradient(90deg, #2a2a2a, #1a1a1a);">
      <th style="color: #f0f; padding: 15px; border-bottom: 3px solid #0ff; text-shadow: 0 0 5px #f0f;">Área</th>
      <th style="color: #f0f; padding: 15px; border-bottom: 3px solid #0ff; text-shadow: 0 0 5px #f0f;">Tecnologías</th>
      <th style="color: #f0f; padding: 15px; border-bottom: 3px solid #0ff; text-shadow: 0 0 5px #f0f;">Nivel</th>
    </tr>
    <tr style="background: linear-gradient(90deg, #1a1a1a, #2a2a2a);">
      <td style="padding: 15px; text-align: center;">Frontend</td>
      <td style="padding: 15px; text-align: center;">HTML5, CSS3, React</td>
      <td style="padding: 15px; text-align: center;">🌟🌟🌟🌟☆</td>
    </tr>
    <tr style="background: linear-gradient(90deg, #2a2a2a, #1a1a1a);">
      <td style="padding: 15px; text-align: center;">Backend</td>
      <td style="padding: 15px; text-align: center;">Java, Spring, Laravel</td>
      <td style="padding: 15px; text-align: center;">🌟🌟🌟☆☆</td>
    </tr>
    <tr style="background: linear-gradient(90deg, #1a1a1a, #2a2a2a);">
      <td style="padding: 15px; text-align: center;">Bases de Datos</td>
      <td style="padding: 15px; text-align: center;">MySQL</td>
      <td style="padding: 15px; text-align: center;">🌟🌟🌟🌟☆</td>
    </tr>
  </table>
</div>

---

<div align="center" style="margin: 40px;">
  <h2 style="color: #ff0; font-size: 3em; text-shadow: 0 0 15px #ff0, 3px 3px 0 #f0f, -3px -3px 0 #0ff;">🏆 LOGROS HACKERS</h2>
  <div style="background: linear-gradient(45deg, #1a1a1a, #2a2a2a); padding: 25px; border: 4px solid #ff0; box-shadow: 0 0 25px #ff0, 0 0 50px #f0f; border-radius: 20px; max-width: 800px; color: #ccc; transform: skew(8deg);">
    <p>🧨 <span style="color: #0ff;">Cazador de Bugs:</span> 100+ errores aniquilados</p>
    <p>🌠 <span style="color: #0ff;">Nave Espacial:</span> Creador de apps que orbitan</p>
    <p>💣 <span style="color: #0ff;">Caos Controlado:</span> <i>Maestro del debug galáctico</i></p>
  </div>
</div>

---

<div align="center" style="margin: 40px;">
  <h2 style="color: #ff0; font-size: 3em; text-shadow: 0 0 15px #ff0, 3px 3px 0 #f0f, -3px -3px 0 #0ff;">📡 SEÑAL CÓSMICA</h2>
  <div style="background: linear-gradient(45deg, #1a1a1a, #2a2a2a); padding: 25px; border: 4px solid #f0f; box-shadow: 0 0 25px #f0f, 0 0 50px #0ff; border-radius: 20px; max-width: 800px;">
    <p>
      <a href="https://www.tiktok.com/@ivan_morag" style="color: #0ff; text-decoration: none; text-shadow: 0 0 8px #0ff;">🎵 TikTok</a>  • 
      <a href="https://www.instagram.com/ivn_mg" style="color: #0ff; text-decoration: none; text-shadow: 0 0 8px #0ff;">📸 Instagram</a>  • 
      <a href="https://www.linkedin.com/in/iván-mora-1a70942a7" style="color: #0ff; text-decoration: none; text-shadow: 0 0 8px #0ff;">💼 LinkedIn</a>  • 
      <a href="mailto:ivanmoragarcia412@gmail.com" style="color: #0ff; text-decoration: none; text-shadow: 0 0 8px #0ff;">✉️ Email</a>
    </p>
  </div>
</div>

---

<div align="center" style="margin: 20px;">
  <p style="color: #ff0; font-size: 1.5em; text-shadow: 0 0 10px #ff0;">🪐🌟 SYSTEM OVERLOAD 🌟🪐</p>
</div>

<div align="center" style="background: linear-gradient(135deg, #000, #1a1a1a); padding: 30px; border: 5px double #0ff; box-shadow: 0 0 30px #f0f, 0 0 60px #0ff, 0 0 90px #ff0; border-radius: 25px; margin-top: 20px;">
  <p style="color: #ccc; font-style: italic;">🌃 Forjado en un reactor de código y neon</p>
  <p style="color: #ff0; font-size: 2em; text-shadow: 0 0 15px #ff0, 3px 3px 0 #f0f;">💥 ¡Únete a la revolución digital!</p>
</div>
