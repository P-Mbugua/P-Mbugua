<div align="center">
  <img src="https://p-mbugua.github.io/Official-_Portfolio/peter.png" alt="Profile Picture" width="200" height="200" style="border-radius: 50%; box-shadow: 0 4px 12px rgba(0, 0, 0, 0.2);" />
  <h1 style="font-size: 2.5em; margin-top: 10px;">Hi there, I'm <strong>Peter Mbugua</strong>! 👋</h1>
</div>

<hr style="border: 1px solid #cccccc; margin-top: 20px;"/>

<div align="center">
  <h2>📅 My Coding Activity</h2>
  <p id="codingTime">Loading coding times...</p>
</div>

<script>
  async function getCodingTime() {
    const username = 'P-Mbugua';
    const url = `https://github-readme-stats.vercel.app/api/traffic/${P-Mbugua}`;
    
    try {
      const response = await fetch(url);
      if (!response.ok) throw new Error('Network response was not ok');
      
      const data = await response.json();
      const currentHour = new Date().getHours();
      let timePeriod = "";

      // Example productive time data, replace with actual response logic
      let codingHours = [
        { time: "3am - 9am", count: data.times["3-9"] || 0 },
        { time: "9am - 6pm", count: data.times["9-18"] || 0 },
        { time: "6pm - 9:30pm", count: data.times["18-21"] || 0 },
        { time: "9:30pm - 2am", count: data.times["21-3"] || 0 },
      ];

      // Determine current coding period
      if (currentHour >= 3 && currentHour < 9) {
        timePeriod = "🕰️ Morning (3am - 9am)";
      } else if (currentHour >= 9 && currentHour < 18) {
        timePeriod = "🌞 Day Time (9am - 6pm)";
      } else if (currentHour >= 18 && currentHour < 21.5) {
        timePeriod = "🌆 Evening (7pm - 9:30pm)";
      } else {
        timePeriod = "🌙 Late Night (10pm - 2am)";
      }

      document.getElementById("codingTime").innerText = `Currently Coding: ${timePeriod}`;
      // You can also display coding hours if necessary
    } catch (error) {
      console.error('Error fetching GitHub data:', error);
      document.getElementById("codingTime").innerText = 'Error loading data.';
    }
  }

  getCodingTime();
  setInterval(getCodingTime, 60000); 
</script>

<hr style="border: 1px solid #cccccc; margin-top: 20px;"/>

# 🚀 About Me
I am a **Junior Fullstack Developer** passionate about creating responsive, scalable web applications...




# 🚀 About Me
I am a **Junior Fullstack Developer** passionate about creating responsive, scalable web applications. I enjoy solving real-world problems through technology and continuously learning to enhance | sharpen my skills set.

- 🌍 **Location**: Kenya
- 💼 **Current Work**: MarpsAfrica | Save A Soul Organization
- 🕰️ **Work Hours**: Mostly at night (Kenyan time).
- 🌱 **Learning**: Cloud computing & DevOps.
- 🗣️ **Languages**: Fluent in English | Swahili.

### ✨ Personal Statement
"Code is like humor. When you have to explain it, it’s bad." – Cory House

<div align="center">
  <a href="https://developerp.netlify.app/" target="_blank">
    <img src="https://img.shields.io/badge/-Portfolio-%230084FF?style=for-the-badge&logo=google-chrome&logoColor=white" alt="Portfolio Badge">
  </a>
  <a href="https://www.linkedin.com/in/your-linkedin-profile/" target="_blank">
    <img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn Badge">
  </a>
  <a href="mailto:pmbugua276@gmail.com">
    <img src="https://img.shields.io/badge/-Email-%23D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email Badge">
  </a>
  <a href="https://flowcv.com/resume/f62ua50tfk" target="_blank">
    <img src="https://img.shields.io/badge/-Download%20CV-brightgreen?style=for-the-badge&logo=google-drive&logoColor=white" alt="CV Badge">
  </a>
</div>

<hr style="border: 1px solid #cccccc; margin-top: 20px;"/>

# 🔧 Skills & Technologies

## Frontend
- **Languages**: HTML, CSS, JavaScript, TypeScript
- **Frameworks/Libraries**: React.js, Tailwind CSS, Bootstrap
- **Tools**: Figma, VS Code, Chrome DevTools

## Backend
- **Languages**: Python
- **Databases**: MySQLite3
- **API**: RESTful, GraphQL
- **Authentication**: JWT, OAuth

