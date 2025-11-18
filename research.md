---
layout: default
title: Research Vision
permalink: /research/
---

<div style="max-width: 800px; margin: 0 auto;">

<div class="project featured">
    <div class="project-header">
        <h3>Research Focus: Reinforcement Learning & Optimization for Human-Centered Robotics</h3>
        <span class="project-status">Active Research</span>
    </div>
    
    <div class="project-meta">
        <span class="project-tech">Artificial Intelligence • Robotics • Reinforcement Learning • Optimization-Based Control</span>
    </div>
    
    <p class="project-description">
        My research focuses on developing robotic systems that can learn adaptively while guaranteeing safety, especially in environments shared with humans—a central challenge in Human–Robot Interaction (HRI). I combine Reinforcement Learning (RL) with optimization-based control methods—such as Control Barrier Functions (CBF-QP) and Model Predictive Control (MPC)—to enable robots to learn complex behaviours while strictly respecting physical, safety, and operational constraints.
    </p>

    <div class="project-features">
        <h4>The Challenge with Current Robotic Learning</h4>
        <ul>
            <li><strong>Reinforcement Learning is powerful but unsafe</strong> — standard RL may violate safety constraints during exploration or deployment, especially around humans.</li>
            <li><strong>Optimization-based controllers are safe but rigid</strong> — MPC, PID, and CBF-QP ensure stability and constraint satisfaction but cannot learn new behaviours from interaction.</li>
            <li><strong>Human behavior is uncertain</strong> — robots must understand intent, anticipate motion, and maintain safe distances in unpredictable environments.</li>
        </ul>
    </div>

    <div class="project-results">
        <h4>Why This Matters</h4>
        <p>Consider a robot assisting a human worker in a shared workspace:</p>
        <ul>
            <li>A pure RL policy can learn the task but may break safety boundaries or behave unpredictably under uncertainty.</li>
            <li>A pure classical controller maintains safety but fails to adapt when the human moves unexpectedly, or the task dynamics change.</li>  
            <li>A hybrid RL + optimization approach allows the robot to:
                <ul>
                    <li>learn efficient, adaptable behaviours,</li>
                    <li>predict human motion or intent,</li>
                    <li>and enforce safety constraints through real-time optimization.</li>
                </ul>
            </li>
        </ul>
        <p>This combination is essential for building robots that can safely assist, collaborate, and interact with people in real-world settings.</p>
    </div>
</div>

<div class="project featured">
    <div class="project-header">
        <h3>Research Directions</h3>
        <span class="project-status">Current Focus</span>
    </div>

    <div class="project-features">
        <h4>1. Safe Reinforcement Learning Algorithms</h4>
        <p>Developing reinforcement learning methods that can learn high-performance behaviours while provably avoiding unsafe actions. My work explores constrained RL, dual-variable stability, and probabilistic safety guarantees to ensure learning remains safe even in unpredictable human-centered environments, particularly during close-proximity human–robot collaboration.</p>
        <p><strong>Key Question:</strong> How can RL agents learn and adapt efficiently while guaranteeing safety throughout training and deployment?</p>
    </div>

    <div class="project-features">
        <h4>2. Optimization-Based Safety Shields (CBF-QP, MPC)</h4>
        <p>Integrating optimization-based controllers such as Control Barrier Functions, Quadratic Programs, and Model Predictive Control to provide real-time safety corrections around RL policies. These mechanisms ensure stability, constraint satisfaction, and verifiable safety when robots operate near humans.</p>
        <p><strong>Key Question:</strong> How can optimization methods provide immediate, mathematically guaranteed safety around learned policies?</p>
    </div>

    <div class="project-features">
        <h4>3. Human–Robot Shared Control & Intent Prediction</h4>
        <p>Designing predictive models and shared-control frameworks that allow robots to anticipate human behaviour, adjust their actions dynamically, and maintain safe collaboration. This includes modelling human motion, predicting intent, and enforcing interaction constraints in real time.</p>
        <p><strong>Key Question:</strong> How can robots understand and predict human behaviour to support smooth, safe human-robot cooperation?</p>
    </div>

    <div class="project-features">
        <h4>4. Applications in Critical Robotic Domains</h4>
        <p>I'm particularly interested in applying safe RL and optimization to domains where safety, reliability, and adaptability are essential — especially when robots operate close to humans or in high-risk environments.</p>
        
        <p><strong>Human-Centered Robotics</strong></p>
        <ul>
            <li>Assistive robots that maintain safe distances while adapting to human motion</li>
            <li>Collaborative robots (cobots) that predict human intent and coordinate actions</li>
            <li>Robots that enforce physical and interaction constraints in real time</li>
            <li>Shared-control frameworks for joint human–robot manipulation</li>
            <li>Real-time safety during physical human–robot interaction (pHRI)</li>
        </ul>

        <p><strong>Autonomous Systems & Mobility</strong></p>
        <ul>
            <li>Robots and vehicles that guarantee safe exploration under uncertainty</li>
            <li>Systems that use RL + optimization to respect safety limits</li>
            <li>Agents capable of real-time risk assessment in dynamic environments</li>
        </ul>

        <p><strong>Healthcare & Rehabilitation Robotics</strong></p>
        <ul>
            <li>Medical robots that ensure safety in physical interaction</li>
            <li>Personalized assistive systems that adapt to patient behaviour</li>
            <li>Safe RL for prosthetics, exoskeletons, and therapy robots</li>
        </ul>

        <p><strong>Industrial & Manufacturing Robotics</strong></p>
        <ul>
            <li>Robots performing precision tasks under strict safety budgets</li>
            <li>Systems that generalise across varying conditions and tools</li>
            <li>Real-time safety enforcement during high-speed operations</li>
        </ul>

        <p><strong>Scientific & Exploration Robotics</strong></p>
        <ul>
            <li>Robots operating safely in unstructured, high-uncertainty settings</li>
            <li>Safe exploration in disaster response or space missions</li>
            <li>Systems that reason about environmental constraints during execution</li>
        </ul>
    </div>
