<div align="right">
  <img src="./kudawasama_emote.png" width="120" alt="JC Logo" />
</div>

# Hola, soy José Céspedes 👋

### Arquitecto de IA · Sistemas que automatizan lo que nadie quería hacer a mano

![Banner](./kudawasama_github_profile.png)

<p align="left">
  <a href="https://github.com/kudawasama?tab=followers"><img src="https://img.shields.io/github/followers/kudawasama?style=for-the-badge&logo=github&color=c97a3c" alt="followers" /></a>
  <a href="https://github.com/kudawasama?tab=repositories"><img src="https://img.shields.io/badge/repos-públicos-2dd4bf?style=for-the-badge&logo=github" alt="repos" /></a>
  <img src="https://komarev.com/ghpvc/?username=kudawasama&color=c97a3c&style=for-the-badge&label=visitas+al+perfil" alt="profile views" />
</p>

---

Construyo **sistemas con IA** que resuelven problemas reales, no demos: agentes con memoria persistente, ruteo híbrido entre razonamiento simbólico y modelos pequeños, RPA con visión artificial, y pipelines ETL que ahorran horas de trabajo manual.

Mi tesis: **la IA no es magia, es arquitectura**. Un LLM pequeño (Qwen 0.5B) puede comportarse como un modelo PRO si le das el sistema correcto — memoria, skills, contexto dinámico, y la capacidad de *actuar* sobre el mundo real, no solo responder.

Empecé automatizando mi propio trabajo como Analista de Costos. Cada sistema que construyo parte de un problema real: facturación que tomaba 2 días ahora toma 7 minutos, registro contable que era manual ahora es un bot con OCR, y reportes mensuales que se quebraban por duplicados ahora se deduplican antes de consolidarse.

> 🏔️ *"La mejor automatización es la que nadie nota. Solo ven el resultado."*

---

## 🧠 Lo que diseño y construyo

- **Agentes con memoria tripartita** — episódica, semántica, procedural. Aprenden sin reentrenar.
- **Ruteo híbrido** — motor simbólico (rápido, sin GPU) + SLM local (Qwen/Llama vía Ollama) con fallback automático.
- **Function calling nativo** — sin OpenAI, sin APIs pagas. Skills registradas en código Python.
- **RPA con visión artificial** — Tesseract + pyautogui para automatizar sistemas sin API.
- **ETL financieros** — pipelines que ingieren Excels, deduplican, atribuyen centros de costo, generan reportes Excel.
- **Sistemas self-hosted** — WSL2 + Docker + Cloudflare Tunnel. Sin dependencia de terceros.

---

## ⭐ Proyecto Estrella: DTE Manager (Reporte Mensuales)

> **Lo que me hizo crecer.** Empezó como scripts para no perder 2 días cada mes armando el reporte. Hoy es un sistema con microservicios, bots headless, dashboard web y CLI portable. Lo que el SII no te da, lo construyes tú.

<a href="https://github.com/kudawasama/reporte_mensuales">
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=kudawasama&repo=reporte_mensuales&theme=radical&show_owner=true" alt="DTE Manager CLI" />
</a>

**¿Qué hace?**
- Ingesta documentos DTE desde i-Construye (portal de la constructora)
- Dedup antes de merge (fix que aprendí por las malas — facturas duplicadas por guías/OCs repetidas)
- Atribución automática de centros de costo (CC_OC + CC_FC)
- Reporte Excel mensual con 9 hojas (5 estándar + 4 analista)
- Dashboard web con KPIs y filtros por RUT
- CLI portable: `pip install -e . && dte-costo report MAYO 2026`
- Cron programado 9 AM: ingesta c/6h + reporte diario

**Stack:** Python · FastAPI · PostgreSQL · Docker · Playwright · pandas · openpyxl

---

## 🧠 NucleoNexus — IA local ultraligera

> **Un LLM pequeño (Qwen 0.5B) con comportamiento PRO mediante arquitectura, no por tamaño.**

<a href="https://github.com/kudawasama/NucleoNexus">
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=kudawasama&repo=NucleoNexus&theme=radical&show_owner=true" alt="NucleoNexus" />
</a>