## DevOps & Tools
- **Version Control**: Git, GitHub, Gitlab
- **Deployment**: Heroku, Netlify, Vercel 
- **Containerization**: Docker, Kubernetes (learning)
- **CI/CD**: GitHub Actions, CircleCI
- **Testing**: Jest, Mocha

<hr style="border: 1px solid #cccccc; margin-top: 20px;"/>

# 🧠 Currently Learning
- **Cloud Platforms**: AWS, Azure
- **Serverless Functions**: AWS Lambda, Azure Functions
- **Infrastructure as Code**: Terraform

<hr style="border: 1px solid #cccccc; margin-top: 20px;"/>

# 📈 GitHub Stats

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=P-Mbugua&show_icons=true&theme=radical&count_private=true" alt="GitHub Stats" width="450px">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=P-Mbugua&layout=compact&theme=radical" alt="Top Languages" width="350px">
  
 
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=P-Mbugua&theme=radical" alt="GitHub Streak Stats" width="450px">


  <img src="https://github-profile-summary-cards.vercel.app/api/cards/productive-time?username=P-Mbugua&theme=radical" alt="Most Active Hours" width="350px">
</div>

<hr style="border: 1px solid #cccccc; margin-top: 20px;"/>

# 🌟 Featured Projects

## 🚚 [Delivery Management](https://parcelpoa.netlify.app)
   - **Description**: A fullstack web app for managing orders | deliveries.
   - **Tech Stack**: React.js, Python, Flask, SQLite3, Tailwind CSS, JWT.
   - **Features**: Authentication, CRUD, real-time updates.

## 🖥️ [Personal Portfolio](https://mbuguapeter.netlify.app)
   - **Description**: A responsive portfolio website showcasing my work.
   - **Tech Stack**: React.js, Tailwind CSS, Typescript, Firebase, Python, EmailJs.
   - **Features**: Modern design, fully responsive.

## 🏨 [Hotel Management API](https://hetelogix.netlify.app)
   - **Description**: RESTful API for Hotel management.
   - **Tech Stack**: Flask, SQLite3, Tailwind CSS, Python, React.js.
   - **Features**: JWT authentication, role-based access.

<hr style="border: 1px solid #cccccc; margin-top: 20px;"/>

# 🎯 Interests & Hobbies
- **Tech Enthusiast**: I explore web development trends, cloud technologies, and DevOps.
- **Coding Challenges**: Active on LeetCode and Codewars.
- **Open Source**: Contribute to open-source projects.
- **Gaming**: Enjoy strategy and RPG games.
- **Music**: Jazz and instrumental music for focus.

<hr style="border: 1px solid #cccccc; margin-top: 20px;"/>

# 📜 Certifications
- **JavaScript Algorithms & Data Structures** – freeCodeCamp
- **Responsive Web Design** – freeCodeCamp
- **Cloud Practitioner Essentials** – AWS

<hr style="border: 1px solid #cccccc; margin-top: 20px;"/>



### 🌱 Future Goals
I aim to deepen my knowledge of cloud technologies and DevOps practices, with a goal to contribute to open-source projects and collaborate with like-minded developers.

### 🤝 Community Involvement
- Volunteer at local coding bootcamps to mentor aspiring developers.


### 🎉 Achievements
- **Winner** of the 2023 Local Code Jam.
- **Top 5%** on LeetCode for problem-solving challenges.

### 🎤 Testimonials
> "Peter's dedication to solving problems and his ability to learn quickly make him a valuable asset to any team." – Ian Okumu

### 🤔 Fun Facts
- I once built a weather app that uses data from a rocket launch! 
- My favorite programming language is JavaScript, but I'm keen to learn Go!

# 💬 Let's Connect!
<p align="center">
  <a href="mailto:petermbuguangumi@gmail.com">
    <img src="https://img.shields.io/badge/-Gmail-D14836?style=flat-square&logo=Gmail&logoColor=white" alt="Gmail">
  </a>
  <a href="https://www.linkedin.com/in/peter-mbugua-a6351a262/">
    <img src="https://img.shields.io/badge/-LinkedIn-blue?style=flat-square&logo=Linkedin&logoColor=white" alt="LinkedIn">
  </a>
  <a href="https://mbuguapeter.netlify.app/">
    <img src="https://img.shields.io/badge/-Portfolio-green?style=flat-square&logo=google-chrome&logoColor=white" alt="Portfolio">
  </a>
</p>

<!-- Dones -->

---

*Thank you for visiting my GitHub profile! 😊*
