<!-- 🦇 THE DARK KNIGHT OF CODE — README -->

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:000000,50:1a1a1a,100:f5c518&height=200&section=header&text=Vedant%20Talekar&fontSize=60&fontColor=f5c518&fontAlignY=38&desc=aka%20thevedantt%20%E2%80%94%20Gotham's%20AI%20Engineer&descAlignY=58&descSize=18&animation=fadeIn" />
</p>

<p align="center">
  <a href="https://github.com/thevedantt">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1000&color=F5C518&center=true&vCenter=true&width=650&lines=%F0%9F%A6%87+By+day%3A+AI%2FML+Backend+Engineer+%40+Zeqo;%F0%9F%8C%83+By+night%3A+guarding+Gotham's+pipelines;%F0%9F%93%9C+Turning+30%2C000%2B+scanned+pages+into+clean+data;%F0%9F%A7%A0+LLMs+%C2%B7+OCR+%C2%B7+RAG+%C2%B7+Full-Stack" alt="Typing SVG" />
  </a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/STATUS-ON%20PATROL-f5c518?style=for-the-badge&labelColor=000000" />
  <img src="https://img.shields.io/badge/BASE-THE%20BATCAVE-f5c518?style=for-the-badge&labelColor=000000" />
  <img src="https://img.shields.io/badge/CURRENT%20MISSION-ZEQO-f5c518?style=for-the-badge&labelColor=000000" />
</p>

---

# 🦇 Hi, I'm Vedant Talekar (aka thevedantt)

🚀 **AI Engineer | Python Developer | Full-Stack Developer | AI/ML Enthusiast**

> *Gotham doesn't need another app. It needs systems that work in the dark — quietly, reliably, at scale.*

Hi there! I'm Vedant — a developer who blends code with creativity and AI with real-world utility. I build scalable web apps, smart systems, and AI-driven solutions that matter.

---

## 🌃 Origin Story — About Me

- 🛠️ I work across the stack with **Next.js**, **React**, **TypeScript**, and **Python**
- 🤖 I'm passionate about **AI & ML**, working with **TensorFlow**, **scikit-learn**, and LLMs
- 💡 I believe in building tools that are intuitive, intelligent, and impactful
- 🎯 Constantly exploring the intersection of tech and human problems — from **healthcare** to **education**
- 🦇 Currently fighting chaos in **EdTech** — turning messy exam PDFs into structured knowledge and AI-generated question papers at **Zeqo**

---

## 🏙️ Missions in Gotham — Experience

### 🦇 AI/ML Backend Engineer — **Zeqo** &nbsp;·&nbsp; *Jul 2026 – Present*

> *The Batcave's main computer. Where the real detective work happens.*

