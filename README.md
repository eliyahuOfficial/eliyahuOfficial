# Eliyahu Levi

**Full-Stack & AI Engineer — I build and run generative-AI products in production.**

Not demos. Live, deployed products: multi-provider media pipelines, background job architecture, cost routing across AI vendors, and the billing and account layers around them. Based in Israel.

> **Where is the code?** My current work lives in private repositories, so it doesn't show up on this profile. The products below are live — the links are the best way to see it. The public repos here are mostly earlier learning projects.

---

## What I'm building

### [The Amazing Studio](https://theamazing.studio) · AI product-video studio
One product photo in → a finished 9:16 ad film out: AI storyboard, five animated shots, soundtrack, final render. Live commercial product with per-unit pricing, a credit system and payment-gateway checkout.

**Engineering:** Three-service architecture on Railway (web / BullMQ worker / Redis) after refactoring away from synchronous Remotion rendering inside the web process — long renders now run in the background and survive interruption. Character and world consistency maintained across the full film.

### [Felora](https://felora.app) · AI marketing-content platform for Israeli businesses
Videos, ads, product imagery and print/packaging files — generated in Hebrew, in each brand's own voice.

**Engineering:** Cost-based routing across three video providers (Runway, Kling, Seedance via fal.ai) with up to a 10x spread in per-second cost. Separate BullMQ queues with per-provider rate limiters, sized for concurrent load. Hardening: auth rate limiting, SSRF guards on user-supplied URLs, automatic credit refunds on failure, startup recovery for stuck workers.

### [The Amazing Online](https://theamazing.online) · AI UGC video studio
A short brief becomes a vertical UGC ad — script, photorealistic imagery, animated clips, natural voiceover in six languages, music and captions. Step-by-step approval before final render.

### [Atarika](https://atarika.co.il) · Digital solutions studio
Websites and landing pages, AI video production, CRM systems and automation, and campaign management for business clients. The studio behind The Amazing Studio.

---

## In development

### Jarvis Commerce OS · Autonomous e-commerce operating system
An AI-first system that runs online stores through a conversational interface (Jarvis): multi-store storefronts, AliExpress supplier API, tiered Claude agents and WhatsApp approval alerts.

### AAI · AI app builder
A Base44 / Lovable-style builder focused on the design quality of the apps it generates.

### Elara · Experimental digital entity
A persistent "digital organism" designed with long-term memory of its user, emotions and incremental language learning, rendered as a fully animated 3D scene.

---

## Engineering focus

- **Generative media pipelines** — orchestrating image, video, voice and music models into a single reliable output
- **Background job architecture** — queues, workers, rate limiting, retries, recovery from partial failure
- **AI cost control** — provider abstraction and routing so unit economics survive scale
- **Full ownership** — architecture through deployment, plus the billing, auth and account layers that make a product sellable

## Stack

- **Frontend** — React · Next.js · TypeScript · Vite · Tailwind CSS
- **Backend** — Node.js · Express · REST APIs · JWT
- **Data & Infra** — MongoDB · PostgreSQL · Prisma · Redis · BullMQ · Docker · Nginx · Railway · Cloudinary
- **AI** — OpenAI · Gemini · Claude · LangChain · RAG · embeddings & vector DBs · fal.ai · Runway · Kling · Seedance · ElevenLabs · Remotion

---

## Background

- MBA in Business Management (marketing specialization) · B.A. Business & Marketing
- Full-Stack Web Developer, HackerU — 535 hours, completed with honors
- Before engineering: founded and ran a workwear and safety-footwear import business (2009–2023)

I came to engineering from business and marketing, which is why my products tend to be aimed at a real buyer rather than at a benchmark.

---

📫 [LinkedIn](https://www.linkedin.com/in/eliyahuofficial/) · [atarika.co.il](https://atarika.co.il) · [eliyahu.levi.official@gmail.com](mailto:eliyahu.levi.official@gmail.com)
