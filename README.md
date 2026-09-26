<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/banner-dark.png">
  <img alt="Saad Ahmed. Product Engineer / Software Engineer. B2B SaaS and AI systems, TypeScript, Node, Python." src="assets/banner-light.png">
</picture>

<p align="center">
  <img alt="Product engineer at Teczon. B2B software with AI systems at its core. TypeScript and Node, Python for the agent layer. Based in Lahore, UTC+5." src="https://readme-typing-svg.demolab.com?font=Inter&weight=500&size=20&duration=3000&pause=1400&color=3EA3A6&center=true&vCenter=true&width=640&lines=Product+engineer+at+Teczon;B2B+software+with+AI+systems+at+its+core;TypeScript+and+Node%2C+Python+for+the+agent+layer;Based+in+Lahore+%28UTC%2B5%29">
</p>

<p align="center">
  <a href="https://saad.run"><img alt="Website" src="https://img.shields.io/badge/saad.run-1f6f8a?style=for-the-badge&logo=googlechrome&logoColor=white"></a>
  <a href="https://www.linkedin.com/in/saadsolves"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-saadsolves-2b7f86?style=for-the-badge&logo=linkedin&logoColor=white"></a>
  <a href="mailto:iamsaad640@gmail.com"><img alt="Email" src="https://img.shields.io/badge/Email-iamsaad640%40gmail.com-3ea3a6?style=for-the-badge&logo=gmail&logoColor=white"></a>
</p>

## 👋 About

I'm a product engineer at Teczon. I build B2B software with AI systems at its core, and each product I've worked on has been my responsibility from the requirement meetings and the first commit to keeping it running after launch.

The code for the work below lives in private company repositories.

## 🧪 Recent work

<table>
  <tr>
    <td width="30%" valign="top">🧫 <b>Lab automation for a cell-culture robot</b></td>
    <td valign="top">A scientist writes instructions for the next experiment in plain language, and the model plans the experiment and instructs the robot's incubators, microscopes and cell analyzers to perform it, with a person approving every hardware step before anything moves. Scientists use it from Slack and Microsoft Teams. It passed the full security assessment of a pharmaceutical customer valued at about $90B.</td>
  </tr>
  <tr>
    <td valign="top">🔐 <b>Business-mentor agent</b></td>
    <td valign="top">Advises each user from their own spreadsheets and financial documents. Personal details are stripped and sensitive values masked before anything reaches the model provider, including calls made from tools, and the masked values are restored in the answer.</td>
  </tr>
  <tr>
    <td valign="top">📄 <b>Document assistant for a public-sector organisation</b></td>
    <td valign="top">Citizens upload a document and ask questions about it. It runs on the organisation's own GPUs with an 8B Polish-language open-source model, because the data could not leave the country, and I engineered the layer that detects and fixes the model's broken tool calls.</td>
  </tr>
</table>

<details open>
<summary><b>How the lab agent fits together</b></summary>
<br>

```mermaid
flowchart LR
    S(["Scientist in Slack or Teams"]) -- "instructions for the next experiment" --> P["Model plans the experiment"]
    P --> A{"Person approves each hardware step"}
    A -- approved --> H["Incubators, microscopes, cell analyzers"]
    H --> T["Experiment tracking"]
    T -- "pick up exactly where it stopped" --> S
    A -.-> L[("Audit trail of every change")]

    classDef teal fill:#1f6f8a,stroke:#48b1b8,color:#ffffff
    classDef soft fill:#3ea3a6,stroke:#7fc4bd,color:#ffffff
    class S,H teal
    class P,A,T,L soft
```

</details>

## 🧰 Stack

<p>
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://skillicons.dev/icons?i=ts,js,nodejs,nestjs,express,react,nextjs,tailwind,py,fastapi,postgres,prisma,docker,gcp,aws,git&perline=16&theme=dark">
    <img alt="TypeScript, JavaScript, Node.js, NestJS, Express, React, Next.js, Tailwind CSS, Python, FastAPI, PostgreSQL, Prisma, Docker, Google Cloud, AWS, Git" src="https://skillicons.dev/icons?i=ts,js,nodejs,nestjs,express,react,nextjs,tailwind,py,fastapi,postgres,prisma,docker,gcp,aws,git&perline=16&theme=light">
  </picture>
</p>

<p>
  <img alt="LangGraph" src="https://img.shields.io/badge/LangGraph-1f6f8a?style=flat-square&logo=langchain&logoColor=white">
  <img alt="LangChain" src="https://img.shields.io/badge/LangChain-2b7f86?style=flat-square&logo=langchain&logoColor=white">
  <img alt="OpenAI API" src="https://img.shields.io/badge/OpenAI_API-3ea3a6?style=flat-square">
  <img alt="Gemini API" src="https://img.shields.io/badge/Gemini_API-48b1b8?style=flat-square&logo=googlegemini&logoColor=white">
  <img alt="pgvector" src="https://img.shields.io/badge/pgvector-2295b6?style=flat-square&logo=postgresql&logoColor=white">
  <img alt="vLLM" src="https://img.shields.io/badge/vLLM-1f6f8a?style=flat-square">
</p>

## 🕹️ Arcade

> [!NOTE]
> These games play on my contribution graph and redraw every night. Most of the activity on it is in private company repositories.

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/iamsaad640/iamsaad640/output/snake-dark.svg">
  <img alt="Snake eating the contribution graph" src="https://raw.githubusercontent.com/iamsaad640/iamsaad640/output/snake.svg">
</picture>

<details>
<summary><b>Two more games on the same graph</b></summary>
<br>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/iamsaad640/iamsaad640/output/pacman-contribution-graph-dark.svg">
  <img alt="Pac-Man eating the contribution graph" src="https://raw.githubusercontent.com/iamsaad640/iamsaad640/output/pacman-contribution-graph.svg">
</picture>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/iamsaad640/iamsaad640/output/breakout-contribution-graph-dark.svg">
  <img alt="Breakout ball clearing the contribution graph" src="https://raw.githubusercontent.com/iamsaad640/iamsaad640/output/breakout-contribution-graph.svg">
</picture>

</details>

<img alt="" src="assets/footer-wave.svg" width="100%">
