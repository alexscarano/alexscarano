<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://shieldcn.dev/header/graph.svg?title=Alexandre%20Scarano&subtitle=Fullstack%20developer%20%C2%B7%20.NET%2C%20Next.js%20and%20React%20Native&theme=zinc&align=center&mode=dark" />
    <img alt="Alexandre Scarano, fullstack developer" src="https://shieldcn.dev/header/graph.svg?title=Alexandre%20Scarano&subtitle=Fullstack%20developer%20%C2%B7%20.NET%2C%20Next.js%20and%20React%20Native&theme=zinc&align=center&mode=light" />
  </picture>
</p>

I build web and mobile apps. Most of my backend work is .NET, and the front end is usually Next.js or React Native. Lately I've been spending my time on web security tooling: you point a scanner at a site and it tells you what's wrong with it, in words a person can actually act on.

I finished my Systems Analysis and Development degree at FATEC - SP in 2026.

## Projects

### [HeimdallWeb](https://heimdall.warphsolutions.cloud)

A security scanner for websites. Give it a URL and it checks:

- HTTP security headers (CSP, HSTS, X-Frame-Options)
- the SSL/TLS certificate
- 25 ports that tend to be left open
- whether HTTP actually redirects to HTTPS
- what `robots.txt` gives away
- around 35 files and folders that should never be public, like `/.env` and `/.git`

Raw scanner output is hard to read, so Google Gemini turns the findings into a risk rating, a short summary and specific things to fix. The admin side has usage metrics, filterable audit logs and user management. Sessions use JWT stored in `HttpOnly` `Secure` cookies, with separate user and admin roles.

The backend is .NET 10 Minimal APIs with DDD-Light and CQRS. The front end is Next.js 15.

<p>
  <img alt=".NET 10" src="https://shieldcn.dev/badge/.NET_10.svg?variant=secondary&theme=zinc&logo=dotnet" />
  <img alt="Next.js 15" src="https://shieldcn.dev/badge/Next.js_15.svg?variant=secondary&theme=zinc&logo=nextdotjs" />
  <img alt="PostgreSQL 16" src="https://shieldcn.dev/badge/PostgreSQL_16.svg?variant=secondary&theme=zinc&logo=postgresql" />
  <img alt="TypeScript" src="https://shieldcn.dev/badge/TypeScript.svg?variant=secondary&theme=zinc&logo=typescript" />
  <img alt="Tailwind CSS" src="https://shieldcn.dev/badge/Tailwind_CSS.svg?variant=secondary&theme=zinc&logo=tailwindcss" />
  <img alt="Google Gemini" src="https://shieldcn.dev/badge/Gemini.svg?variant=secondary&theme=zinc&logo=googlegemini" />
</p>

### [QrLinkki](https://github.com/alexscarano/QrLinkki)

Short links and QR codes, with an Android app on top. You shorten a URL (custom code if you want one), generate a QR from it, and then watch the click count go up. The app scans codes with the camera and caches your links locally, so the dashboard still opens when the connection drops. Login persists through Expo SecureStore.

The API follows Clean Architecture and DDD. The app is React Native with Expo.

<p>
  <img alt=".NET 8" src="https://shieldcn.dev/badge/.NET_8.svg?variant=secondary&theme=zinc&logo=dotnet" />
  <img alt="React Native" src="https://shieldcn.dev/badge/React_Native.svg?variant=secondary&theme=zinc&logo=react" />
  <img alt="Expo" src="https://shieldcn.dev/badge/Expo.svg?variant=secondary&theme=zinc&logo=expo" />
  <img alt="TypeScript" src="https://shieldcn.dev/badge/TypeScript.svg?variant=secondary&theme=zinc&logo=typescript" />
  <img alt="SQLite" src="https://shieldcn.dev/badge/SQLite.svg?variant=secondary&theme=zinc&logo=sqlite" />
  <img alt="Docker" src="https://shieldcn.dev/badge/Docker.svg?variant=secondary&theme=zinc&logo=docker" />
