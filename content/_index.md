---
title: ''
date: 2026-10-06
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: About
      username: admin

  - block: markdown
    id: impact
    content:
      title: ''
      text: |-
        <div class="impact-grid" role="list" aria-label="Research and career highlights">
          <div class="impact-stat" role="listitem">
            <span class="impact-value">300+</span>
            <span class="impact-label">Google Scholar citations</span>
          </div>
          <div class="impact-stat" role="listitem">
            <span class="impact-value">h-index 7</span>
            <span class="impact-label">Research impact</span>
          </div>
          <div class="impact-stat" role="listitem">
            <span class="impact-value">10+ years</span>
            <span class="impact-label">Working in AI and robotics</span>
          </div>
          <div class="impact-stat" role="listitem">
            <span class="impact-value">3rd place</span>
            <span class="impact-label">MBZIRC 2020 Grand Challenge</span>
          </div>
        </div>
    design:
      columns: '1'

  - block: markdown
    id: research
    content:
      title: Research Focus
      subtitle: Building intelligent systems that operate beyond their training conditions.
      text: |-
        <div class="focus-grid">
          <article class="focus-card">
            <span class="focus-index">01</span>
            <h3>Generalizable Autonomy</h3>
            <p>Methods that help intelligent and autonomous systems perceive, reason, and adapt when conditions differ from those seen during training.</p>
          </article>
          <article class="focus-card">
            <span class="focus-index">02</span>
            <h3>Embodied & Adaptive AI</h3>
            <p>World models, adaptive agents, planning, memory, and robot learning for agents that interact with complex environments.</p>
          </article>
          <article class="focus-card">
            <span class="focus-index">03</span>
            <h3>Perception for Autonomous Systems</h3>
            <p>Computer vision and deep learning for robotics, UAVs, industrial inspection, material understanding, and real-world deployment.</p>
          </article>
        </div>
    design:
      columns: '1'

  - block: markdown
    id: projects
    content:
      title: Selected Work
      subtitle: Research directions and applied systems across autonomy, perception, and learning.
      text: |-
        <div class="work-grid">
          <article class="work-card work-card--autonomy">
            <div class="work-card__meta">Research leadership · ARQUIMEA</div>
            <h3>Generalizable Autonomy</h3>
            <p>Leading research on intelligent and autonomous systems that combine world models, planning, memory, adaptation, and robot learning.</p>
            <div class="tag-row"><span>World models</span><span>Planning</span><span>Memory</span><span>Robot learning</span></div>
            <a class="work-link" href="https://www.arquimea.com/es/imasd/research-center/">ARQUIMEA Research Center <span aria-hidden="true">↗</span></a>
          </article>
          <article class="work-card work-card--adaptive">
            <div class="work-card__meta">Doctoral research · UPM</div>
            <h3>Adaptive Learning for Robotic Perception</h3>
            <p>Weak supervision and adaptive learning methods aimed at reducing data requirements and improving deep-learning systems for real-world robotic perception.</p>
            <div class="tag-row"><span>Weak supervision</span><span>Domain adaptation</span><span>Robotic perception</span></div>
            <a class="work-link" href="/publication/phd_thesis24/">View doctoral thesis <span aria-hidden="true">→</span></a>
          </article>
          <article class="work-card work-card--robotics">
            <div class="work-card__meta">Autonomous systems · UAVs</div>
            <h3>Autonomous Aerial Robotics</h3>
            <p>Perception and autonomous-system development for UAV inspection, navigation, trajectory generation, and high-speed search and interception.</p>
            <div class="tag-row"><span>Computer vision</span><span>UAVs</span><span>Motion planning</span><span>Embedded AI</span></div>
            <a class="work-link" href="/project/mbzirc/">Explore MBZIRC project <span aria-hidden="true">→</span></a>
          </article>
          <article class="work-card work-card--materials">
            <div class="work-card__meta">Applied computer vision · SEDDI</div>
            <h3>Visual Material Understanding</h3>
            <p>Learning-based methods for single-image fabric digitization and material appearance modelling, including reflectance, opacity, and transmittance estimation.</p>
            <div class="tag-row"><span>Material capture</span><span>Generative models</span><span>SVBSDF</span></div>
            <a class="work-link" href="/publication/flatbed_scanner25/">View publication <span aria-hidden="true">→</span></a>
          </article>
        </div>
    design:
      columns: '1'

  - block: collection
    id: publications
    content:
      title: Selected Publications
      subtitle: Peer-reviewed work spanning autonomy, robotic perception, computer vision, and applied machine learning.
      count: 6
      filters:
        folders:
          - publication
        featured_only: true
        exclude_future: false
      order: desc
    design:
      columns: '1'
      view: compact

  - block: markdown
    id: experience
    content:
      title: Experience
      subtitle: A career connecting fundamental AI research with autonomous and industrial systems.
      text: |-
        <div class="career-list">
          <article class="career-item">
            <div class="career-period">2024 — Present</div>
            <div class="career-body">
              <h3>ARQUIMEA Research Center</h3>
              <p class="career-role">Principal Researcher</p>
              <p>Leading the Generalizable Autonomy research line. Previously Project Leader & Postdoctoral Researcher and Postdoctoral Researcher.</p>
              <div class="career-progression"><span>Postdoctoral Researcher · May 2024</span><span>Project Leader · Jun 2025</span><span>Principal Researcher · Jan 2026</span></div>
            </div>
          </article>
          <article class="career-item">
            <div class="career-period">2023 — 2024</div>
            <div class="career-body">
              <h3>SEDDI</h3>
              <p class="career-role">Research Scientist</p>
              <p>Research on learning-based fabric digitization, generative material modelling, and continuous improvement of the neural-network model behind textura.ai.</p>
            </div>
          </article>
          <article class="career-item">
            <div class="career-period">2017 — 2023</div>
            <div class="career-body">
              <h3>Computer Vision and Aerial Robotics Group · UPM</h3>
              <p class="career-role">Research Scientist</p>
              <p>Learning-based computer vision for aerial robotic perception, applied research, industry collaboration, and doctoral work on adaptive learning with weak supervision.</p>
            </div>
          </article>
          <article class="career-item career-item--earlier">
            <div class="career-period">2014 — 2020</div>
            <div class="career-body">
              <h3>Earlier research and engineering roles</h3>
              <p>Research Assistant at UPM GFMC and Universidad de Cádiz, and Consulting Intern at Altran, working across electron microscopy, GPU computing, multiview vision, and immersive manufacturing systems.</p>
            </div>
          </article>
        </div>
    design:
      columns: '1'

  - block: markdown
    id: contact
    content:
      title: Let's Connect
      subtitle: Professional conversations about AI research, autonomous systems, and research collaboration.
      text: |-
        <div class="contact-panel">
          <p>Connect with me through LinkedIn, or explore my complete research record on Google Scholar and ORCID.</p>
          <div class="contact-actions">
            <a class="btn btn-primary btn-lg" href="https://www.linkedin.com/in/francisco-javier-rodriguez-vazquez-b1a764124/">Connect on LinkedIn</a>
            <a class="btn btn-outline-primary btn-lg" href="https://scholar.google.es/citations?user=t1l1vIQAAAAJ&hl=en">Google Scholar</a>
            <a class="btn btn-outline-primary btn-lg" href="https://orcid.org/0000-0003-0305-7806">ORCID</a>
          </div>
        </div>
    design:
      columns: '1'
---
