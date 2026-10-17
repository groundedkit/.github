<h1>
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://groundedkit.github.io/brand/groundedkit-wordmark-dark.png">
    <img alt="groundedkit" src="https://groundedkit.github.io/brand/groundedkit-wordmark-light.png" height="40">
  </picture>
</h1>

**Grounded, production-ready starter kits for Java developers.**

Each kit is a complete, tested application you can clone, run in minutes, and build your own product on.

## Projects

### [<picture><source media="(prefers-color-scheme: dark)" srcset="https://groundedkit.github.io/brand/docbound-wordmark-dark.png"><img alt="Docbound" src="https://groundedkit.github.io/brand/docbound-wordmark-light.png" height="28"></picture>](https://github.com/groundedkit/docbound)

A production-ready RAG ("chat with your documents") starter for Spring Boot. Answers stream in, cite the exact passages they came from, and say "not found" instead of guessing. It runs on your machine with [Ollama](https://ollama.com): no API keys, and your documents never leave it.

- **Cited, grounded answers:** every claim links to its source passage
- **Measured retrieval:** structure-aware chunking, tuned with an included evaluation harness
- **A complete app:** Spring Boot 4.1 + Spring AI 2.0, React UI, PostgreSQL + pgvector, tests, CI, and one-command Docker setup

```bash
git clone https://github.com/groundedkit/docbound.git
cd docbound
docker compose up --build
```

Full setup for macOS, Windows and Linux is in the [README](https://github.com/groundedkit/docbound#quick-start). Licensed under Apache 2.0.

Bug reports, wrong answers and feature ideas are all welcome in the [issues](https://github.com/groundedkit/docbound/issues).

## Products

### [<picture><source media="(prefers-color-scheme: dark)" srcset="https://groundedkit.github.io/brand/edify-wordmark-dark.png"><img alt="Edify" src="https://groundedkit.github.io/brand/edify-wordmark-light.png" height="28"></picture>](https://edify.adityasrivastavaa.me)

AI tutoring that grades every step. A student uploads their school syllabus and Edify builds a course grounded in it, generates fresh exams on every attempt, grades each answer step by step, and keeps a live skill map for the student and their parents.

- **Grounded in the student's own material:** courses, lessons and questions come from their syllabus or a curated textbook, and every question shows the passage it came from
- **Step-level grading:** partial credit and diagnosis tags per step, not just right or wrong
- **Parents in the loop:** progress, weekly insights, alerts when an exam is graded, and assigned tests
- **Built with:** Next.js, FastAPI, Celery, PostgreSQL + pgvector, Cloudflare Workers AI and Groq

Try it at [edify.adityasrivastavaa.me](https://edify.adityasrivastavaa.me). The source is private.

## Links

- Website: [groundedkit.github.io](https://groundedkit.github.io)
- Edify: [edify.adityasrivastavaa.me](https://edify.adityasrivastavaa.me)
- Issues and questions: [open an issue on Docbound](https://github.com/groundedkit/docbound/issues)
