<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&height=200&section=header&reversal=false&fontSize=70&fontColor=FFFFFF&fontAlign=50&fontAlignY=50&stroke=-&descSize=20&descAlign=50&descAlignY=50&theme=cobalt" width="100%" />
</div>

###

<style>
  @keyframes gradientBG {
    0% { background-position: 0% 50%; }
    50% { background-position: 100% 50%; }
    100% { background-position: 0% 50%; }
  }
  
  @keyframes float {
    0% { transform: translateY(0px); }
    50% { transform: translateY(-10px); }
    100% { transform: translateY(0px); }
  }
  
  @keyframes glow {
    0% { box-shadow: 0 0 20px rgba(102, 126, 234, 0.3); }
    50% { box-shadow: 0 0 40px rgba(102, 126, 234, 0.6); }
    100% { box-shadow: 0 0 20px rgba(102, 126, 234, 0.3); }
  }
  
  @keyframes slideInLeft {
    from {
      opacity: 0;
      transform: translateX(-30px);
    }
    to {
      opacity: 1;
      transform: translateX(0);
    }
  }
  
  @keyframes slideInRight {
    from {
      opacity: 0;
      transform: translateX(30px);
    }
    to {
      opacity: 1;
      transform: translateX(0);
    }
  }
  
  @keyframes scaleIn {
    from {
      opacity: 0;
      transform: scale(0.8);
    }
    to {
      opacity: 1;
      transform: scale(1);
    }
  }
  
  .main-title {
    font-size: 42px;
    font-weight: bold;
    background: linear-gradient(135deg, #667eea 0%, #764ba2 50%, #f093fb 100%);
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
    background-size: 200% 200%;
    animation: gradientBG 3s ease infinite;
    text-shadow: none;
    margin: 20px 0;
  }
  
  .section-title {
    font-size: 28px;
    font-weight: bold;
    color: #667eea;
    border-bottom: 3px solid transparent;
    border-image: linear-gradient(135deg, #667eea, #764ba2, #f093fb);
    border-image-slice: 1;
    padding-bottom: 10px;
    display: inline-block;
    animation: slideInLeft 0.8s ease-out;
  }
  
  .about-box {
    background: linear-gradient(135deg, rgba(102, 126, 234, 0.08), rgba(118, 75, 162, 0.08));
    backdrop-filter: blur(10px);
    border-radius: 20px;
    padding: 25px 30px;
    border: 1px solid rgba(102, 126, 234, 0.2);
    animation: slideInRight 0.8s ease-out;
    transition: all 0.5s ease;
  }
  
  .about-box:hover {
    transform: translateY(-5px);
    box-shadow: 0 10px 40px rgba(102, 126, 234, 0.2);
    border-color: rgba(102, 126, 234, 0.5);
  }
  
  .language-badge {
    display: inline-block;
    padding: 6px 18px;
    border-radius: 50px;
    font-size: 14px;
    font-weight: bold;
    margin: 4px 6px;
    animation: float 3s ease-in-out infinite;
    transition: all 0.3s ease;
    cursor: default;
  }
  
  .language-badge:hover {
    transform: scale(1.1);
    box-shadow: 0 5px 20px rgba(0, 0, 0, 0.2);
  }
  
  .language-badge.native { 
    background: linear-gradient(135deg, #f093fb 0%, #f5576c 100%);
    color: white;
    animation-delay: 0s;
  }
  
  .language-badge.technical { 
    background: linear-gradient(135deg, #4facfe 0%, #00f2fe 100%);
    color: white;
    animation-delay: 0.5s;
  }
  
  .language-badge.intermediate { 
    background: linear-gradient(135deg, #43e97b 0%, #38f9d7 100%);
    color: #2d3748;
    animation-delay: 1s;
  }
  
  .language-badge.basic { 
    background: linear-gradient(135deg, #fa709a 0%, #fee140 100%);
    color: #2d3748;
    animation-delay: 1.5s;
  }
  
  .interest-item {
    padding: 12px 20px;
    border-radius: 12px;
    background: linear-gradient(135deg, rgba(102, 126, 234, 0.05), rgba(118, 75, 162, 0.05));
    border-left: 4px solid #667eea;
    margin: 8px 0;
    transition: all 0.4s ease;
    cursor: default;
    animation: slideInLeft 0.6s ease-out;
    animation-fill-mode: both;
  }
  
  .interest-item:nth-child(1) { animation-delay: 0.1s; }
  .interest-item:nth-child(2) { animation-delay: 0.2s; }
  .interest-item:nth-child(3) { animation-delay: 0.3s; }
  .interest-item:nth-child(4) { animation-delay: 0.4s; }
  .interest-item:nth-child(5) { animation-delay: 0.5s; }
  
  .interest-item:hover {
    transform: translateX(15px) scale(1.02);
    background: linear-gradient(135deg, rgba(102, 126, 234, 0.15), rgba(118, 75, 162, 0.15));
    border-left-color: #764ba2;
    box-shadow: 0 5px 25px rgba(102, 126, 234, 0.2);
  }
  
  .project-item {
    padding: 15px 25px;
    border-radius: 15px;
    background: linear-gradient(135deg, rgba(102, 126, 234, 0.05), rgba(118, 75, 162, 0.05));
    border: 1px solid rgba(102, 126, 234, 0.2);
    margin: 12px 0;
    transition: all 0.4s ease;
    animation: scaleIn 0.6s ease-out;
    animation-fill-mode: both;
    cursor: default;
  }
  
  .project-item:nth-child(1) { animation-delay: 0.2s; }
  .project-item:nth-child(2) { animation-delay: 0.4s; }
  
  .project-item:hover {
    transform: translateY(-5px) scale(1.02);
    background: linear-gradient(135deg, rgba(102, 126, 234, 0.15), rgba(118, 75, 162, 0.15));
    border-color: #667eea;
    box-shadow: 0 10px 40px rgba(102, 126, 234, 0.25);
  }
  
  .project-item strong {
    color: #667eea;
  }
  
  .social-icon {
    display: inline-block;
    margin: 0 12px;
    transition: all 0.4s cubic-bezier(0.175, 0.885, 0.32, 1.275);
  }
  
  .social-icon:hover {
    transform: translateY(-8px) scale(1.15);
    filter: drop-shadow(0 8px 25px rgba(102, 126, 234, 0.5));
  }
  
  .social-icon img {
    border-radius: 50%;
    transition: all 0.3s ease;
  }
  
  .social-icon:hover img {
    box-shadow: 0 0 30px rgba(102, 126, 234, 0.4);
  }
  
  .tech-badge {
    display: inline-block;
    margin: 6px;
    transition: all 0.3s cubic-bezier(0.175, 0.885, 0.32, 1.275);
    animation: scaleIn 0.5s ease-out;
    animation-fill-mode: both;
  }
  
  .tech-badge:nth-child(1) { animation-delay: 0.05s; }
  .tech-badge:nth-child(2) { animation-delay: 0.1s; }
  .tech-badge:nth-child(3) { animation-delay: 0.15s; }
  .tech-badge:nth-child(4) { animation-delay: 0.2s; }
  /* ... y así sucesivamente para todos los badges */
  
  .tech-badge:hover {
    transform: translateY(-5px) scale(1.08) rotate(-2deg);
    filter: drop-shadow(0 8px 25px rgba(0, 0, 0, 0.3));
  }
  
  .donate-button {
    display: inline-block;
    transition: all 0.4s cubic-bezier(0.175, 0.885, 0.32, 1.275);
    animation: float 3s ease-in-out infinite;
  }
  
  .donate-button:hover {
    transform: scale(1.1) rotate(-3deg);
    filter: drop-shadow(0 10px 40px rgba(0, 68, 92, 0.5));
  }
  
  .pollo-gif {
    animation: float 4s ease-in-out infinite;
    border-radius: 50%;
    box-shadow: 0 0 40px rgba(102, 126, 234, 0.3);
    transition: all 0.5s ease;
  }
  
  .pollo-gif:hover {
    transform: scale(1.1) rotate(5deg);
    box-shadow: 0 0 60px rgba(102, 126, 234, 0.6);
  }
  
  .contact-box {
    background: linear-gradient(135deg, rgba(102, 126, 234, 0.08), rgba(118, 75, 162, 0.08));
    border-radius: 20px;
    padding: 25px 30px;
    border: 2px solid transparent;
    background-image: linear-gradient(white, white), linear-gradient(135deg, #667eea, #764ba2);
    background-origin: padding-box, border-box;
    background-clip: padding-box, border-box;
    animation: glow 3s ease-in-out infinite;
    transition: all 0.5s ease;
  }
  
  .contact-box:hover {
    transform: translateY(-5px);
    box-shadow: 0 10px 50px rgba(102, 126, 234, 0.3);
  }
  
  .section-container {
    max-width: 900px;
    margin: 0 auto;
    padding: 0 20px;
  }
  
  .badge-container {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 8px;
  }
</style>

###

<div align="center" class="section-container">
  <h1 class="main-title">✨ ¡Bienvenido a mi repositorio! ✨</h1>
  
  <div style="width: 100px; height: 4px; background: linear-gradient(90deg, #667eea, #764ba2, #f093fb); margin: 10px auto; border-radius: 2px;"></div>
</div>

###

<div align="left" class="section-container">
  <h2 class="section-title">🌙 Acerca de mí</h2>
</div>

###

<div align="left" class="section-container">
  <div class="about-box">
    <p style="font-size: 17px; line-height: 1.8; margin: 0;">
      ¡Hola! Soy <strong style="color: #667eea; font-size: 19px;">Deivyd Saúl Vidal Ortiz</strong>, un <strong>desarrollador apasionado</strong> por la tecnología y la innovación. 
      Me especializo en el desarrollo de aplicaciones móviles, plataformas web y herramientas digitales que 
      facilitan la vida de las personas. 🚀
      <br><br>
      🎓 <strong>Formación:</strong> Estudiante autodidacta con experiencia en múltiples lenguajes de programación 
      y frameworks modernos. Siempre estoy en constante aprendizaje para mantenerme actualizado con las últimas 
      tendencias tecnológicas.
      <br><br>
      💡 <strong>Filosofía de trabajo:</strong> Creo en el poder del código limpio, la colaboración y la mejora continua. 
      Cada proyecto es una oportunidad para aprender, innovar y crear soluciones que marquen la diferencia.
      <br><br>
      <strong>🌍 Idiomas:</strong><br>
      <span class="language-badge native">🇪🇸 Español - Nativo</span>
      <span class="language-badge technical">🇬🇧 Inglés - Técnico</span>
      <span class="language-badge intermediate">🇫🇷 Francés - Intermedio</span>
      <span class="language-badge basic">🇹🇭 Tailandés - Básico</span>
      <br><br>
      🎯 <strong>Objetivo actual:</strong> Consolidar mis habilidades como desarrollador full-stack y contribuir a 
      proyectos de código abierto que tengan un impacto positivo en la comunidad tecnológica.
    </p>
  </div>
</div>

###

<div align="left" class="section-container">
  <h2 class="section-title">🚀 Áreas de Interés</h2>
</div>

###

<div align="left" class="section-container">
  <ul style="list-style: none; padding: 0; font-size: 17px;">
    <li class="interest-item">📱 <strong>Desarrollo de aplicaciones móviles Android</strong></li>
    <li class="interest-item">🌐 <strong>Desarrollo y diseño web</strong></li>
    <li class="interest-item">🤖 <strong>Automatización e ingeniería IA</strong></li>
    <li class="interest-item">🔬 <strong>Investigación en tecnología del día a día</strong></li>
    <li class="interest-item">💻 <strong>Desarrollo de programas y sistemas</strong></li>
  </ul>
</div>

###

<div align="left" class="section-container">
  <h2 class="section-title">📂 Proyectos Destacados</h2>
</div>

###

<div align="left" class="section-container">
  <ul style="list-style: none; padding: 0; font-size: 16px;">
    <li class="project-item">
      <strong>🔹 Senati Manager</strong><br>
      <span style="color: #4a5568;">Aplicación móvil diseñada para estudiantes de SENATI que ofrece herramientas de apoyo, soporte de ayuda y conexiones con más recursos educativos.</span>
    </li>
    <li class="project-item">
      <strong>🔹 Temas Diferentes</strong><br>
      <span style="color: #4a5568;">Mi sitio web oficial donde comparto contenido variado sobre tecnología, desarrollo y temas de interés general.</span>
    </li>
  </ul>
</div>

###

<div align="left" class="section-container">
  <h2 class="section-title">📫 Contacto y Colaboración</h2>
</div>

###

<div align="left" class="section-container">
  <div class="contact-box">
    <p style="font-size: 17px; line-height: 1.8; margin: 0;">
      💬 Si deseas colaborar en algún proyecto, sugerir mejoras o simplemente compartir ideas, no dudes en contactarme. 
      Estoy abierto a nuevas oportunidades y desafíos que me permitan crecer profesionalmente y aportar valor a la comunidad.
      <br><br>
      🌐 <strong style="color: #667eea;">GitHub:</strong> <a href="https://github.com/PolloCraft" target="_blank" style="color: #764ba2; text-decoration: none; font-weight: bold;">github.com/PolloCraft</a>
    </p>
  </div>
</div>

###

<div align="left" class="section-container">
  <h2 class="section-title">🌐 Redes Sociales</h2>
</div>

###

<div align="center" class="section-container">
  <div style="padding: 20px; background: linear-gradient(135deg, rgba(102, 126, 234, 0.05), rgba(118, 75, 162, 0.05)); border-radius: 20px;">
    <a href="https://www.facebook.com/profile.php?id=100094099170367" target="_blank" class="social-icon">
      <img src="https://raw.githubusercontent.com/CLorant/readme-social-icons/097d0b23dcc0d22ba7710f6c113fafd321624a79/large/filled/facebook.svg" width="45" height="45" />
    </a>
    <a href="https://www.instagram.com/pollocraft20/" target="_blank" class="social-icon">
      <img src="https://raw.githubusercontent.com/CLorant/readme-social-icons/097d0b23dcc0d22ba7710f6c113fafd321624a79/large/filled/instagram.svg" width="45" height="45" />
    </a>
    <a href="https://www.linkedin.com/in/deivyd-saul-vidal-ortiz-40756339b/" target="_blank" class="social-icon">
      <img src="https://raw.githubusercontent.com/CLorant/readme-social-icons/097d0b23dcc0d22ba7710f6c113fafd321624a79/large/filled/linkedin.svg" width="45" height="45" />
    </a>
    <a href="https://www.tiktok.com/@pollocraft20_fimf?lang=es" target="_blank" class="social-icon">
      <img src="https://raw.githubusercontent.com/CLorant/readme-social-icons/097d0b23dcc0d22ba7710f6c113fafd321624a79/large/filled/tiktok.svg" width="45" height="45" />
    </a>
    <a href="https://www.youtube.com/@PolloCraft20_FIMF" target="_blank" class="social-icon">
      <img src="https://raw.githubusercontent.com/CLorant/readme-social-icons/097d0b23dcc0d22ba7710f6c113fafd321624a79/large/filled/youtube.svg" width="45" height="45" />
    </a>
  </div>
</div>

###

<div align="left" class="section-container">
  <h2 class="section-title">💻 Mis Conocimientos</h2>
</div>

###

<div align="center" class="section-container">
  <div class="badge-container" style="background: linear-gradient(135deg, rgba(102, 126, 234, 0.03), rgba(118, 75, 162, 0.03)); padding: 20px; border-radius: 20px;">
    <span class="tech-badge"><img src="https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white" /></span>
    <span class="tech-badge"><img src="https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white" /></span>
    <span class="tech-badge"><img src="https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E" /></span>
    <span class="tech-badge"><img src="https://img.shields.io/badge/lua-%232C2D72.svg?style=for-the-badge&logo=lua&logoColor=white" /></span>
    <span class="tech-badge"><img src="https://img.shields.io/badge/kotlin-%237F52FF.svg?style=for-the-badge&logo=kotlin&logoColor=white" /></span>
    <span class="tech-badge"><img src="https://img.shields.io/badge/php-%23777BB4.svg?style=for-the-badge&logo=php&logoColor=white" /></span>
    <span class="tech-badge"><img src="https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54" /></span>
    <span class="tech-badge"><img src="https://img.shields.io/badge/Windows%20Terminal-%234D4D4D.svg?style=for-the-badge&logo=windows-terminal&logoColor=white" /></span>
    <span class="tech-badge"><img src="https://img.shields.io/badge/azure-%230072C6.svg?style=for-the-badge&logo=microsoftazure&logoColor=white" /></span>
    <span class="tech-badge"><img src="https://img.shields.io/badge/Oracle-F80000?style=for-the-badge&logo=oracle&logoColor=white" /></span>
    <span class="tech-badge"><img src="https://img.shields.io/badge/GoogleCloud-%234285F4.svg?style=for-the-badge&logo=google-cloud&logoColor=white" /></span>
    <span class="tech-badge"><img src="https://img.shields.io/badge/netlify-%23000000.svg?style=for-the-badge&logo=netlify&logoColor=#00C7B7" /></span>
    <span class="tech-badge"><img src="https://img.shields.io/badge/bootstrap-%238511FA.svg?style=for-the-badge&logo=bootstrap&logoColor=white" /></span>
    <span class="tech-badge"><img src="https://img.shields.io/badge/esbuild-%23FFCF00.svg?style=for-the-badge&logo=esbuild&logoColor=black" /></span>
    <span class="tech-badge"><img src="https://img.shields.io/badge/Flutter-%2302569B.svg?style=for-the-badge&logo=Flutter&logoColor=white" /></span>
    <span class="tech-badge"><img src="https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white" /></span>
    <span class="tech-badge"><img src="https://img.shields.io/badge/Qt-%23217346.svg?style=for-the-badge&logo=Qt&logoColor=white" /></span>
    <span class="tech-badge"><img src="https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB" /></span>
    <span class="tech-badge"><img src="https://img.shields.io/badge/apache-%23D42029.svg?style=for-the-badge&logo=apache&logoColor=white" /></span>
    <span class="tech-badge"><img src="https://img.shields.io/badge/apache%20tomcat-%23F8DC75.svg?style=for-the-badge&logo=apache-tomcat&logoColor=black" /></span>
    <span class="tech-badge"><img src="https://img.shields.io/badge/mysql-4479A1.svg?style=for-the-badge&logo=mysql&logoColor=white" /></span>
    <span class="tech-badge"><img src="https://img.shields.io/badge/Microsoft%20SQL%20Server-CC2927?style=for-the-badge&logo=microsoft%20sql%20server&logoColor=white" /></span>
    <span class="tech-badge"><img src="https://img.shields.io/badge/adobe-%23FF0000.svg?style=for-the-badge&logo=adobe&logoColor=white" /></span>
    <span class="tech-badge"><img src="https://img.shields.io/badge/adobe%20photoshop-%2331A8FF.svg?style=for-the-badge&logo=adobe%20photoshop&logoColor=white" /></span>
    <span class="tech-badge"><img src="https://img.shields.io/badge/Canva-%2300C4CC.svg?style=for-the-badge&logo=Canva&logoColor=white" /></span>
    <span class="tech-badge"><img src="https://img.shields.io/badge/SketchUp-005F9E?style=for-the-badge&logo=sketchup&logoColor=white" /></span>
    <span class="tech-badge"><img src="https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white" /></span>
    <span class="tech-badge"><img src="https://img.shields.io/badge/-TestingLibrary-%23E33332?style=for-the-badge&logo=testing-library&logoColor=white" /></span>
    <span class="tech-badge"><img src="https://img.shields.io/badge/-Arduino-00979D?style=for-the-badge&logo=Arduino&logoColor=white" /></span>
    <span class="tech-badge"><img src="https://img.shields.io/badge/cisco-%23049fd9.svg?style=for-the-badge&logo=cisco&logoColor=black" /></span>
    <span class="tech-badge"><img src="https://img.shields.io/badge/codecov-%23ff0077.svg?style=for-the-badge&logo=codecov&logoColor=white" /></span>
    <span class="tech-badge"><img src="https://img.shields.io/badge/confluence-%23172BF4.svg?style=for-the-badge&logo=confluence&logoColor=white" /></span>
    <span class="tech-badge"><img src="https://img.shields.io/badge/home%20assistant-%2341BDF5.svg?style=for-the-badge&logo=home-assistant&logoColor=white" /></span>
    <span class="tech-badge"><img src="https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white" /></span>
    <span class="tech-badge"><img src="https://img.shields.io/badge/Notion-%23000000.svg?style=for-the-badge&logo=notion&logoColor=white" /></span>
    <span class="tech-badge"><img src="https://img.shields.io/badge/packer-%23E7EEF0.svg?style=for-the-badge&logo=packer&logoColor=%2302A8EF" /></span>
    <span class="tech-badge"><img src="https://img.shields.io/badge/Portfolio-%23000000.svg?style=for-the-badge&logo=firefox&logoColor=#FF7139" /></span>
    <span class="tech-badge"><img src="https://img.shields.io/badge/tor-%237E4798.svg?style=for-the-badge&logo=tor-project&logoColor=white" /></span>
    <span class="tech-badge"><img src="https://img.shields.io/badge/GODOT-%23FFFFFF.svg?style=for-the-badge&logo=godot-engine" /></span>
    <span class="tech-badge"><img src="https://img.shields.io/badge/steam-%23000000.svg?style=for-the-badge&logo=steam&logoColor=white" /></span>
  </div>
</div>

###

<div align="left" class="section-container">
  <h2 class="section-title">💰 Apoya mi trabajo</h2>
</div>

###

<div align="center" class="section-container">
  <div style="padding: 20px;">
    <a href="https://www.paypal.me/deivydvidal" target="_blank" class="donate-button">
      <img src="https://img.shields.io/badge/PayPal-00457C?style=for-the-badge&logo=paypal&logoColor=white" />
    </a>
  </div>
</div>

###

<div align="center" class="section-container">
  <img class="pollo-gif" height="130" src="https://i.postimg.cc/t4pGYBc9/Pollo-Animado.gif" />
  <p style="color: #718096; font-size: 14px; margin-top: 10px;">🐔 ¡Gracias por visitar mi perfil!</p>
</div>

###

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&height=150&section=footer&reversal=false&fontSize=70&fontColor=FFFFFF&fontAlign=50&fontAlignY=50&stroke=-&descSize=20&descAlign=50&descAlignY=50&theme=cobalt" width="100%" />
</div>

<br>

<div align="center">
  <img src="https://komarev.com/ghpvc/?username=PolloCraft&label=Visitas%20al%20perfil&color=667eea&style=flat-square" alt="Visitor Counter" />
</div>
