<div align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=600&size=32&duration=4000&pause=1000&color=00C4B4&center=true&vCenter=true&width=600&lines=Hi+There!+I'm+Afif+Showfeer+%F0%9F%91%8B;Full-Stack+Web+Developer+%7C+B.Tech+CSE;Building+with+MERN+%F0%9F%9A%80" alt="Typing SVG" />
</div>

<div align="center">
  <a href="https://portfolio-afifshowfeers-projects.vercel.app/"><img src="https://img.shields.io/badge/Portfolio-00C4B4?style=for-the-badge&logo=vercel&logoColor=white" alt="Portfolio" /></a>
  <a href="https://github.com/afifshowfeer"><img src="https://img.shields.io/github/followers/afifshowfeer?label=Followers&style=for-the-badge&logo=github&color=181717" alt="GitHub followers" /></a>
  <img src="https://komarev.com/ghpvc/?username=afifshowfeer&style=for-the-badge&color=00C4B4&label=Profile+Views" alt="Profile views" />
</div>

<br/>

<div align="center">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black" alt="React" />
  <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white" alt="Node.js" />
  <img src="https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white" alt="Express" />
  <img src="https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white" alt="MongoDB" />
  <br/>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white" alt="Django" />
  <img src="https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white" alt="C++" />
  <img src="https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=white" alt="AWS" />
  <img src="https://img.shields.io/badge/Java-007396?style=for-the-badge&logo=openjdk&logoColor=white" alt="Java" />
  <img src="https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white" alt="Flutter" />
  <img src="https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white" alt="Tailwind CSS" />
</div>

<br/>

### 👨‍💻 About Me

- 🎓 **B.Tech Computer Science** student at **Mar Baselios College of Engineering and Technology**
- 🤝 Backend Developer Intern at **[µLearn](https://mulearn.org/)**, working on its Django backend
- 🌐 Building full-stack apps with the **MERN stack** — JWT auth, role-based access, REST APIs, deployed on Vercel + Render + MongoDB Atlas
- 🧩 Sharpening problem-solving on **LeetCode** and **NeetCode**
- 💻 Also worked with **Java (Swing)**, **C**, **Python**, **SQL**, and **Flutter**
- 🔐 Interested in **ethical hacking**, **algorithms**, and solving real-world problems
- 🎯 Goal: Turn ideas into real products — one commit at a time!

<br/>

### 🌟 Featured Contributions

#### 🎓 [µLearn Backend](https://github.com/gtech-mulearn/mulearnbackend) — Backend Developer Intern
Backend for [mulearn.org](https://mulearn.org/), a peer-learning community platform · `Python` `Django REST Framework`
- 🔔 Built the in-app **notification system**
- 🧑‍💼 Worked on the **intern module** — timesheets and monthly reviews
- 🧩 Added solution submissions for **problem statements**
- 📅 Improved **events** — search and sorting
- 🛠️ Various API features and bug fixes

#### 🚁 [Autonomous Traffic Violation Detection & Urban Planning System](https://github.com/afifshowfeer/main-project) — final-year team project
UAV aerial footage + digital twin for traffic violation detection · `Python` `YOLO` `BoT-SORT` `CARLA` `FastAPI` `React`
- 🎯 **BoT-SORT tracking pipeline** with tracklet stitching, plus YOLO / YOLO-OBB fine-tuning and dataset prep ([PR #1](https://github.com/DevWithPranav/main-project/pull/1))
- 🏷️ CARLA auto-labelling/export, a retraining pipeline with metrics logging, and an old-vs-retrained detector comparison
- 📡 **Live streaming system:** evidence clips, live zone reload, a watchdog, and a two-machine Ethernet link
- 🚦 Scripted speeding, stopping and pedestrian-crossing violations, plus a dashboard with date/time filters

#### 🚗 [Smart Parking System (AWS IoT)](https://github.com/ADU773/Smart-Parking-System) · [Live](https://smart-parking-system.vercel.app)
Real-time parking slot availability · `ESP32` `AWS IoT Core` `MQTT` `Lambda`
- 📟 Wrote the **ESP32 firmware**: ultrasonic sensors watch 4 slots and publish only when a slot's status changes, which keeps MQTT traffic and AWS costs low
- ☁️ **AWS pipeline:**
  - **AWS IoT Core** — the ESP32 connects securely (MQTT over TLS, X.509 certificate) and sends updates like `{"slotid":"B2","occupied":true}` to the `parking/slots` topic
  - **IoT Rule → AWS Lambda** — every message triggers a Lambda function
  - **Lambda → Database** — Lambda saves each slot's latest status and timestamp
  - **Web dashboard** — reads the database and shows a live map of the lot, updated within 2–3 seconds
- 📝 Added demo media and detailed pipeline documentation

```text
Sensors ─► ESP32 ─(MQTT/TLS)─► AWS IoT Core ─(Rule)─► Lambda ─► Database ─► Web Dashboard
```

#### 💡 [Catalyst Web](https://github.com/thecatalystiedcmbcet/Catalyst-Web) · [Live](https://catalyst-web-dev.vercel.app)
Official website of Catalyst, the Innovation and Entrepreneurship Development Centre (IEDC) at MBCET · `Next.js` `TypeScript` `Supabase` `Tailwind CSS`
- 🛡️ Built the **admin panel** — manage members, roles, achievements, events and logs
- 🏆 Built the **achievements page**
- ✅ Added form validation across the admin forms
- 🐛 Fixed build and deployment issues, and cleaned up the codebase

#### 🎮 [TruckSim Realistic Engine Rumble](https://github.com/afifshowfeer/rpm-haptics-ets2-ats) — personal project
Controller rumble that follows engine RPM in Euro Truck Simulator 2 & American Truck Simulator · `C++` `Python` `XInput`
- ⚙️ V2 is rewritten as a **native C++ SCS telemetry plugin** (`.dll`) for lower latency and smooth 60 FPS updates
- 🛻 Diesel idle chug and rev-scaled vibration that stops automatically when the engine is off, the game is paused or you exit

<br/>

### 🛠️ Tech Stack

```text
Frontend ────────►  React • Next.js • Tailwind CSS • Material-UI • shadcn/ui • Vite
Backend  ────────►  Node.js • Express.js • Django REST Framework • FastAPI • JWT
ML / CV  ────────►  YOLO • BoT-SORT • CARLA Simulator
IoT      ────────►  ESP32 • AWS IoT Core • MQTT • AWS Lambda
Database ────────►  MongoDB (Mongoose, Atlas) • Supabase • SQL
Mobile   ────────►  Flutter
Languages────────►  JavaScript • TypeScript • Python • C++ • Java • C • SQL
Tools    ────────►  Git • VS Code • Postman • Vercel • Render
```

<br/>

### 📊 GitHub Stats

<div align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=afifshowfeer&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" alt="GitHub stats" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=afifshowfeer&layout=compact&theme=tokyonight&hide_border=true&langs_count=8" alt="Top languages" />
</div>

<div align="center">
  <img src="https://streak-stats.demolab.com?user=afifshowfeer&theme=tokyonight&hide_border=true" alt="GitHub streak" />
</div>

<br/>

### 🤝 Connect With Me

<div align="center">
  <a href="https://portfolio-afifshowfeers-projects.vercel.app/"><img src="https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white" alt="Portfolio" /></a>
  <a href="https://github.com/afifshowfeer"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" /></a>
</div>

<div align="center">
  <sub>⭐ Thanks for stopping by!</sub>
</div>
