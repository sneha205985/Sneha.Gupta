---
layout: default
title: Sneha Gupta
---

<div class="landing-container">
    <!-- Header Section -->
    <header class="landing-header">
        <h1>Sneha Gupta</h1>
        <p class="header-subtitle">PhD Applicant in Computer Science</p>
        <p class="header-focus">Reinforcement Learning & Optimization for Human–Robot Interaction</p>
    </header>

   <!-- About Me Section -->
<section class="about-section">
    <div class="about-content">
        <p>I am advancing the next generation of intelligent, human-centric robotic systems through <strong>Reinforcement Learning (RL) and Optimization-based control</strong>, focusing on enabling robots to learn adaptively while maintaining safety, stability, and predictable behaviour during interaction with humans. My work lies at the intersection of Human–Robot Interaction (HRI), Safe RL, and Control Optimization, where I design algorithms and shared-control frameworks that support reliable and interpretable robot behaviour in dynamic, real-world environments.</p>
        
        <p>My recent work involves building a unified safe RL benchmark for human–robot shared control, integrating CBF/QP-based shielding, constrained-policy optimisation, and performance-guaranteed decision-making. I am particularly interested in how optimisation-driven RL can contribute to trustworthy collaboration between humans and autonomous systems, enabling robots to balance exploration, safety, and task efficiency during close-proximity interaction.</p>
        
        <p>My background in Information Technology engineering, combined with hands-on experience in AI development, data analysis, and applied research, has shaped a strong foundation for PhD-level research in robotics and learning-based control. I aim to advance scalable, interpretable, and safety-aware robot-learning systems that can collaborate with humans across shared-workspace, assistive, and multi-robot settings. I am seeking PhD opportunities in Computer Science (Robotics) for Fall 2026.</p>
    </div>

        <!-- Research Interests Only -->
        <div class="interests-section">
            <h3>Research Interests</h3>
            <div class="interests-grid">
                <span class="interest-tag">Safe Reinforcement Learning</span>
                <span class="interest-tag">Human–Robot Interaction (HRI)</span>
                <span class="interest-tag">Optimization-Based Control</span>
                <span class="interest-tag">Shared Autonomy & Intent Prediction</span>
            </div>
        </div>
    </section>

    <!-- Quick Navigation -->
    <section class="nav-section">
        <div class="nav-buttons">
            <a href="/Sneha.Gupta/publications" class="nav-btn">Publications</a>
            <a href="/Sneha.Gupta/projects" class="nav-btn">Projects</a>
            <a href="/Sneha.Gupta/research" class="nav-btn">Research</a>
        </div>
    </section>

    <!-- CV Section -->
    <section class="cv-section">
        <h2>Curriculum Vitae</h2>
        <p>View my professional background, experience, and skills. The CV is typeset in LaTeX for optimal readability.</p>
        
        <div class="cv-preview">
            <div class="cv-controls">
                <button onclick="zoomInCV()" class="cv-control-btn">Zoom In</button>
                <button onclick="zoomOutCV()" class="cv-control-btn">Zoom Out</button>
                <button onclick="resetZoomCV()" class="cv-control-btn">Reset Zoom</button>
                <a href="{{ site.baseurl }}/assets/cv/cv.pdf" download class="cv-download-btn">Download PDF</a>
            </div>
            
            <div class="pdf-viewer">
                <iframe 
                    id="cv-pdf"
                    src="{{ site.baseurl }}/assets/cv/cv.pdf#view=FitH"
                    width="100%" 
                    height="500"
                    frameborder="0"
                    allowfullscreen>
                </iframe>
            </div>
        </div>
    </section>

    <!-- Contact Section at Bottom -->
    <section class="contact-section">
        <h3>Get in Touch</h3>
        <div class="contact-links">
            <a href="mailto:snehaguptta005@gmail.com" class="contact-link">Email</a>
            <a href="https://github.com/sneha205985" target="_blank" class="contact-link">GitHub</a>
            <a href="https://www.linkedin.com/in/sneha-gupta34/" target="_blank" class="contact-link">LinkedIn</a>
        </div>
    </section>
</div>

<style>
.landing-container {
    max-width: 900px;
    margin: 0 auto;
    padding: 2rem 1rem;
    line-height: 1.6;
}

.landing-header {
    text-align: center;
    margin-bottom: 3rem;
    padding-bottom: 2rem;
    border-bottom: 2px solid #f0f0f0;
}

.landing-header h1 {
    font-size: 2.8rem;
    margin-bottom: 0.5rem;
    color: #000;
    font-weight: 700;
}

.header-subtitle {
    font-size: 1.3rem;
    color: #666;
    margin-bottom: 0.5rem;
    font-weight: 500;
}

