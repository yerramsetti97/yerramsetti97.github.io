---
layout: default
title: "Home"
---

<style>
  /* Hide site title in the global header so only the page H1 shows */
  .site-header .site-title, .site-header .site-nav { display: none !important; }

  /* Jellybean look: playful bright accent + rounded cards */
  :root {
    --accent: #ff4f7b;       /* jellybean pink/red */
    --accent-dark: #d93a64;
    --card-bg: #ffffff;
    --bg: #f6f7fb;
    --text: #1f2430;
    --muted: #667085;
    --shadow: 0 6px 16px rgba(15, 23, 42, 0.08);
  }
  @media (prefers-color-scheme: dark) {
    :root {
      --card-bg: #111827;
      --bg: #0b1220;
      --text: #e5e7eb;
      --muted: #9aa4b2;
      --shadow: 0 6px 16px rgba(0,0,0,0.35);
    }
  }

  body { background: var(--bg); color: var(--text); }
  .hero {
    text-align: center;
    margin: 56px auto 28px;
  }
  .hero h1 {
    font-size: 2.4rem;
    margin: 0 0 6px;
    letter-spacing: 0.2px;
  }
  .hero h3 {
    margin: 0 0 16px;
    font-weight: 500;
    color: var(--muted);
  }

  .links a {
    display: inline-flex; align-items: center;
    gap: 6px; margin: 0 10px; text-decoration: none;
    color: var(--accent); font-weight: 600;
  }
  .links a:hover { color: var(--accent-dark); }

  section {
    background: var(--card-bg);
    border-radius: 16px;
    padding: 24px 26px;
    margin: 14px auto;
    max-width: 900px;
    box-shadow: var(--shadow);
  }
  section h2 { margin-top: 0; }
  ul { margin: 0.6rem 0 0.2rem 1.1rem; }
  li + li { margin-top: 6px; }

  /* Soft accent underline on section titles */
  h2 {
    position: relative; display: inline-block; padding-bottom: 4px;
  }
  h2:after {
    content: ""; position: absolute; left: 0; bottom: 0;
    width: 42%; height: 3px; border-radius: 2px; background: var(--accent);
  }

  /* Hide site footer duplication if any */
  .site-footer { display: none !important; }
</style>

<div class="hero">
  <h1>Venkata Sai Teja Yerramsetti</h1>
  <h3>Senior .NET Full Stack Developer</h3>
  <p class="links">
    <a href="mailto:vyerramsetti1997@gmail.com">📧 Email</a>
    <a href="https://www.linkedin.com/in/venkata-sai-teja-yerramsetti-595511172/">💼 LinkedIn</a>
    <a href="https://github.com/yerramsetti97">💻 GitHub</a>
  </p>
</div>

<section>
  <h2>About Me</h2>
  <p>
    I'm a <strong>Full Stack .NET Developer</strong> with 7+ years of experience building secure, scalable, and cloud-native enterprise applications across healthcare, finance, and cloud domains.
    I specialize in <strong>.NET 8, ASP.NET Core Web API, Angular, React, and Azure DevOps</strong>, with deep expertise in
    <strong>microservices, CI/CD automation, and cloud migrations</strong> that improve performance and delivery efficiency by up to 50%.
  </p>
</section>

<section>
  <h2>Core Skills</h2>
  <ul>
    <li><strong>Backend:</strong> .NET 8, C#, ASP.NET Core Web API, EF Core 8, LINQ, REST, OAuth2/JWT</li>
    <li><strong>Frontend:</strong> Angular 18, React 18, TypeScript, NgRx, RxJS, Material UI</li>
    <li><strong>Cloud & DevOps:</strong> Azure (AKS, App Services, AD B2C, API Management), Docker, Kubernetes, GitHub Actions, Azure DevOps, SonarQube</li>
    <li><strong>Database:</strong> SQL Server 2022, Redis, EF Core, Query Tuning, Normalization</li>
    <li><strong>Testing & Security:</strong> xUnit, Moq, Jasmine, Karma, OAuth2, TLS, HIPAA/FHIR Compliance</li>
  </ul>
</section>

<section>
  <h2>Professional Experience (Highlights)</h2>

  <h3>BJC Healthcare — <em>Full Stack .NET Developer</em></h3>
  <ul>
    <li>Modernized care coordination into .NET 8 microservices on Azure AKS; Angular 18 front-end.</li>
    <li>FHIR R5 APIs integrating EMR/lab/payer systems; Redis + SQL tuning → ~60% faster APIs.</li>
    <li>CI/CD via Azure DevOps & GitHub Actions with SonarQube gates.</li>
  </ul>

  <h3>HSBC — <em>.NET Full Stack Developer</em></h3>
  <ul>
    <li>Compliance automation platform with .NET 6 + React 18; Onion Arch microservices.</li>
    <li>OAuth2/Azure AD, APIM governance; MongoDB perf + Kafka/RabbitMQ async flows.</li>
  </ul>

  <h3>IBM — <em>IT Analyst / .NET Developer</em></h3>
  <ul>
    <li>Migrated .NET Framework to .NET 6 (EF Core, async); performance tuning on SQL Server.</li>
    <li>Serverless AWS Lambda + S3/SQS for audit and file workflows.</li>
  </ul>
</section>