</p>

### [QuizForge](https://github.com/alexscarano/QuizForge)

Write a prompt, get a quiz. You describe the topic, Gemini writes the questions, and the app grades your answers as soon as you finish. Quizzes can be saved for later or exported to PDF with iText. There's a small account area for editing your data and finding what you saved.

Built for the OOP course at FATEC - SP, with Java servlets and JSP.

<p>
  <img alt="Java" src="https://shieldcn.dev/badge/Java.svg?variant=secondary&theme=zinc&logo=openjdk" />
  <img alt="JSP and Servlets" src="https://shieldcn.dev/badge/JSP_%2B_Servlets.svg?variant=secondary&theme=zinc&logo=apachetomcat" />
  <img alt="MySQL" src="https://shieldcn.dev/badge/MySQL.svg?variant=secondary&theme=zinc&logo=mysql" />
  <img alt="iText 7" src="https://shieldcn.dev/badge/iText_7.svg?variant=secondary&theme=zinc" />
  <img alt="Google Gemini" src="https://shieldcn.dev/badge/Gemini.svg?variant=secondary&theme=zinc&logo=googlegemini" />
</p>

## Stack

What I reach for day to day.

<p>
  <img alt=".NET" src="https://shieldcn.dev/badge/.NET.svg?variant=secondary&theme=zinc&logo=dotnet" />
  <img alt="Java" src="https://shieldcn.dev/badge/Java.svg?variant=secondary&theme=zinc&logo=openjdk" />
  <img alt="TypeScript" src="https://shieldcn.dev/badge/TypeScript.svg?variant=secondary&theme=zinc&logo=typescript" />
  <img alt="JavaScript" src="https://shieldcn.dev/badge/JavaScript.svg?variant=secondary&theme=zinc&logo=javascript" />
</p>

<p>
  <img alt="Next.js" src="https://shieldcn.dev/badge/Next.js.svg?variant=secondary&theme=zinc&logo=nextdotjs" />
  <img alt="React" src="https://shieldcn.dev/badge/React.svg?variant=secondary&theme=zinc&logo=react" />
  <img alt="React Native" src="https://shieldcn.dev/badge/React_Native.svg?variant=secondary&theme=zinc&logo=expo" />
  <img alt="Tailwind CSS" src="https://shieldcn.dev/badge/Tailwind_CSS.svg?variant=secondary&theme=zinc&logo=tailwindcss" />
</p>

<p>
  <img alt="PostgreSQL" src="https://shieldcn.dev/badge/PostgreSQL.svg?variant=secondary&theme=zinc&logo=postgresql" />
  <img alt="MySQL" src="https://shieldcn.dev/badge/MySQL.svg?variant=secondary&theme=zinc&logo=mysql" />
  <img alt="SQLite" src="https://shieldcn.dev/badge/SQLite.svg?variant=secondary&theme=zinc&logo=sqlite" />
  <img alt="Docker" src="https://shieldcn.dev/badge/Docker.svg?variant=secondary&theme=zinc&logo=docker" />
  <img alt="Git" src="https://shieldcn.dev/badge/Git.svg?variant=secondary&theme=zinc&logo=git" />
</p>

## Where to find me

<p>
  <a href="https://portfolio.warphsolutions.cloud/"><img alt="Portfolio" src="https://shieldcn.dev/badge/portfolio.warphsolutions.cloud.svg?variant=secondary&theme=zinc&logo=googlechrome" /></a>
  <a href="https://www.linkedin.com/in/alexandre-scarano/"><img alt="LinkedIn" src="https://shieldcn.dev/badge/LinkedIn.svg?variant=secondary&theme=zinc" /></a>
  <a href="https://heimdall.warphsolutions.cloud"><img alt="HeimdallWeb" src="https://shieldcn.dev/badge/heimdall.warphsolutions.cloud.svg?variant=secondary&theme=zinc" /></a>
</p>