</div>

<div class="project featured">
    <div class="project-header">
        <h3>The Big Picture</h3>
        <span class="project-status">Research Vision</span>
    </div>
    
    <p class="project-description">
        As robots increasingly operate in close proximity to humans—in homes, hospitals, factories, and rehabilitation settings—the need for systems that are safe, predictable, adaptive, and trustworthy becomes critical. Reinforcement Learning combined with optimization-based control provides a path toward autonomous systems that can learn from experience while maintaining formal safety guarantees.
    </p>

    <div class="project-features">
        <h4>Research Objectives</h4>
        <ul>
            <li><strong>Trustworthy Autonomous Robots</strong> - Robots whose decisions can be verified, validated, and trusted under uncertainty.</li>
            <li><strong>Collaborative Human-Aware Systems</strong> - Robots that understand human intent, anticipate actions, and work alongside people safely and efficiently.</li>  
            <li><strong>Adaptable and Generalizable Learning</strong> - Learning agents that apply knowledge across new tasks while satisfying real-world constraints.</li>
            <li><strong>Safety-Critical AI</strong> - Autonomous systems that maintain safety even during exploration, learning, and unexpected scenarios.</li>
        </ul>
    </div>

    <div class="project-results">
        <h4>Long-term Impact</h4>
        <p>My long-term vision is to build the theoretical foundations and practical systems required for real-world safe robotic autonomy. This includes:</p>
        <ul>
            <li>RL algorithms with formal guarantees,</li>
            <li>Optimization-based safety mechanisms that scale to complex robots,</li>
            <li>Human-centered control frameworks that anticipate and respect human behaviour,</li>
            <li>and robust sim-to-real pipelines that enable safe deployment.</li>
        </ul>
        <p>Through this work, I aim to advance a future where robots can learn, adapt, and collaborate safely—creating autonomous systems that are not only intelligent but also aligned with human needs, values, and safety requirements.</p>
    </div>
</div>

</div>

<style>
.project {
    border: 1px solid #eaeaea;
    border-radius: 8px;
    padding: 2rem;
    margin-bottom: 2.5rem;
    transition: transform 0.2s, box-shadow 0.2s;
}

.project.featured {
    border-left: 4px solid #000;
    background: #fafafa;
}

.project:hover {
    transform: translateY(-2px);
    box-shadow: 0 4px 12px rgba(0,0,0,0.1);
}

.project-header {
    display: flex;
    justify-content: space-between;
    align-items: flex-start;
    margin-bottom: 1rem;
    flex-wrap: wrap;
    gap: 1rem;
}

.project-header h3 {
    color: #000;
    margin: 0;
    font-size: 1.4rem;
    flex: 1;
    min-width: 300px;
}

.project-status {
    background: #000;
    color: white;
    padding: 0.3rem 0.8rem;
    border-radius: 4px;
    font-size: 0.9rem;
    font-weight: 500;
    white-space: nowrap;
}

.project-meta {
    display: flex;
    justify-content: space-between;
    align-items: center;
    margin-bottom: 1.5rem;
    flex-wrap: wrap;
    gap: 1rem;
}

.project-tech {
    color: #666;
    font-family: 'Monaco', 'Menlo', monospace;
    font-size: 0.9rem;
}

.project-date {
    color: #888;
    font-size: 0.9rem;
}

.project-description {
    color: #333;
    line-height: 1.6;
    margin-bottom: 1.5rem;
    font-size: 1.1rem;
}

.project-features, .project-results {
    margin-bottom: 1.5rem;
}

.project-features h4, .project-results h4 {
    color: #000;
    margin-bottom: 0.5rem;
    font-size: 1.1rem;
}

.project-features ul, .project-results ul {
    list-style: none;
    padding-left: 0;
}

.project-features li, .project-results li {
    padding: 0.3rem 0;
    position: relative;
    padding-left: 1.5rem;
    color: #333;
}

/* Changed from green checkmarks to black dots */
.project-features li:before, .project-results li:before {
    content: "•";
    position: absolute;
    left: 0;
    color: #000;
    font-weight: bold;
    font-size: 1.2rem;
}

.project-links {
    display: flex;
    gap: 1rem;
    flex-wrap: wrap;
}

.project-link {
    display: inline-block;
    padding: 0.5rem 1.2rem;
    background: #000;
    color: white;
    text-decoration: none;
    border-radius: 4px;
    font-size: 0.9rem;
    transition: background 0.2s;
}

.project-link:hover {
    background: #333;
}

@media (max-width: 768px) {
    .project-header {
        flex-direction: column;
        align-items: flex-start;
    }
    
    .project-header h3 {
        min-width: auto;
    }
    
    .project-meta {
        flex-direction: column;
        align-items: flex-start;
    }
}
</style>