.header-focus {
    font-size: 1.1rem;
    color: #888;
    font-style: italic;
}

.about-section {
    margin-bottom: 3rem;
}

.about-content {
    margin-bottom: 2.5rem;
}

.about-content p {
    font-size: 1.1rem;
    margin-bottom: 1.2rem;
    color: #333;
}

.interests-section {
    margin-top: 2rem;
}

.interests-section h3 {
    color: #333;
    margin-bottom: 1rem;
    font-size: 1.3rem;
}

.interests-grid {
    display: flex;
    flex-wrap: wrap;
    gap: 0.8rem;
}

.interest-tag {
    background: #000;
    color: white;
    padding: 0.5rem 1rem;
    border-radius: 20px;
    font-size: 0.9rem;
    font-weight: 500;
}

/* Navigation Section */
.nav-section {
    margin-bottom: 3rem;
}

.nav-buttons {
    display: flex;
    gap: 1rem;
    justify-content: center;
    flex-wrap: wrap;
}

.nav-btn {
    padding: 0.8rem 2rem;
    background: #000;
    color: white;
    text-decoration: none;
    border-radius: 4px;
    font-size: 1rem;
    transition: background 0.2s, transform 0.2s;
    flex: 1;
    max-width: 200px;
    text-align: center;
}

.nav-btn:hover {
    background: #333;
    transform: translateY(-2px);
}

/* CV Section */
.cv-section {
    margin-bottom: 3rem;
}

.cv-section h2 {
    color: #333;
    margin-bottom: 1rem;
}

.cv-controls {
    margin-bottom: 1rem;
    text-align: center;
}

.cv-control-btn {
    padding: 0.6rem 1.2rem;
    margin: 0 0.3rem;
    background: #000;
    color: white;
    border: none;
    border-radius: 4px;
    cursor: pointer;
    font-size: 0.9rem;
    transition: background 0.2s;
}

.cv-control-btn:hover {
    background: #333;
}

.cv-download-btn {
    padding: 0.6rem 1.2rem;
    background: #000;
    color: white;
    text-decoration: none;
    border-radius: 4px;
    font-size: 0.9rem;
    transition: background 0.2s;
}

.cv-download-btn:hover {
    background: #333;
}

.pdf-viewer {
    border: 1px solid #eaeaea;
    border-radius: 8px;
    overflow: hidden;
    background-color: #f8f9fa;
}

/* Contact Section */
.contact-section {
    text-align: center;
    padding: 2rem 0;
    border-top: 1px solid #f0f0f0;
}

.contact-section h3 {
    color: #333;
    margin-bottom: 1.5rem;
    font-size: 1.3rem;
}

.contact-links {
    display: flex;
    gap: 1rem;
    justify-content: center;
    flex-wrap: wrap;
}

.contact-link {
    padding: 0.8rem 1.5rem;
    background: #000;
    color: white;
    text-decoration: none;
    border-radius: 4px;
    font-size: 0.9rem;
    transition: background 0.2s;
}

.contact-link:hover {
    background: #333;
}

@media (max-width: 768px) {
    .landing-header h1 {
        font-size: 2.2rem;
    }
    
    .nav-buttons {
        flex-direction: column;
        align-items: center;
    }
    
    .nav-btn {
        width: 100%;
        max-width: 250px;
    }
    
    .cv-controls {
        display: flex;
        flex-wrap: wrap;
        gap: 0.5rem;
        justify-content: center;
    }
    
    .cv-control-btn, .cv-download-btn {
        margin: 0.2rem;
    }
    
    .contact-links {
        flex-direction: column;
        align-items: center;
    }
    
    .contact-link {
        width: 200px;
    }
}
</style>

<script>
let currentZoomCV = 1;
const zoomStepCV = 0.1;
const minZoomCV = 0.5;
const maxZoomCV = 3;

function zoomInCV() {
    if (currentZoomCV < maxZoomCV) {
        currentZoomCV += zoomStepCV;
        updateZoomCV();
    }
}

function zoomOutCV() {
    if (currentZoomCV > minZoomCV) {
        currentZoomCV -= zoomStepCV;
        updateZoomCV();
    }
}

function resetZoomCV() {
    currentZoomCV = 1;
    updateZoomCV();
}

function updateZoomCV() {
    const iframe = document.getElementById('cv-pdf');
    iframe.style.transform = `scale(${currentZoomCV})`;
    iframe.style.transformOrigin = 'top left';
    iframe.style.width = `${100 / currentZoomCV}%`;
    iframe.style.height = `${500 / currentZoomCV}px`;
}
</script>