| 🗂️ Case File | 🔦 What I Built |
|---|---|
| 🧾 **AI Test Generator (CBSE Paper Setter)** | End-to-end engine that builds board-style papers the way a real paper setter does: syllabus → concept selection → marks allocation → **Blueprint Engine** (difficulty + Bloom's distribution) → generation → validation report → analytics → PDF export. |
| 🎯 **3-Tier Question Sourcing** | Each paper slot is filled by **retrieval** (real PYQ match) → **seeded generation** (real PYQ used as a style reference at the right difficulty) → **blind generation** (LLM from scratch). Deterministic fallbacks keep counts exact even when an LLM call fails. |
| 📜 **OCR & Extraction Pipeline** | Multi-stage pipeline over **663 PDFs / 30,590 pages** of JEE, NEET, MHT-CET & CBSE PYQs: digital-vs-scanned classification, **PyMuPDF** + **MinerU** block extraction, rule-based question segmentation, JSON structuring with Vision-LLM fallback, images to **Supabase** storage, structured JSONB to **PostgreSQL**. |
| 🧪 **Model Benchmarking** | Ran head-to-head pilots of MinerU, Marker, Docling, texify, GOT-OCR2.0 and Gemini vision models on real formula crops to pick the most accurate extractor per page type. |
| 🏷️ **Concept & Formula Tagging** | Mapped **~1,570 syllabus concepts across 78 chapters** (Physics/Chemistry/Maths, XI–XII) to textbook sections with a single-pass LLM prompt for under **$0.50** for the whole corpus; tagged PYQs to concept + formula schemas with Gemini, scaling to **~10k questions**. |
| 🔁 **Question Variant Generator** | Rephrases existing questions and changes the numericals, then runs a **blind solver** + verification loop (Gemini Flash generates, Gemini 2.5 Pro checks & fixes) so the new answer and the difficulty stay correct. |
| 📐 **AI Diagram Generation** | Generating physics/chemistry/maths diagrams from question text using a component-library approach. |
| 🕸️ **PYQ Corpus Scraping** | Built a human-in-the-loop scraper for 2012–2026 board & entrance PYQs, plus a PyMuPDF watermark-stripper that removes transparency-layer watermarks without touching real content. |
| 📲 **WhatsApp Report Sender** | Auto-delivers PDF reports to users over the official **Meta WhatsApp Cloud API**. |
| 🎨 **Product & UI** | Teacher-facing wizard UX for the test generator and the Zeqo app redesign (Flutter target), with click-reduction work on the Streamlit prototype. |

### 🦇 AI Engineer Intern — **FindFake Services** &nbsp;·&nbsp; *Jun 2025 – Dec 2025*

> *Early nights on patrol — learning the streets of production AI.*

- Built and shipped AI features at an early-stage startup.

---

## 🔍 Focus Areas — Current Investigations

- 💬 Real-time voice agents powered by **AI**
- 🧾 ML-backed tools like **question generators** and **recommendation systems**
- 📜 **Document AI** — OCR, layout extraction, LaTeX/formula recognition
- 🧠 **LLM pipelines** — tagging, generation, self-verification loops
- 🩺 Building health-focused AI (e.g., **diabetes prediction**, symptom analyzers)
- 🌐 Frontend frameworks with motion UI & interactive UX

---

## 📁 The Batcomputer Archives — Noteworthy Projects

| Project         | Description                                                                                                                                                     | Tech Stack               | Link |
|-----------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------|--------------------------|------|
| 📚 **ExaLearn** | A dynamic, interactive web-based learning platform built using pure JavaScript and CSS. Delivers real-time feedback, responsive UI, and gamified experiences with a lightweight, client-side architecture. | JavaScript, CSS          | [View Project](https://github.com/thevedantt/ExaLearn) |
| 🍽️ **GustoGo**  | A digital canteen management system using Flask that allows users to browse the menu, place orders, and manage their profiles in a seamless web experience.      | Flask, Python, HTML, CSS | [View Project](https://github.com/thevedantt/gustogo) |
| 🧠 **VaidAI**    | Real-time AI medical voice assistant leveraging AssemblyAI, Clerk, and NeonDB. Provides conversational diagnosis with report generation for enhanced virtual care. | Next.js, TypeScript, AssemblyAI, NeonDB | [View Project](https://github.com/thevedantt/vaidai) |
| 🎬 **CineMind**  | A movie recommendation system using hybrid ML techniques combining collaborative filtering and content-based filtering for personalized suggestions.               | Python, Scikit-learn     | [View Project](https://github.com/thevedantt/cinemind) |
| 🩸 **GlucoGuardAI** | AI-powered tool for real-time glucose and diabetes risk prediction, combining ML classification with visualizations for better patient awareness.                | Python, Pandas, Sklearn  | [View Project](https://github.com/thevedantt/glucoguardai) |
| 📊 **DigitRec**  | MNIST digit recognition model built with TensorFlow and CNN, designed to classify handwritten digits with high accuracy and interactive demo support.             | Python, TensorFlow       | [View Project](https://github.com/thevedantt/digitrec) |

---

## 🦇 The Utility Belt — Tech Toolbox

| Category       | Tools & Frameworks |
|----------------|--------------------|
| **Languages**  | Python, JavaScript, TypeScript, SQL, HTML/CSS, Dart |
| **Frontend**   | React, Next.js, Tailwind CSS, GSAP, Streamlit, Flutter |
| **Backend**    | Flask, Firebase, SQLite, Neon DB, PostgreSQL, Supabase |
| **ML/AI**      | TensorFlow, Scikit-learn, LangChain, OpenAI, Gemini, OpenRouter, Hugging Face |
| **Document AI**| PyMuPDF, MinerU, Marker, Docling, GOT-OCR2.0, PaddleOCR |
| **Others**     | Git, Vercel, PythonAnywhere, Clerk, AssemblyAI, Meta WhatsApp Cloud API |

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,js,ts,react,nextjs,tailwind,flask,postgres,supabase,firebase,tensorflow,sklearn,flutter,dart,git,vercel&theme=dark&perline=8" />
</p>

---

## 📊 Batcomputer Readout — GitHub Insights

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=thevedantt&show_icons=true&hide_border=true&bg_color=0d0d0d&title_color=f5c518&icon_color=f5c518&text_color=c9d1d9&custom_title=Batcomputer%20Stats" height="165" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=thevedantt&layout=compact&hide=jupyter%20notebook,html,css&langs_count=8&hide_border=true&bg_color=0d0d0d&title_color=f5c518&text_color=c9d1d9" height="165" />
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=thevedantt&hide_border=true&background=0D0D0D&ring=F5C518&fire=F5C518&currStreakLabel=F5C518&sideLabels=C9D1D9&currStreakNum=FFFFFF&sideNums=FFFFFF&dates=8B949E" />
</p>

---

## 🔦 Light the Signal — Reach Out

<p align="center">
  <a href="mailto:vedanttalekar1705@gmail.com"><img src="https://img.shields.io/badge/Email-vedanttalekar1705%40gmail.com-f5c518?style=for-the-badge&logo=gmail&logoColor=000000&labelColor=000000" /></a>
  <a href="https://www.linkedin.com/in/vedant-talekar-055910208/"><img src="https://img.shields.io/badge/LinkedIn-Vedant%20Talekar-f5c518?style=for-the-badge&logo=linkedin&logoColor=000000&labelColor=000000" /></a>
</p>

- 📧 **Email**: vedanttalekar1705@gmail.com  
- 💼 **LinkedIn**: [linkedin.com/in/vedant-talekar-055910208](https://www.linkedin.com/in/vedant-talekar-055910208/)

---

> 🚀 *"Tech should simplify lives, not complicate them — I build with that belief."*

<p align="center"><b>🦇 Not the hero Gotham asked for — the engineer it shipped. 🦇</b></p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:f5c518,50:1a1a1a,100:000000&height=120&section=footer" />
</p>
