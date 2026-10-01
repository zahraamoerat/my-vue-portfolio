<template>
  <div class="portfolio-case">
    <header>
      <a href="#" class="logo">ZM.</a>
      <nav class="navbar">
        <a href="#hero-section">Profile</a>
        <a href="#about-section">About Me</a>
        <a href="#projects-section">Projects</a>
        <a href="#contact-section">Contact</a>
      </nav>
    </header>

    <section class="hero-section" id="hero-section">
      <h1>Hi, my name is Zahraa Moerat</h1>
      <p>
        I’m a beginner web developer passionate about creating clean,
        user-friendly websites. I started coding about 6 months ago and have
        learnt how to work with both frontend and backend development.
      </p>
      <img
        src="@/assets/portfolio-profile-picture.png"
        alt="Zahraa Moerat"
        class="img1"
      />
    </section>

    <section class="about-section" id="about-section">
      <h2>About Me</h2>
      <div class="flex-box">
        <div>
          <h4>📚 My learning experience</h4>
          <p>
            I am currently a trainee at Life Choices Academy. So far I have
            learnt the basics of Python and worked with HTML, CSS, JavaScript,
            Vue.js, Node.js and MySQL workbench. I also understand the
            fundamentals of GitHub and hosting websites.
          </p>
        </div>
        <div>
          <h4>⚡ My strengths</h4>
          <p>
            My current strength lies in creating databases and connecting the
            backend of a website to its frontend. I am working on upskilling
            myself in the other languages that I have learnt so far. I’m also
            someone who is able to work under pressure.
          </p>
        </div>
        <div>
          <h4>🎯 My Goals</h4>
          <p>- Land my first tech internship.</p>
          <p>- Build projects that help people.</p>
          <p>- Create my own app.</p>
        </div>
        <div>
          <h4>🎯 My Interests</h4>
          <p>- Frontend Development.</p>
          <p>- UI/UX Design.</p>
          <p>- Art.</p>
        </div>
      </div>

      <div class="skills-container">
        <h2 class="skills-heading">My Skills</h2>
        <div class="skills-description">
          <p>
            The skills I'm developing are applied in the projects featured
            below—each one represents a step forward in my technical journey.
          </p>
        </div>
        <div class="skills-item">
          <div class="skills-info">
            <div class="skill-name-wrapper">
              <span class="skill-name">Python</span>
              <span class="skill-percentage">65%</span>
            </div>
            <div class="progress-bar">
              <div class="progress-fill" style="width: 65%"></div>
            </div>
          </div>
          <div class="skills-info">
            <div class="skill-name-wrapper">
              <span class="skill-name">HTML</span>
              <span class="skill-percentage">78%</span>
            </div>
            <div class="progress-bar">
              <div class="progress-fill" style="width: 78%"></div>
            </div>
          </div>
          <div class="skills-info">
            <div class="skill-name-wrapper">
              <span class="skill-name">CSS</span>
              <span class="skill-percentage">60%</span>
            </div>
            <div class="progress-bar">
              <div class="progress-fill" style="width: 60%"></div>
            </div>
          </div>
          <div class="skills-info">
            <div class="skill-name-wrapper">
              <span class="skill-name">JavaScript</span>
              <span class="skill-percentage">40%</span>
            </div>
            <div class="progress-bar">
              <div class="progress-fill" style="width: 40%"></div>
            </div>
          </div>
          <div class="skills-info">
            <div class="skill-name-wrapper">
              <span class="skill-name">Node.js</span>
              <span class="skill-percentage">50%</span>
            </div>
            <div class="progress-bar">
              <div class="progress-fill" style="width: 50%"></div>
            </div>
          </div>
          <div class="skills-info">
            <div class="skill-name-wrapper">
              <span class="skill-name">Vue.js</span>
              <span class="skill-percentage">65%</span>
            </div>
            <div class="progress-bar">
              <div class="progress-fill" style="width: 65%"></div>
            </div>
          </div>
          <div class="skills-info">
            <div class="skill-name-wrapper">
              <span class="skill-name">MySQL Workbench</span>
              <span class="skill-percentage">75%</span>
            </div>
            <div class="progress-bar">
              <div class="progress-fill" style="width: 75%"></div>
            </div>
          </div>
          <div class="skills-info">
            <div class="skill-name-wrapper">
              <span class="skill-name">GitHub</span>
              <span class="skill-percentage">74%</span>
            </div>
            <div class="progress-bar">
              <div class="progress-fill" style="width: 74%"></div>
            </div>
          </div>
        </div>
      </div>
    </section>

    <section class="projects-section" id="projects-section">
      <h2>My Projects</h2>
      <p>
        The following projects include both the projects that I have done at
        Life Choices Academy, as well as my own personal projects.
      </p>
      <div class="project-preview">
        <div class="project-card">
          <img src="@/assets/theblushingbrush.png" alt="The Blushing Brush" />
          <h4>Product Showcase Page</h4>
          <a
            href="https://github.com/zahraamoerat/exercise3-CSS.git"
            class="project-btn"
            target="_blank"
            rel="noreferrer"
            >GitHub</a
          >
          <a
            href="https://the-blushing-brush.netlify.app/"
            target="_blank"
            rel="noreferrer"
            class="project-btn"
            >View Project</a
          >
        </div>
        <div class="project-card">
          <img src="@/assets/gallery.png" alt="Responsive Gallery" />
          <h4>Responsive Gallery</h4>
          <a
            href="https://github.com/zahraamoerat/exercise2-CSS.git"
            class="project-btn"
            target="_blank"
            rel="noreferrer"
            >GitHub</a
          >
          <a
            href="https://my-gallery-of-images.netlify.app/"
            target="_blank"
            rel="noreferrer"
            class="project-btn"
            >View Project</a
          >
        </div>
        <div class="project-card">
          <img src="@/assets/driptheory.png" alt="Drip Theory" />
          <h4>Bootstrap Store CSS project</h4>
          <a
            href="https://github.com/zahraamoerat/exercise4-CSS.git"
            class="project-btn"
            target="_blank"
            rel="noreferrer"
            >GitHub</a
          >
          <a
            href="https://drip-theory.netlify.app/"
            target="_blank"
            rel="noreferrer"
            class="project-btn"
            >View Project</a
          >
        </div>
      </div>
    </section>

    <section class="contact-section" id="contact-section">
      <h2>Contact Me</h2>
      <div class="my-information">
        <h5><i class="fas fa-phone-alt"></i> My Number: 063 248 1595</h5>
        <h5>
          <i class="fas fa-envelope"></i> My Email: zahraamoerat70@gmail.com
        </h5>
      </div>

      <form
        action="https://formspree.io/f/mgobyygg"
        enctype="multipart/form-data"
        method="post"
      >
        <label for="name">Name:</label>
        <input
          type="text"
          id="name"
          name="name"
          placeholder="Jane Doe"
          required
        />

        <label for="email">Email:</label>
        <input
          type="email"
          id="email"
          name="email"
          placeholder="JDoe@gmail.com"
        />

        <label for="userMessage">Message:</label>
        <textarea
          class="form-control"
          id="userMessage"
          name="message"
          rows="5"
          cols="50"
          placeholder="Start message..."
          required
        ></textarea>

        <button type="submit">Send Message ✨</button>
      </form>
    </section>

    <footer>
      <div class="footer-content">
        <p>Author: Zahraa Moerat</p>
        <p>&copy; copyright reserved 2026</p>
        <a
          href="http://www.linkedin.com/in/zahraa-moerat-0b17a2218"
          target="_blank"
          rel="noreferrer"
          ><i class="fab fa-linkedin"></i> LinkedIn</a
        >
        <a
          href="https://github.com/zahraamoerat"
          target="_blank"
          rel="noreferrer"
          ><i class="fab fa-github"></i> GitHub</a
        >
      </div>
    </footer>
  </div>
