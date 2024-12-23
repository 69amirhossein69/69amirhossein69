<!DOCTYPE html>
<html>
<head>
  <style>
    body {
      font-family: 'Inter', sans-serif;
      background: linear-gradient(to right, #0f2027, #203a43, #2c5364);
      color: #fff;
    }
    
    .tech-container {
      max-width: 1200px;
      margin: 0 auto;
      padding: 20px;
    }

    .skills-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(120px, 1fr));
      gap: 20px;
      margin: 20px 0;
    }

    .skill-card {
      background: rgba(255, 255, 255, 0.1);
      border-radius: 16px;
      padding: 20px;
      text-align: center;
      transition: all 0.3s ease;
      border: 1px solid rgba(255, 255, 255, 0.1);
      backdrop-filter: blur(10px);
    }

    .skill-card:hover {
      transform: translateY(-5px);
      box-shadow: 0 8px 20px rgba(0,0,0,0.2);
      border-color: #00FFFF;
    }

    .skill-icon {
      width: 65px;
      height: 65px;
      margin-bottom: 10px;
    }

    .status-container {
      background: rgba(255, 255, 255, 0.05);
      border-radius: 20px;
      padding: 30px;
      margin: 40px 0;
      position: relative;
      overflow: hidden;
    }

    .status-code {
      font-family: 'Fira Code', monospace;
      position: relative;
      z-index: 2;
    }

    .status-container::before {
      content: '';
      position: absolute;
      top: 0;
      left: 0;
      right: 0;
      bottom: 0;
      background: linear-gradient(45deg, #00FFFF20, #FF69B420);
      animation: gradient 15s ease infinite;
      z-index: 1;
    }

    .contact-section {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
      gap: 30px;
      padding: 40px 0;
    }

    .contact-card {
      background: rgba(255, 255, 255, 0.05);
      border-radius: 20px;
      padding: 30px;
      text-align: center;
      transition: all 0.3s ease;
      position: relative;
      overflow: hidden;
    }

    .contact-card::after {
      content: '';
      position: absolute;
      height: 2px;
      width: 50px;
      background: #00FFFF;
      bottom: 0;
      left: 50%;
      transform: translateX(-50%);
      transition: width 0.3s ease;
    }

    .contact-card:hover::after {
      width: 100px;
    }

    .contact-icon {
      font-size: 2.5rem;
      margin-bottom: 15px;
      color: #00FFFF;
    }

    @keyframes gradient {
      0% { background-position: 0% 50%; }
      50% { background-position: 100% 50%; }
      100% { background-position: 0% 50%; }
    }

    .section-title {
      text-align: center;
      font-size: 2.5rem;
      margin: 40px 0;
      color: #00FFFF;
      text-shadow: 0 0 10px rgba(0, 255, 255, 0.5);
    }
  </style>
</head>
<body>
  <div class="tech-container">
    <h2 class="section-title">Tech Arsenal</h2>
    
    <div class="skills-grid">
      <!-- Core Technologies -->
      <div class="skill-card">
        <img src="https://techstack-generator.vercel.app/react-icon.svg" alt="React" class="skill-icon">
        <h3>React</h3>
        <p>Advanced</p>
      </div>
      <div class="skill-card">
        <img src="https://techstack-generator.vercel.app/js-icon.svg" alt="JavaScript" class="skill-icon">
        <h3>JavaScript</h3>
        <p>Expert</p>
      </div>
      <div class="skill-card">
        <img src="https://techstack-generator.vercel.app/ts-icon.svg" alt="TypeScript" class="skill-icon">
        <h3>TypeScript</h3>
        <p>Intermediate</p>
      </div>
      <div class="skill-card">
        <img src="https://raw.githubusercontent.com/tandpfun/skill-icons/main/icons/TailwindCSS-Dark.svg" alt="Tailwind" class="skill-icon">
        <h3>Tailwind</h3>
        <p>Advanced</p>
      </div>
      <div class="skill-card">
        <img src="https://techstack-generator.vercel.app/sass-icon.svg" alt="Sass" class="skill-icon">
        <h3>Sass</h3>
        <p>Intermediate</p>
      </div>
      <div class="skill-card">
        <img src="https://techstack-generator.vercel.app/github-icon.svg" alt="GitHub" class="skill-icon">
        <h3>GitHub</h3>
        <p>Advanced</p>
      </div>
    </div>

    <div class="status-container">
      <pre class="status-code">
class AmirhosseinKhalajAsadi {
    readonly status = {
        currentRole: "Frontend Developer & AI Explorer 🚀",
        location: "Tehran, Iran 🌃",
        education: {
            masters: "AI @ Eyvanekey University 🤖",
            bachelors: "Software Engineering @ Damghan University 💻"
        },
        
        currentlyWorking: {
            frontend: ["React", "TypeScript", "TailwindCSS"],
            aiProjects: ["Machine Learning", "Neural Networks"],
            personal: "Building Dreams with Code ⚡"
        },

        interests: ["Web Development", "AI", "UI/UX Design"],
        lifeMode: "Debug && Design && Deploy 🎯",
        listening: "Lofi Beats 🎵"
    };

    readonly mission = "Crafting Digital Excellence 💫";
}
      </pre>
    </div>

    <h2 class="section-title">Let's Connect</h2>
    <div class="contact-section">
      <div class="contact-card">
        <div class="contact-icon">📧</div>
        <h3>Email</h3>
        <p>a.h.khalajasadi@gmail.com</p>
      </div>
      <div class="contact-card">
        <div class="contact-icon">📱</div>
        <h3>Phone</h3>
        <p>+98 910 033 8699</p>
      </div>
      <div class="contact-card">
        <div class="contact-icon">📍</div>
        <h3>Location</h3>
        <p>Tehran, Iran</p>
      </div>
      <div class="contact-card">
        <div class="contact-icon">💼</div>
        <h3>Portfolio</h3>
        <p>github.com/69amirhossein69</p>
      </div>
    </div>
  </div>
</body>
</html>
