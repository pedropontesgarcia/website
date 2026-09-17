+++
title = "CV"
# template = "cv.html"

[extra]
show_reading_time = false
quick_navigation_buttons = true
+++

## Education

<div class="cv-prose">
  <strong>Cornell University</strong>
  <div class="cv-degree-row">
    <span>Master of Science, Computer Science</span>
    <span>(exp) 2026–2028</span>
  </div>

  <div class="cv-degree-row">
    <span>Bachelor of Arts, Computer Science, <i>magna cum laude</i></span>
    <span>2022–2026</span>
  </div>

  <em>Advisor:</em> <a href="url">Adrian Sampson</a></br>
  <em>Research areas:</em> programming languages, compilers, systems
</div>

## Research

<div class="cv-prose">
  <p class="cv-entry-title"><strong><a href="https://github.com/cucapra/rewrite-dsl">Width-parametric bitvector rewrite DSL for pass generation and verification</a></strong></p>
  <div class="cv-entry-body">
    <p class="cv-entry-meta">Pedro Pontes García, Kevin Laeufer, Adrian Sampson</p>
    <p class="cv-entry-note"><i>Project in progress</i></p>
    <p class="cv-entry-desc">Bitvector equivalences are crucial for software and hardware verification through satisfiability modulo the theory of bitvectors (SMT-BV), as well as electronic design automation (EDA). Prior work toward bitvector reasoning is largely constrained to fixed-width and single-parameter applications, despite the pervasiveness of multi-width parametric bitvector operations in EDA and SMT-BV. We develop a domain-specific language for expressing bitvector rewrites, with the goals of automatic generation of compilation passes for MLIR-based EDA toolchains, and production of correctness certificates via SMT.</p>
  </div>
</div>

<div class="cv-prose">
  <p class="cv-entry-title"><strong><a href="petal.pdf">Understanding Accelerator Compilers via Performance Profiling</a></strong></p>
  <div class="cv-entry-body">
    <p class="cv-entry-meta">Ayaka Yorihiro, Griffin Berlstein, Pedro Pontes García, Kevin Laeufer, Adrian Sampson</p>
    <p class="cv-entry-note"><i>In Object-Oriented Programming, Systems, Languages &amp; Applications (<a href="https://conf.researchr.org/track/splash-2026/oopsla-2026">OOPSLA 2026</a>)</i></p>
    <p class="cv-entry-desc">Accelerator design languages (ADLs), high-level languages that compile to hardware units, help domain experts quickly design efficient application-specific hardware. We introduce Petal, a cycle-level profiler for ADLs that compile to the Calyx intermediate language (IL). Petal produces traces of <i>call trees</i>, and constructs an ADL-level profile. We demonstrate that Petal's cycle-level profiles can identify performance problems in existing accelerator designs and guide compiler developers toward optimizations, including a reduction by 46.9% of total cycles for a large-scale application.</p>
  </div>
</div>

## Teaching

<div class="cv-prose">

- *Fall 2026, Fall 2025:* CS 3410, Computer System Organization
- *Spring 2026:* CS 4152, Advanced Game Architecture
- *Spring 2025:* CS 3152, Introduction to Game Architecture
- *Fall 2024:* CS 3110, Functional Programming
- *Spring 2023–Spring 2024:* CS 1110, Introduction to Computing

</div>

## Industry

<div class="cv-prose">
  <p class="cv-entry-title"><strong><a href="https://github.com/cucapra/rewrite-dsl">Software Engineering Internship at Equinor</a></strong></p>
  <div class="cv-entry-body">
    <p class="cv-entry-meta">Equinor Research Center, Trondheim, Norway</p>
    <p class="cv-entry-note"><i>Summer 2024</i></p>
    <ul class="cv-entry-list">
      <li>Worked on the development of a software tool for model predictive control in offshore energy production and carbon capture.</li>
      <li>Rebuilt frontend using TypeScript, React, and D3.js, and developed comprehensive types in a previously untyped codebase.</li>
      <li>Built a functional-style Python middleware server with gRPC to connect the frontend to a legacy C++ backend.</li>
      <li>Rotated through leadership within a six-person international team.</li>
    </ul>
  </div>
</div>

## Honors

<div class="cv-prose">

- Department honors, *Cornell Computer Science Dept (2026)*
- Davis UWC Scholar, *(2022–2026)*
- Cornell Bowers TA Annual Award, *nominee (2025)*
- Cornell J.G. White Award for Excellence in Writing *(2025)*
- Norway National Young Researchers' Award, *2nd place (2022)*
- Baltic Sea Philosophy Essay Event, *bronze (2021 and 2022)*

</div>

## Other projects

<div class="cv-prose">

- *Bril Development Suite*, a set of compiler analysis and optimization passes for the Bril teaching language.
- Software lead on *Trigger Happy*, a multiplayer last-man-standing mobile card game in C++.
- Software lead on *Phytopolis*, a platforming and strategic resource management game in Java.
- *Zephyr*, a lightweight OCaml game engine with support for 2D physics.

</div>