</template>

<style scoped>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

:global(:root) {
  --deep-navy: #1a4a6f;
  --ocean-teal: #2c7a7b;
  --warm-sand: #d9ae6c;
  --sage-green: #5f8b6f;
  --bg-soft: #fefcf7;
  --pure-white: #ffffff;
  --text-dark: #1a2c3e;
  --text-muted: #2c4c6c;
  --border-light: #e2ecf3;
  --shadow-elegant: 0 20px 35px -12px rgba(26, 74, 111, 0.1);
  --shadow-light: 0 4px 12px rgba(26, 74, 111, 0.05);
  --radius-xl: 1.8rem;
  --radius-lg: 1.2rem;
}

:global(html) {
  scroll-behavior: smooth;
  scroll-padding-top: 100px;
}

:global(body) {
  margin: 0;
  min-height: 100vh;
  font-family:
    "Inter",
    system-ui,
    -apple-system,
    "Segoe UI",
    "Roboto",
    sans-serif;
  background: linear-gradient(145deg, #eef3fc 0%, #e0eaf5 100%);
  color: var(--text-dark);
  line-height: 1.6;
}

/* main portfolio case */
.portfolio-case {
  max-width: 1300px;
  margin: 2rem auto;
  background: var(--bg-soft);
  border-radius: 2.5rem;
  box-shadow: var(--shadow-elegant);
  overflow: hidden;
}

/* header */
header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 1.2rem 2.8rem;
  background: rgba(255, 255, 245, 0.96);
  backdrop-filter: blur(4px);
  border-bottom: 1px solid rgba(26, 74, 111, 0.15);
  flex-wrap: wrap;
  gap: 1rem;
}