- ✅ 3 memorias persistentes (episódica, semántica, procedural) con SQLite + TF-IDF
- ✅ Ruteo híbrido: motor simbólico + SLM con Qwen 2.5 vía Ollama
- ✅ Function calling nativo sin OpenAI — 15+ skills builtins
- ✅ ReAct + self-consistency + structured generation
- ✅ 100% local, sin GPU, ~500 MB de RAM, soporta Qwen/Llama/Phi
- ✅ Agente con paso de síntesis que redacta respuestas usando el SLM

---

## 🤖 Bot AX Contable — RPA con visión artificial

> **Automatización de registro contable en AX usando OCR y GUI dual.**

<a href="https://github.com/kudawasama/Bot_AX_Contable">
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=kudawasama&repo=Bot_AX_Contable&theme=radical&show_owner=true" alt="Bot AX Contable" />
</a>

- ✅ pyautogui + Tesseract OCR para automatizar formularios sin API
- ✅ GUI dual: tkinter (liviano) + PyQt6 (premium) con fallback automático
- ✅ Versionado semántico automático desde git
- ✅ Logger estructurado con rotación
- ✅ Tests unitarios + launchers `.bat` portables con detección de venv

---

## 💰 mi-app-utm — Finanzas personales para Chile

> **Aplicación web privada y ligera para controlar tus finanzas, hecha en Chile.**

<a href="https://github.com/kudawasama/mi-app-utm">
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=kudawasama&repo=mi-app-utm&theme=radical&show_owner=true" alt="mi-app-utm" />
</a>

🌐 [Ver demo en vivo](https://kudawasama.github.io/mi-app-utm/)

---

## 🧰 Stack & Herramientas

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" alt="FastAPI" />
  <img src="https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL" />
  <img src="https://img.shields.io/badge/SQLite-07405E?style=for-the-badge&logo=sqlite&logoColor=white" alt="SQLite" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker" />
  <img src="https://img.shields.io/badge/WSL2-4EAA25?style=for-the-badge&logo=linux&logoColor=white" alt="WSL2" />
  <img src="https://img.shields.io/badge/Ollama-000000?style=for-the-badge&logo=ollama&logoColor=white" alt="Ollama" />
  <img src="https://img.shields.io/badge/Qwen-FF6A00?style=for-the-badge&logo=alibabacloud&logoColor=white" alt="Qwen" />
  <img src="https://img.shields.io/badge/Cloudflare-F38020?style=for-the-badge&logo=cloudflare&logoColor=white" alt="Cloudflare" />
  <img src="https://img.shields.io/badge/Tesseract-4285F4?style=for-the-badge&logo=google&logoColor=white" alt="Tesseract" />
  <img src="https://img.shields.io/badge/Playwright-2EAD33?style=for-the-badge&logo=playwright&logoColor=white" alt="Playwright" />
  <img src="https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=csharp&logoColor=white" alt="C#" />
  <img src="https://img.shields.io/badge/.NET-512BD4?style=for-the-badge&logo=dotnet&logoColor=white" alt=".NET" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript" />
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git" />
</p>

---

## 📊 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=kudawasama&show_icons=true&theme=radical&hide_border=true&count_private=true&include_all_commits=true" height="170" alt="GitHub Stats" />
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=kudawasama&theme=radical&hide_border=true" height="170" alt="Streak Stats" />
</p>

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=kudawasama&layout=compact&theme=radical&hide_border=true&count_private=true&langs_count=8" height="160" alt="Top Languages" />
</p>

---

## 🌐 Encuéntrame en

<p align="center">
  <a href="https://kudawa.com"><img src="https://img.shields.io/badge/Portfolio-kudawa.com-c97a3c?style=for-the-badge&logo=google-chrome&logoColor=white" alt="Portfolio" /></a>
  <a href="mailto:jose@kudawa.com"><img src="https://img.shields.io/badge/Email-jose@kudawa.com-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
  <a href="https://github.com/kudawasama"><img src="https://img.shields.io/badge/GitHub-@kudawasama-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" /></a>
</p>

---

## 💡 Filosofía

> *"La IA no reemplaza personas. Reemplaza tareas que las personas no querían hacer."*

Si estás empezando como yo: **no esperes a saberlo todo**. Empieza con lo básico, construye algo, rómpelo, arréglalo, repite. Así es como realmente se aprende.

Cada error es una lección. Cada proyecto, una oportunidad de crecer.

---

<p align="center">
  Hecho con ❤️ y mucho ☕ en Santiago, Chile 🇨🇱<br>
  © 2026 <a href="https://kudawa.com">José Céspedes</a> · Kudawa Hub
</p>
