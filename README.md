[index.html](https://github.com/user-attachments/files/23105930/index.html)
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Musoni Junior | Student</title>
    <link rel="stylesheet" href="style.css">
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
</head>
<body>
    <!-- Navigation -->
    <nav class="navbar">
        <div class="nav-container">
            <div class="nav-logo">
                <a href="#home">Musoni Junior</a>
            </div>
            <div class="nav-menu" id="nav-menu">
                <a href="#home" class="nav-link">Home</a>
                <a href="#about" class="nav-link">About</a>
                <a href="#skills" class="nav-link">Skills</a>
                <a href="#projects" class="nav-link">Projects</a>
                <a href="#contact" class="nav-link">Contact</a>
            </div>
            <div class="hamburger" id="hamburger">
                <span class="bar"></span>
                <span class="bar"></span>
                <span class="bar"></span>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <section id="home" class="hero">
        <div class="hero-container">
            <div class="hero-content">
                <h1 class="hero-title">Hi, I'm <span class="highlight">Musoni Junior</span></h1>
                <h2 class="hero-subtitle">IT Student</h2>
                <p class="hero-description">Am 17, l study at King David Academy, and l create beautiful, functional websites with clean code and modern design principles.</p>
                <div class="hero-buttons">
                    <a href="#projects" class="btn btn-primary">View My Work</a>
                    <a href="#contact" class="btn btn-secondary">Contact Me</a>
                </div>
            </div>
            <div class="hero-image">
                <div class="image-placeholder">
                    <i class="fas fa-user"></i>
                </div>
            </div>
        </div>
    </section>

    <!-- About Section -->
    <section id="about" class="about">
        <div class="container">
            <h2 class="section-title">About Me</h2>
            <div class="about-content">
                <div class="about-text">
                    <p>I'm a passionate web developement student with 2 months of experience creating digital experiences. I specialize in building responsive websites and web applications with a focus on user experience and performance.</p>
                    <p>My journey in web development started during my computer science studies, and I've been constantly learning and adapting to new technologies ever since.</p>
                    <div class="about-stats">
                        <div class="stat">
                            <h3>5+</h3>
                            <p>Projects Completed</p>
                        </div>
                        <div class="stat">
                            <h3>2+</h3>
                            <p>months Experience</p>
                        </div>
                        <div class="stat">
                            <h3>10+</h3>
                            <p>Happy Clients</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Skills Section -->
    <section id="skills" class="skills">
        <div class="container">
            <h2 class="section-title">My Skills</h2>
            <div class="skills-container">
                <div class="skill-category">
                    <h3>Frontend</h3>
                    <div class="skill-list">
                        <div class="skill-item">
                            <span>HTML/CSS</span>
                            <div class="skill-bar">
                                <div class="skill-progress" data-width="95%"></div>
                            </div>
                        </div>
                        <div class="skill-item">
                            <span>JavaScript</span>
                            <div class="skill-bar">
                                <div class="skill-progress" data-width="90%"></div>
                            </div>
                        </div>
                        <div class="skill-item">
                            <span>React</span>
                            <div class="skill-bar">
                                <div class="skill-progress" data-width="85%"></div>
                            </div>
                        </div>
                        <div class="skill-item">
                            <span>Vue.js</span>
                            <div class="skill-bar">
                                <div class="skill-progress" data-width="75%"></div>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="skill-category">
                    <h3>Tools & Others</h3>
                    <div class="skill-list">
                        <div class="skill-item">
                            <span>Git</span>
                            <div class="skill-bar">
                                <div class="skill-progress" data-width="80%"></div>
                            </div>
                        </div>
                        <div class="skill-item">
                            <span>Figma</span>
                            <div class="skill-bar">
                                <div class="skill-progress" data-width="70%"></div>
                            </div>
                        </div>
                        <div class="skill-item">
                            <span>Webpack</span>
                            <div class="skill-bar">
                                <div class="skill-progress" data-width="65%"></div>
                            </div>
                        </div>
                        <div class="skill-item">
                            <span>Node.js</span>
                            <div class="skill-bar">
                                <div class="skill-progress" data-width="60%"></div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Projects Section -->
    <section id="projects" class="projects">
        <div class="container">
            <h2 class="section-title">My Projects</h2>
            <div class="projects-grid">
                <div class="project-card">
                    <div class="project-image">
                        <div class="image-placeholder">
                            <i class="fas fa-laptop-code"></i>
                        </div>
                    </div>
                    <div class="project-content">
                        <h3>E-Commerce Website</h3>
                        <p>A fully responsive e-commerce platform built with React and Node.js with payment integration.</p>
                        <div class="project-tech">
                            <span>React</span>
                            <span>Node.js</span>
                            <span>MongoDB</span>
                        </div>
                        <div class="project-links">
                            <a href="#"><i class="fas fa-external-link-alt"></i> Live Demo</a>
                            <a href="#"><i class="fab fa-github"></i> Code</a>
                        </div>
                    </div>
                </div>
                <div class="project-card">
                    <div class="project-image">
                        <div class="image-placeholder">
                            <i class="fas fa-mobile-alt"></i>
                        </div>
                    </div>
                    <div class="project-content">
                        <h3>Task Management App</h3>
                        <p>A productivity application for managing daily tasks with drag-and-drop functionality.</p>
                        <div class="project-tech">
                            <span>Vue.js</span>
                            <span>Firebase</span>
                            <span>SCSS</span>
                        </div>
                        <div class="project-links">
                            <a href="#"><i class="fas fa-external-link-alt"></i> Live Demo</a>
                            <a href="#"><i class="fab fa-github"></i> Code</a>
                        </div>
                    </div>
                </div>
                <div class="project-card">
                    <div class="project-image">
                        <div class="image-placeholder">
                            <i class="fas fa-chart-line"></i>
                        </div>
                    </div>
                    <div class="project-content">
                        <h3>Analytics Dashboard</h3>
                        <p>A data visualization dashboard for business metrics with interactive charts and graphs.</p>
                        <div class="project-tech">
                            <span>React</span>
                            <span>D3.js</span>
                            <span>Python</span>
                        </div>
                        <div class="project-links">
                            <a href="#"><i class="fas fa-external-link-alt"></i> Live Demo</a>
                            <a href="#"><i class="fab fa-github"></i> Code</a>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="contact">
        <div class="container">
            <h2 class="section-title">Get In Touch</h2>
            <div class="contact-container">
                <div class="contact-info">
                    <h3>Let's work together</h3>
                    <p>I'm currently available for freelance work or full-time positions. Feel free to reach out if you have a project in mind or just want to connect!</p>
                    <div class="contact-details">
                        <div class="contact-item">
                            <i class="fas fa-envelope"></i>
                            <span>musonijunior7@gmail.com</span>
                        </div>
                        <div class="contact-item">
                            <i class="fas fa-phone"></i>
                            <span>+250 722 357 316</span>
                        </div>
                        <div class="contact-item">
                            <i class="fas fa-map-marker-alt"></i>
                            <span>Kigali, Rwanda</span>
                        </div>
                    </div>
                    <div class="social-links">
                        <a href="#"><i class="fab fa-github"></i></a>
                        <a href="#"><i class="fab fa-linkedin"></i></a>
                        <a href="#"><i class="fab fa-twitter"></i></a>
                        <a href="#"><i class="fab fa-dribbble"></i></a>
                    </div>
                </div>
                <form class="contact-form">
                    <div class="form-group">
                        <input type="text" placeholder="Your Name" required>
                    </div>
                    <div class="form-group">
                        <input type="email" placeholder="Your Email" required>
                    </div>
                    <div class="form-group">
                        <input type="text" placeholder="Subject" required>
                    </div>
                    <div class="form-group">
                        <textarea placeholder="Your Message" rows="5" required></textarea>
                    </div>
                    <button type="submit" class="btn btn-primary">Send Message</button>
                </form>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="footer">
        <div class="container">
            <p>&copy; 2025 Musoni Junior. All rights reserved.</p>
        </div>
    </footer>

    <script src="script.js"></script>
</body>
</html>
[script.js](https://github.com/user-attachments/files/23105942/script.js)
// Mobile Navigation Toggle
const hamburger = document.getElementById('hamburger');
const navMenu = document.getElementById('nav-menu');

hamburger.addEventListener('click', () => {
    hamburger.classList.toggle('active');
    navMenu.classList.toggle('active');
});

// Close mobile menu when clicking on a nav link
document.querySelectorAll('.nav-link').forEach(n => n.addEventListener('click', () => {
    hamburger.classList.remove('active');
    navMenu.classList.remove('active');
}));

// Animate skill bars when they come into view
const skillBars = document.querySelectorAll('.skill-progress');

const animateSkillBars = () => {
    skillBars.forEach(skillBar => {
        const skillValue = skillBar.getAttribute('data-width');
        skillBar.style.width = skillValue;
    });
};

// Use Intersection Observer to trigger animation when skills section is in view
const skillsSection = document.querySelector('.skills');
const observerOptions = {
    root: null,
    threshold: 0.3,
    rootMargin: '0px'
};

const observer = new IntersectionObserver((entries, observer) => {
    entries.forEach(entry => {
        if (entry.isIntersecting) {
            animateSkillBars();
            observer.unobserve(entry.target);
        }
    });
}, observerOptions);

if (skillsSection) {
    observer.observe(skillsSection);
}

// Smooth scrolling for navigation links
document.querySelectorAll('a[href^="#"]').forEach(anchor => {
    anchor.addEventListener('click', function (e) {
        e.preventDefault();
        
        const targetId = this.getAttribute('href');
        if (targetId === '#') return;
        
        const targetElement = document.querySelector(targetId);
        if (targetElement) {
            window.scrollTo({
                top: targetElement.offsetTop - 80,
                behavior: 'smooth'
            });
        }
    });
});

// Navbar background change on scroll
window.addEventListener('scroll', () => {
    const navbar = document.querySelector('.navbar');
    if (window.scrollY > 50) {
        navbar.style.backgroundColor = 'rgba(255, 255, 255, 0.98)';
        navbar.style.boxShadow = '0 5px 15px rgba(0, 0, 0, 0.1)';
    } else {
        navbar.style.backgroundColor = 'rgba(255, 255, 255, 0.95)';
        navbar.style.boxShadow = '0 2px 10px rgba(0, 0, 0, 0.1)';
    }
});
[style.css](https://github.com/user-attachments/files/23105946/style.css)
/* Reset and Base Styles */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

:root {
    --primary-color: #6c63ff;
    --secondary-color: #4a44c9;
    --dark-color: #2a2a3c;
    --light-color: #f8f9fa;
    --gray-color: #6c757d;
    --white: #ffffff;
    --black: #000000;
    --transition: all 0.3s ease;
}

html {
    scroll-behavior: smooth;
}

body {
    font-family: 'Poppins', sans-serif;
    line-height: 1.6;
    color: var(--dark-color);
    background-color: var(--white);
    overflow-x: hidden;
}

.container {
    width: 90%;
    max-width: 1200px;
    margin: 0 auto;
    padding: 0 15px;
}

section {
    padding: 80px 0;
}

.section-title {
    font-size: 2.5rem;
    text-align: center;
    margin-bottom: 60px;
    position: relative;
}

.section-title::after {
    content: '';
    position: absolute;
    bottom: -15px;
    left: 50%;
    transform: translateX(-50%);
    width: 80px;
    height: 4px;
    background-color: var(--primary-color);
    border-radius: 2px;
}

.btn {
    display: inline-block;
    padding: 12px 30px;
    border-radius: 30px;
    text-decoration: none;
    font-weight: 500;
    transition: var(--transition);
    border: none;
    cursor: pointer;
    font-size: 1rem;
}

.btn-primary {
    background-color: var(--primary-color);
    color: var(--white);
}

.btn-primary:hover {
    background-color: var(--secondary-color);
    transform: translateY(-3px);
    box-shadow: 0 10px 20px rgba(108, 99, 255, 0.3);
}

.btn-secondary {
    background-color: transparent;
    color: var(--primary-color);
    border: 2px solid var(--primary-color);
}

.btn-secondary:hover {
    background-color: var(--primary-color);
    color: var(--white);
    transform: translateY(-3px);
    box-shadow: 0 10px 20px rgba(108, 99, 255, 0.3);
}

.highlight {
    color: var(--primary-color);
}

/* Navigation */
.navbar {
    position: fixed;
    top: 0;
    left: 0;
    width: 100%;
    background-color: rgba(255, 255, 255, 0.95);
    box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
    z-index: 1000;
    transition: var(--transition);
}

.nav-container {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 20px 0;
}

.nav-logo a {
    font-size: 1.8rem;
    font-weight: 700;
    color: var(--dark-color);
    text-decoration: none;
}

.nav-menu {
    display: flex;
    gap: 30px;
}

.nav-link {
    color: var(--dark-color);
    text-decoration: none;
    font-weight: 500;
    transition: var(--transition);
    position: relative;
}

.nav-link:hover {
    color: var(--primary-color);
}

.nav-link::after {
    content: '';
    position: absolute;
    bottom: -5px;
    left: 0;
    width: 0;
    height: 2px;
    background-color: var(--primary-color);
    transition: var(--transition);
}

.nav-link:hover::after {
    width: 100%;
}

.hamburger {
    display: none;
    flex-direction: column;
    cursor: pointer;
}

.bar {
    width: 25px;
    height: 3px;
    background-color: var(--dark-color);
    margin: 3px 0;
    transition: var(--transition);
}

/* Hero Section */
.hero {
    padding: 150px 0 100px;
    background: linear-gradient(135deg, #f5f7fa 0%, #c3cfe2 100%);
}

.hero-container {
    display: flex;
    align-items: center;
    justify-content: space-between;
    gap: 50px;
}

.hero-content {
    flex: 1;
}

.hero-title {
    font-size: 3.5rem;
    margin-bottom: 15px;
    line-height: 1.2;
}

.hero-subtitle {
    font-size: 1.8rem;
    color: var(--gray-color);
    margin-bottom: 20px;
    font-weight: 400;
}

.hero-description {
    font-size: 1.1rem;
    margin-bottom: 30px;
    color: var(--gray-color);
    max-width: 500px;
}

.hero-buttons {
    display: flex;
    gap: 15px;
    flex-wrap: wrap;
}

.hero-image {
    flex: 1;
    display: flex;
    justify-content: center;
}

.image-placeholder {
    width: 350px;
    height: 350px;
    background: linear-gradient(135deg, var(--primary-color), var(--secondary-color));
    border-radius: 50%;
    display: flex;
    align-items: center;
    justify-content: center;
    color: var(--white);
    font-size: 8rem;
    box-shadow: 0 20px 40px rgba(108, 99, 255, 0.3);
}

/* About Section */
.about {
    background-color: var(--light-color);
}

.about-content {
    display: flex;
    align-items: center;
    gap: 50px;
}

.about-text {
    flex: 1;
}

.about-text p {
    margin-bottom: 20px;
    font-size: 1.1rem;
    color: var(--gray-color);
}

.about-stats {
    display: flex;
    justify-content: space-between;
    margin-top: 40px;
}

.stat {
    text-align: center;
}

.stat h3 {
    font-size: 2.5rem;
    color: var(--primary-color);
    margin-bottom: 5px;
}

.stat p {
    font-size: 1rem;
    color: var(--gray-color);
}

/* Skills Section */
.skills-container {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    gap: 50px;
}

.skill-category h3 {
    font-size: 1.5rem;
    margin-bottom: 20px;
    color: var(--dark-color);
}

.skill-item {
    margin-bottom: 20px;
}

.skill-item span {
    display: block;
    margin-bottom: 8px;
    font-weight: 500;
}

.skill-bar {
    height: 10px;
    background-color: #e9ecef;
    border-radius: 5px;
    overflow: hidden;
}

.skill-progress {
    height: 100%;
    background: linear-gradient(to right, var(--primary-color), var(--secondary-color));
    border-radius: 5px;
    width: 0;
    transition: width 1.5s ease;
}

/* Projects Section */
.projects {
    background-color: var(--light-color);
}

.projects-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    gap: 30px;
}

.project-card {
    background-color: var(--white);
    border-radius: 10px;
    overflow: hidden;
    box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
    transition: var(--transition);
}

.project-card:hover {
    transform: translateY(-10px);
    box-shadow: 0 15px 30px rgba(0, 0, 0, 0.15);
}

.project-image {
    height: 200px;
    background-color: #f8f9fa;
    display: flex;
    align-items: center;
    justify-content: center;
}

.project-image .image-placeholder {
    width: 80px;
    height: 80px;
    font-size: 2.5rem;
}

.project-content {
    padding: 25px;
}

.project-content h3 {
    font-size: 1.5rem;
    margin-bottom: 10px;
}

.project-content p {
    color: var(--gray-color);
    margin-bottom: 15px;
}

.project-tech {
    display: flex;
    flex-wrap: wrap;
    gap: 10px;
    margin-bottom: 20px;
}

.project-tech span {
    background-color: #e9ecef;
    padding: 5px 10px;
    border-radius: 20px;
    font-size: 0.8rem;
    color: var(--dark-color);
}

.project-links {
    display: flex;
    gap: 15px;
}

.project-links a {
    color: var(--primary-color);
    text-decoration: none;
    font-weight: 500;
    display: flex;
    align-items: center;
    gap: 5px;
    transition: var(--transition);
}

.project-links a:hover {
    color: var(--secondary-color);
}

/* Contact Section */
.contact-container {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    gap: 50px;
}

.contact-info h3 {
    font-size: 1.8rem;
    margin-bottom: 20px;
}

.contact-info p {
    color: var(--gray-color);
    margin-bottom: 30px;
}

.contact-details {
    margin-bottom: 30px;
}

.contact-item {
    display: flex;
    align-items: center;
    margin-bottom: 15px;
}

.contact-item i {
    width: 40px;
    height: 40px;
    background-color: var(--primary-color);
    color: var(--white);
    border-radius: 50%;
    display: flex;
    align-items: center;
    justify-content: center;
    margin-right: 15px;
}

.social-links {
    display: flex;
    gap: 15px;
}

.social-links a {
    width: 40px;
    height: 40px;
    background-color: var(--primary-color);
    color: var(--white);
    border-radius: 50%;
    display: flex;
    align-items: center;
    justify-content: center;
    text-decoration: none;
    transition: var(--transition);
}

.social-links a:hover {
    background-color: var(--secondary-color);
    transform: translateY(-5px);
}

.contact-form {
    display: flex;
    flex-direction: column;
    gap: 20px;
}

.form-group {
    display: flex;
    flex-direction: column;
}

.form-group input,
.form-group textarea {
    padding: 15px;
    border: 1px solid #e9ecef;
    border-radius: 5px;
    font-family: 'Poppins', sans-serif;
    transition: var(--transition);
}

.form-group input:focus,
.form-group textarea:focus {
    outline: none;
    border-color: var(--primary-color);
    box-shadow: 0 0 0 3px rgba(108, 99, 255, 0.1);
}

/* Footer */
.footer {
    background-color: var(--dark-color);
    color: var(--white);
    text-align: center;
    padding: 30px 0;
}

/* Responsive Design */
@media (max-width: 992px) {
    .hero-container {
        flex-direction: column;
        text-align: center;
    }
    
    .hero-description {
        margin: 0 auto 30px;
    }
    
    .hero-buttons {
        justify-content: center;
    }
    
    .about-content {
        flex-direction: column;
    }
}

@media (max-width: 768px) {
    .nav-menu {
        position: fixed;
        top: 80px;
        right: -100%;
        flex-direction: column;
        background-color: var(--white);
        width: 80%;
        text-align: center;
        transition: 0.3s;
        box-shadow: 0 10px 27px rgba(0, 0, 0, 0.05);
        padding: 20px 0;
        border-radius: 0 0 10px 10px;
    }
    
    .nav-menu.active {
        right: 0;
    }
    
    .nav-link {
        padding: 15px;
        display: block;
    }
    
    .hamburger {
        display: flex;
    }
    
    .hamburger.active .bar:nth-child(2) {
        opacity: 0;
    }
    
    .hamburger.active .bar:nth-child(1) {
        transform: translateY(8px) rotate(45deg);
    }
    
    .hamburger.active .bar:nth-child(3) {
        transform: translateY(-8px) rotate(-45deg);
    }
    
    .hero-title {
        font-size: 2.8rem;
    }
    
    .hero-subtitle {
        font-size: 1.5rem;
    }
    
    .section-title {
        font-size: 2rem;
    }
    
    .about-stats {
        flex-direction: column;
        gap: 30px;
    }
}

@media (max-width: 576px) {
    .hero-title {
        font-size: 2.2rem;
    }
    
    .hero-subtitle {
        font-size: 1.3rem;
    }
    
    .image-placeholder {
        width: 250px;
        height: 250px;
        font-size: 6rem;
    }
    
    .hero-buttons {
        flex-direction: column;
        align-items: center;
    }
    
    .btn {
        width: 100%;
        max-width: 250px;
        text-align: center;
    }
}