.logo {
  font-size: 2rem;
  font-weight: 800;
  text-decoration: none;
  background: linear-gradient(135deg, var(--deep-navy), var(--ocean-teal));
  background-clip: text;
  -webkit-background-clip: text;
  color: transparent;
  letter-spacing: -0.5px;
}

.navbar {
  display: flex;
  gap: 2rem;
  flex-wrap: wrap;
}

.navbar a {
  text-decoration: none;
  font-weight: 600;
  color: var(--text-muted);
  transition: 0.2s;
  font-size: 1rem;
  padding: 0.3rem 0;
  border-bottom: 2px solid transparent;
}

.navbar a:hover {
  color: var(--ocean-teal);
  border-bottom-color: var(--warm-sand);
}

/* sections general */
section {
  padding: 3rem 2.8rem;
}

/* hero */
.hero-section {
  background: linear-gradient(135deg, #fbfef9 0%, #f2f7fc 100%);
  display: flex;
  flex-direction: column;
  align-items: center;
  text-align: center;
  border-bottom: 1px solid var(--border-light);
}

.hero-section h1 {
  font-size: 2.8rem;
  font-weight: 800;
  color: var(--deep-navy);
  margin-bottom: 1rem;
  letter-spacing: -0.02em;
}

.hero-section p {
  max-width: 760px;
  color: var(--text-muted);
  font-size: 1.05rem;
  margin-bottom: 2rem;
}

.img1 {
  width: 150px;
  height: 150px;
  object-fit: cover;
  border-radius: 50%;
  border: 4px solid var(--warm-sand);
  box-shadow: var(--shadow-light);
  background: #e2e8f0;
  transition: transform 0.3s ease;
}

.img1:hover {
  transform: scale(1.05);
  border-color: var(--ocean-teal);
}

/* about section */
.about-section {
  background: var(--pure-white);
}

.about-section h2 {
  font-size: 2rem;
  color: var(--deep-navy);
  margin-bottom: 1.8rem;
  border-left: 6px solid var(--warm-sand);
  padding-left: 1rem;
}

.flex-box {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 1.8rem;
  margin-bottom: 3rem;
}

.flex-box h4 {
  font-size: 1.3rem;
  color: var(--sage-green);
  margin-bottom: 0.6rem;
  font-weight: 700;
}

.flex-box p {
  color: var(--text-muted);
}

.flex-box > div {
  background: #fefaf2;
  padding: 1.6rem;
  border-radius: var(--radius-lg);
  transition: all 0.25s ease;
  border: 1px solid var(--border-light);
  box-shadow: 0 2px 6px rgba(0, 0, 0, 0.02);
}

.flex-box > div:hover {
  transform: translateY(-4px);
  box-shadow: 0 12px 20px -10px rgba(26, 74, 111, 0.15);
  border-color: #cbdde9;
}

/* skills container */
.skills-container {
  background: #f6faf8;
  border-radius: var(--radius-xl);
  padding: 2rem;
  margin-top: 1rem;
}

.skills-heading {
  font-size: 1.9rem;
  color: var(--deep-navy);
  margin-bottom: 0.5rem;
}

.skills-description p {
  color: var(--text-muted);
  margin-bottom: 1.8rem;
}

.skills-item {
  display: flex;
  flex-direction: column;
  gap: 1.4rem;
}

.skills-info {
  background: var(--pure-white);
  padding: 1rem 1.4rem;
  border-radius: 1.2rem;
  border: 1px solid #e0ede8;
}

.skill-name-wrapper {
  display: flex;
  align-items: center;
  gap: 0.8rem;
  margin-bottom: 0.6rem;
  justify-content: space-between;
}

.skill-name {
  font-weight: 700;
  color: var(--deep-navy);
  font-size: 1rem;
}

.skill-percentage {
  font-size: 0.8rem;
  font-weight: 700;
  color: var(--sage-green);
  background: #e3f0ea;
  padding: 0.2rem 0.7rem;
  border-radius: 40px;
}

.progress-bar {
  background: #e2ecf0;
  border-radius: 40px;
  height: 8px;
  width: 100%;
  overflow: hidden;
}

.progress-fill {
  background: linear-gradient(90deg, var(--deep-navy), var(--ocean-teal));
  border-radius: 40px;
  height: 100%;
  transition: width 1s ease;
}

/* projects section */
.projects-section {
  background: var(--pure-white);
  border-top: 1px solid var(--border-light);
}

.projects-section h2 {
  font-size: 2rem;
  color: var(--deep-navy);
  margin-bottom: 1rem;
}

.projects-section p {
  color: var(--text-muted);
  margin-bottom: 1.5rem;
}

.project-preview {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
  gap: 1.8rem;
  margin-top: 1.5rem;
}

.project-card {
  background: #f8faf6;
  border-radius: var(--radius-lg);
  padding: 1.5rem;
  border: 1px solid #e2ebe3;
  transition: all 0.25s ease;
  display: flex;
  flex-direction: column;
}

.project-card:hover {
  transform: translateY(-6px);
  background: var(--pure-white);
  box-shadow: 0 12px 22px -10px rgba(26, 74, 111, 0.15);
  border-color: #cbdbe0;
}

.project-card img {
  width: 100%;
  height: 160px;
  object-fit: cover;
  border-radius: 0.8rem;
  margin-bottom: 1rem;
  border: 1px solid var(--border-light);
}

.project-card h4 {
  margin: 0.5rem 0 1rem;
  color: var(--deep-navy);
  font-size: 1.2rem;
}

.project-btn {
  display: inline-block;
  background: var(--deep-navy);
  color: var(--pure-white);
  text-decoration: none;
  padding: 0.6rem 1.2rem;
  border-radius: 40px;
  margin: 0.3rem 0.5rem 0 0;
  font-weight: 600;
  font-size: 0.85rem;
  transition: 0.2s;
}

.project-btn:hover {
  background: var(--ocean-teal);
  transform: translateY(-2px);
}

/* contact section */
.contact-section {
  background: linear-gradient(135deg, #fefcf5 0%, #f5f8fc 100%);
  border-radius: 0 0 2rem 2rem;
}

.contact-section h2 {
  font-size: 2rem;
  color: var(--deep-navy);
  margin-bottom: 1rem;
}

.my-information {
  background: var(--pure-white);
  padding: 1.2rem 1.6rem;
  border-radius: var(--radius-lg);
  display: inline-block;
  margin-bottom: 1.8rem;
  border-left: 5px solid var(--warm-sand);
  box-shadow: var(--shadow-light);
}

.my-information h5 {
  font-size: 1rem;
  font-weight: 500;
  color: var(--deep-navy);
  margin: 0.5rem 0;
}

label {
  display: inline-block;
  font-weight: 600;
  margin: 1rem 0 0.4rem 0;
  color: var(--deep-navy);
}

input,
textarea {
  width: 560px;
  max-width: 560px;
  padding: 0.8rem 1rem;
  border-radius: 1rem;
  border: 1px solid #cfe0e8;
  background: var(--pure-white);
  font-family: inherit;
  font-size: 1rem;
  transition: 0.2s;
  vertical-align: baseline;
}

@media (max-width: 700px) {
  input,
  textarea {
    width: calc(100% - 5rem);
  }
}

input:focus,
textarea:focus {
  outline: none;
  border-color: var(--ocean-teal);
  box-shadow: 0 0 0 3px rgba(44, 122, 123, 0.2);
}

button {
  background: var(--deep-navy);
  color: var(--pure-white);
  border: none;
  padding: 0.8rem 1.8rem;
  border-radius: 40px;
  margin-top: 1.2rem;
  font-weight: 600;
  cursor: pointer;
  transition: 0.2s;
  font-size: 0.95rem;
}

button:hover {
  background: var(--ocean-teal);
  transform: translateY(-2px);
}

/* footer */
footer {
  background: #1e3a4d;
  color: #eef3fc;
  padding: 1.8rem 2rem;
  text-align: center;
}

.footer-content {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 2rem;
  align-items: center;
}

.footer-content p {
  margin: 0;
}

.footer-content a {
  color: var(--warm-sand);
  text-decoration: none;
  font-weight: 500;
  transition: 0.2s;
}

.footer-content a:hover {
  color: #f5d7a7;
  text-decoration: underline;
}

/* responsiveness */
@media (max-width: 850px) {
  .portfolio-case {
    margin: 1rem;
    border-radius: 1.5rem;
  }

  header {
    padding: 1rem 1.8rem;
    flex-direction: column;
    gap: 1rem;
  }

  section {
    padding: 2rem 1.8rem;
  }

  .hero-section h1 {
    font-size: 2.2rem;
  }

  .navbar {
    gap: 1.2rem;
    justify-content: center;
  }

  .flex-box {
    grid-template-columns: 1fr;
  }
}

@media (max-width: 550px) {
  section {
    padding: 1.8rem 1.2rem;
  }

  .skills-info {
    padding: 0.8rem;
  }

  .project-preview {
    grid-template-columns: 1fr;
  }

  .hero-section h1 {
    font-size: 1.9rem;
  }
}
</style>
