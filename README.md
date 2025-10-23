<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>CS50P — Introduction to Programming with Python — README</title>
  <style>
    :root {
      --bg: #ffffff;
      --card: #f7fafc;
      --muted: #4a5568;
      --accent: #2b6cb0;
      --maxw: 900px;
      --radius: 10px;
      --mono: "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif;
    }
    body {
      background: #f3f6f9;
      color: #0f1720;
      font-family: var(--mono);
      line-height: 1.5;
      padding: 28px 16px;
      display: flex;
      justify-content: center;
    }
    .container {
      width: 100%;
      max-width: var(--maxw);
      background: white;
      border-radius: var(--radius);
      box-shadow: 0 6px 18px rgba(16,24,40,0.08);
      padding: 22px;
      border: 1px solid rgba(2,6,23,0.04);
    }
    header {
      display: flex;
      gap: 18px;
      align-items: center;
      border-bottom: 1px solid rgba(15,23,32,0.04);
      padding-bottom: 16px;
      margin-bottom: 16px;
    }
    .svg-banner {
      width: 160px;
      height: 70px;
      flex-shrink: 0;
      display: flex;
      align-items: center;
      justify-content: center;
    }
    h1 {
      margin: 0;
      font-size: 20px;
      color: #0b1220;
    }
    p.lead {
      margin: 6px 0 0 0;
      color: var(--muted);
      font-size: 13px;
    }
    main { padding-top: 6px; }
    section { margin-bottom: 14px; }
    .muted { color: var(--muted); font-size: 14px; }
    pre {
      background: #f8fafc;
      padding: 12px;
      border-radius: 8px;
      overflow-x: auto;
      font-size: 13px;
      color: #0f1720;
      border: 1px solid rgba(2,6,23,0.03);
    }
    table { width: 100%; border-collapse: collapse; font-size: 14px; margin-top: 8px; }
    th, td { text-align: left; padding: 8px; border-bottom: 1px solid rgba(2,6,23,0.04); }
    th { color: #0b1220; font-weight: 600; width: 16%; }
    .footer { margin-top: 18px; border-top: 1px solid rgba(2,6,23,0.04); padding-top: 12px; color: var(--muted); font-size: 13px; display:flex; justify-content:space-between; align-items:center; gap:12px; }
    a { color: var(--accent); text-decoration: none; }
    .emoji { font-size: 16px; margin-right: 6px; vertical-align: middle; }
  </style>
</head>
<body>
  <div class="container" role="main">
    <header>
      <div class="svg-banner" aria-hidden="true">
        <!-- Lightweight inline SVG banner (no external images, very small) -->
        <svg width="160" height="70" viewBox="0 0 320 140" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="CS50P banner">
          <rect rx="8" ry="8" width="320" height="140" fill="#0b1220" />
          <g transform="translate(18,20)">
            <circle cx="36" cy="18" r="12" fill="#2b6cb0"/>
            <rect x="24" y="36" width="24" height="6" rx="3" fill="#ffd05a"/>
            <text x="88" y="54" font-family="Segoe UI, Roboto, Arial" font-size="42" fill="#ffffff">CS50</text>
            <text x="88" y="94" font-family="Segoe UI, Roboto, Arial" font-size="16" fill="#cbd5e1">CS50P • Python</text>
          </g>
        </svg>
      </div>
      <div>
        <h1>CS50P — Introduction to Programming with Python</h1>
        <p class="lead">A formal collection of weekly assignments and projects completed using the CS50 Duck IDE. <span class="emoji">🧾</span></p>
        <p class="muted">Repository: <strong>CS50P (Course Work)</strong> · Environment: <strong>CS50 Duck IDE</strong></p>
      </div>
    </header>

    <main>
      <section>
        <h2>Overview</h2>
        <p class="muted">This repository contains my completed work for Harvard’s <strong>CS50P</strong> course. Each folder maps to a weekly module of the curriculum and includes exercises, problem sets, and project artifacts. All development, testing, and submission were performed using the official <strong>CS50 Duck IDE</strong> to ensure consistency with course tooling and grading utilities.</p>
      </section>

      <section>
        <h2>Repository Structure</h2>
        <pre>
CS50P/
├── week0/
├── week1/
├── week2/
├── week3/
├── week4/
├── week5/
├── week6/
├── week7/
├── week8/
└── final_project/
        </pre>
        <p class="muted">Each week folder contains source files and, where applicable, test files compatible with <code>pytest</code> and CS50’s automated checkers.</p>
      </section>

      <section>
        <h2>Topics Covered</h2>
        <table>
          <thead><tr><th>Week</th><th>Title</th><th>Key Concepts</th></tr></thead>
          <tbody>
            <tr><td>0</td><td>Functions, Variables</td><td>Syntax, Input/Output, Conditionals</td></tr>
            <tr><td>1</td><td>Loops</td><td>Iteration, Control Flow</td></tr>
            <tr><td>2</td><td>Strings</td><td>Manipulation, Methods, Validation</td></tr>
            <tr><td>3</td><td>Exceptions</td><td>Error Handling, Defensive Programming</td></tr>
            <tr><td>4</td><td>Libraries</td><td>Packages, APIs</td></tr>
            <tr><td>5</td><td>Unit Tests</td><td>Automated Testing with pytest</td></tr>
            <tr><td>6</td><td>File I/O</td><td>Reading/Writing Files, CSV/JSON</td></tr>
            <tr><td>7</td><td>Regular Expressions</td><td>Pattern Matching, Validation</td></tr>
            <tr><td>8</td><td>Object-Oriented Programming</td><td>Classes, Encapsulation</td></tr>
            <tr><td>Final</td><td>Final Project</td><td>Integration of Concepts</td></tr>
          </tbody>
        </table>
      </section>

      <section>
        <h2>Development Environment</h2>
        <p class="muted"><span class="emoji">🛠️</span>All code was developed and tested in the <strong>CS50 Duck IDE</strong>. The environment provides Python 3, CS50-specific testing tools (<code>check50</code>, <code>submit50</code>, <code>style50</code>), and Git integration for version control.</p>
      </section>

      <section>
        <h2>Learning Outcomes</h2>
        <p class="muted"><span class="emoji">🎯</span>By completing the weekly modules I gained strong fundamentals in algorithmic thinking and practical Python programming, including modular design, testing, and object-oriented principles.</p>
      </section>

      <section>
        <h2>References & Resources</h2>
        <p class="muted">Official course materials and references used:</p>
        <ul class="muted">
          <li><a href="https://cs50.harvard.edu/python/">CS50P Official Course</a></li>
          <li><a href="https://cs50.dev/">CS50 Duck IDE</a></li>
          <li><a href="https://docs.python.org/3/">Python Documentation</a></li>
        </ul>
      </section>

      <section>
        <h2>Notes</h2>
        <p class="muted">This README is intentionally formal and concise. Emojis are used sparingly to highlight actionable sections while maintaining a professional presentation suitable for an academic portfolio or GitHub profile. <span class="emoji">✅</span></p>
      </section>

      <div class="footer">
        <div>© 2025 — Course work completed using CS50 Duck IDE</div>
        <div class="muted">Please respect CS50’s academic honesty policy when referencing or reusing code.</div>
      </div>
    </main>
  </div>
</body>
</html>
