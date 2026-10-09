# Hi, I'm Gökhan Kara 👋

**Backend developer · Java & Spring Boot**

I'm a Software Engineering student at Çankaya University. I build scalable backend applications with Java and Spring Boot and am learning AI technologies.

[Website](https://gokhankaradev.com/en) · [LinkedIn](https://www.linkedin.com/in/g%C3%B6khan-kara) · [Email](mailto:gokhankara.swe@gmail.com) · [CV (PDF)](https://gokhankaradev.com/cv.pdf)

<p>
  <img src="https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white" alt="Java" />
  <img src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white" alt="Spring Boot" />
  <img src="https://img.shields.io/badge/Spring_Security-6DB33F?style=flat-square&logo=springsecurity&logoColor=white" alt="Spring Security" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL" />
  <img src="https://img.shields.io/badge/JUnit_5-25A162?style=flat-square&logo=junit5&logoColor=white" alt="JUnit 5" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker" />
</p>

## Projects

### [CTO Project Tracker](https://github.com/gokhankaraa/cto-project-tracker-backend)
Backend where project managers submit weekly status reports and the CTO monitors all projects from a single dashboard. Built during my internship at Kolaysoft (June – July 2026).

- **17 REST endpoints** and **47 automated tests**
- Validates business rules and returns a consistent error format across all endpoints
- Aggregates project data for the CTO's portfolio dashboard
- Swagger UI for trying the API in the browser; starts with a single command via a multi-stage Docker build

`Java 21` `Spring Boot` `Spring Data JPA` `Bean Validation` `JUnit` `Mockito` `MockMvc` `Docker`

### [Content Scheduler](https://github.com/gokhankaraa/content-scheduler)
Full-stack app that schedules video posts for YouTube, Instagram and TikTok.

- Every minute, the backend checks for posts that are due and publishes them through each platform's official API
- Failed posts are retried at increasing intervals, up to 3 attempts

`Java 17` `Spring Boot` `Spring Security` `PostgreSQL` `Flyway` `React` `Vite` `Docker`

### [gokhankaradev.com](https://gokhankaradev.com/en)
My personal website, with an AI assistant that answers visitors' questions about my experience and projects.

- The assistant answers only from the site's own content and says so when it doesn't know
- Per-IP rate limiting, Turkish and English versions
- Unit and end-to-end tests run in GitHub Actions on every push

`TypeScript` `Next.js` `Tailwind CSS` `Vercel AI SDK` `Google Gemini` `Upstash Redis` `Vitest` `Playwright`

## Experience

**Backend Developer Intern** · Kolaysoft A.Ş. · *June 2026 – July 2026*
Built the backend of the CTO Project Tracker and delivered it as a working MVP within a task-based internship program.

## Tech stack

| | |
|---|---|
| **Backend** | Spring Boot, Spring Data JPA (Hibernate), Spring Security, Bean Validation, Lombok |
| **Testing** | JUnit, Mockito, MockMvc |
| **Languages** | Java, Python, C++, C |
| **Databases** | PostgreSQL, SQL |
| **Frontend** | React, Next.js, TypeScript |
| **Tools** | Git, Docker, Maven, Swagger / OpenAPI |

## Education

**Çankaya University** · Software Engineering · *2023 – present*
