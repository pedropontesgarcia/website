+++
title = "CV"
# template = "cv.html"

[extra]
show_reading_time = false
quick_navigation_buttons = true
+++

## Education

{{ edu_entry(school="Cornell University", degrees=["Master of Science, Computer Science", "Bachelor of Arts, Computer Science, *magna cum laude*"], years=["(exp) 2026–2028", "2022–2026"], advisor="Adrian Sampson", advisor_url="url", research_areas="programming languages, compilers, systems") }}

## Research

{{ entry(title="Width-Parametric Bitvector Rewrite DSL for Application and Verification", url="https://github.com/cucapra/rewrite-dsl", byline="Pedro Pontes García, Kevin Laeufer, Adrian Sampson", note="*In progress*", description="Bitvector equivalences are crucial for software and hardware verification through satisfiability modulo the theory of bitvectors (SMT-BV), as well as electronic design automation (EDA). Prior work toward bitvector reasoning is largely constrained to fixed-width and single-parameter applications, despite the pervasiveness of multi-width parametric bitvector operations in EDA and SMT-BV. We develop a domain-specific language for expressing bitvector rewrites, with the goals of automatic generation of compilation passes for MLIR-based EDA toolchains, and production of correctness certificates via SMT.") }}

{{ entry(title="Understanding Accelerator Compilers via Performance Profiling", url="petal.pdf", byline="Ayaka Yorihiro, Griffin Berlstein, Pedro Pontes García, Kevin Laeufer, Adrian Sampson", note="In Object-Oriented Programming, Systems, Languages & Applications ([OOPSLA 2026](https://conf.researchr.org/track/splash-2026/oopsla-2026))", description="Accelerator design languages (ADLs), high-level languages that compile to hardware units, help domain experts quickly design efficient application-specific hardware. We introduce Petal, a cycle-level profiler for ADLs that compile to the Calyx intermediate language (IL). Petal produces traces of *call trees*, and constructs an ADL-level profile. We demonstrate that Petal's cycle-level profiles can identify performance problems in existing accelerator designs and guide compiler developers toward optimizations, including a reduction by 46.9% of total cycles for a large-scale application.") }}

## Teaching

- *Fall 2026, Fall 2025:* CS 3410, Computer System Organization
- *Spring 2026:* CS 4152, Advanced Game Architecture
- *Spring 2025:* CS 3152, Introduction to Game Architecture
- *Fall 2024:* CS 3110, Functional Programming
- *Spring 2023–Spring 2024:* CS 1110, Introduction to Computing

## Industry

{{ entry(title="Software Engineering Internship at Equinor", url="https://github.com/cucapra/rewrite-dsl", byline="Equinor Research Center, Trondheim, Norway", note="Summer 2024", bullets=["Worked on the development of a software tool for model predictive control in offshore energy production and carbon capture.", "Rebuilt frontend using TypeScript, React, and D3.js, and developed comprehensive types in a previously untyped codebase.", "Built a functional-style Python middleware server with gRPC to connect the frontend to a legacy C++ backend.", "Rotated through leadership within a six-person international team."]) }}

## Honors

- Department honors, *Cornell Computer Science Dept (2026)*
- Davis UWC Scholar, *(2022–2026)*
- Cornell Bowers TA Annual Award, *nominee (2025)*
- Cornell J.G. White Award for Excellence in Writing *(2025)*
- Norway National Young Researchers' Award, *2nd place (2022)*
- Baltic Sea Philosophy Essay Event, *bronze (2021 and 2022)*

## Other projects

- *Bril Development Suite*, a set of compiler analysis and optimization passes for the Bril teaching language.
- Software lead on *Trigger Happy*, a multiplayer last-man-standing mobile card game in C++.
- Software lead on *Phytopolis*, a platforming and strategic resource management game in Java.
- *Zephyr*, a lightweight OCaml game engine with support for 2D physics.