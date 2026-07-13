<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:000000,50:003B00,100:00FF41&height=180&section=header&text=VIJAY%20VS&fontSize=60&fontColor=00FF41&fontAlignY=32&animation=fadeIn&desc=%3E%20backend%20%C2%B7%20retrieval%20%C2%B7%20distributed%20systems&descAlignY=55&descSize=16&descColor=39d353" width="100%"/>

```
╻ ╻ ╻ ┏┓ ┏━┓ ╻ ╻   ╻ ╻ ┏━┓
┃┏┛ ┃ ┃┃ ┣━┫ ┗┳┛   ┃┏┛ ┗━┓
┗┛  ╹ ┗┛ ╹ ╹  ╹    ┗┛  ┗━┛
```

<img src="https://raw.githubusercontent.com/Anmol-Baranwal/Cool-GIFs-For-GitHub/main/assets/Matrix.gif" width="100%" height="4"/>

</div>

<div align="center">

```bash
root@vijay:~$ sudo ./boot.sh --verbose

[ OK ]  wake up, neo ......................... done
[ OK ]  loading identity module .............. done
[ OK ]  mounting /dev/curiosity .............. done
[ OK ]  starting backend daemons ............. done
[ OK ]  spawning retrieval pipeline .......... done
[ OK ]  injecting caffeine into bloodstream .. done
[WARN]  sleep schedule ...................... not found

> user      : Vijay
> role      : AI Engineer Intern @ Tecdia
> stack     : backend · retrieval · distributed systems
> uptime    : always shipping, occasionally sleeping
> matrix    : there is no spoon. only edge cases.
> _
```

</div>

<div align="center">

[![Typing SVG](https://readme-typing-svg.demolab.com/?font=Fira+Code&weight=500&size=20&duration=3000&pause=900&color=00FF41&center=true&vCenter=true&width=650&lines=%3E+building+things+that+scale;%3E+RAG+pipelines+%7C+backend+APIs+%7C+computer+vision;%3E+the+tools+change.+curiosity+doesn't.)](https://git.io/typing-svg)

<br>

[![Resume](https://img.shields.io/badge/%F0%9F%93%84_RESUME-0D1117?style=for-the-badge&labelColor=000000&color=00FF41)](https://drive.google.com/file/d/1cTLbskZDVTtZIVK_c6CGWRfneKLqH_Je/view?usp=drive_link)
[![LinkedIn](https://img.shields.io/badge/LINKEDIN-0D1117?style=for-the-badge&logo=linkedin&logoColor=00FF41&labelColor=000000)](https://linkedin.com/in/vijay-vs-103389271)
[![Email](https://img.shields.io/badge/EMAIL-0D1117?style=for-the-badge&logo=gmail&logoColor=00FF41&labelColor=000000)](mailto:vijay080504@gmail.com)

</div>

<br>

<div align="center">

> ` I build. I break things. I trace the stack. I build again. `
>
> ` backend logic by day, retrieval pipelines by night, `
> ` computer vision when the problem gets interesting. `
>
> **`< stay curious, ship relentlessly />`**

</div>

<img src="https://raw.githubusercontent.com/Anmol-Baranwal/Cool-GIFs-For-GitHub/main/assets/Matrix.gif" width="100%" height="3"/>

## `~/whoami $ cat roles.log`

```diff
+ AI Engineer Intern       @ Tecdia         — Apr 2026 – Present
+ Software Engineer Intern @ Globally Gi    — Jan 2026 – Mar 2026
! currently                                 — deep in distributed systems & DB internals
```

<img src="https://raw.githubusercontent.com/Anmol-Baranwal/Cool-GIFs-For-GitHub/main/assets/Matrix.gif" width="100%" height="3"/>

## `~/whoami $ ls -la stack/`

<div align="center">

[![My Skills](https://skillicons.dev/icons?i=python,java,cpp,c,js,ts,react,pytorch,tensorflow,flask,fastapi,docker,gcp,git,linux,mongodb,postgresql,redis&theme=dark&perline=9)](https://skillicons.dev)

</div>

<img src="https://raw.githubusercontent.com/Anmol-Baranwal/Cool-GIFs-For-GitHub/main/assets/Matrix.gif" width="100%" height="3"/>

## `~/whoami $ cat interests.md`

### `>` How I think about retrieval

> A reference architecture I use as my mental model for RAG systems — the general
> shape most retrieval pipelines converge on, regardless of the specific stack.

```mermaid
%%{init: {'theme':'dark', 'themeVariables': {'primaryColor':'#0D1117','primaryTextColor':'#00FF41','primaryBorderColor':'#00FF41','lineColor':'#39d353','secondaryColor':'#003B00','tertiaryColor':'#0D1117','fontFamily':'Fira Code'}}}%%
flowchart LR
    A["👤 Query"] --> B["API<br/>Gateway"]
    B --> C["Embedding<br/>Model"]
    C --> D[("Vector<br/>Store")]
    D -->|"top-k chunks"| E["Context<br/>Builder"]
    E --> F["LLM"]
    F --> G["✅ Grounded<br/>Answer"]
    G -.->|"cite sources"| A

    H[/"📄 Corpus"/] --> I["Chunker +<br/>Embedder"]
    I --> D

    style A fill:#0D1117,stroke:#00FF41,color:#00FF41
    style D fill:#003B00,stroke:#00FF41,color:#00FF41
    style F fill:#003B00,stroke:#00FF41,color:#00FF41
    style G fill:#0D1117,stroke:#39d353,color:#39d353
```

<img src="https://raw.githubusercontent.com/Anmol-Baranwal/Cool-GIFs-For-GitHub/main/assets/Matrix.gif" width="100%" height="3"/>

## `~/whoami $ git log --projects`

### `[01]` [TagVault](https://github.com/Vijayxx/Message-Tagging) — `TypeScript` `Node.js` `MongoDB`

> Secure message ingestion with HMAC + OTP auth, and a tag-indexed dashboard for sub-second retrieval.

```mermaid
%%{init: {'theme':'dark', 'themeVariables': {'primaryColor':'#0D1117','primaryTextColor':'#00FF41','primaryBorderColor':'#00FF41','lineColor':'#39d353','fontFamily':'Fira Code'}}}%%
sequenceDiagram
    autonumber
    participant W as 📱 Client
    participant A as 🔐 HMAC Verify
    participant O as 🔑 OTP Auth
    participant S as ⚙️ Express API
    participant D as 🗄️ MongoDB
    participant U as 📊 Dashboard

    W->>A: inbound message + signature
    A->>A: validate HMAC digest
    A-->>W: ❌ reject if tampered
    A->>O: forward verified payload
    O->>S: authorized session
    S->>S: tag extraction
    S->>D: store + index by tag
    U->>D: query by tag
    D-->>U: results in < 1s ⚡
```

---

### `[02]` [WhatsApp Calendar Agent](https://github.com/Vijayxx/CalendarAgent) — `Flask` `Twilio` `Gemini`

> NLP-driven assistant that parses plain-text messages into calendar events — no manual scheduling.

```mermaid
%%{init: {'theme':'dark', 'themeVariables': {'primaryColor':'#0D1117','primaryTextColor':'#00FF41','primaryBorderColor':'#00FF41','lineColor':'#39d353','fontFamily':'Fira Code'}}}%%
stateDiagram-v2
    [*] --> Received: 💬 "lunch w/ sam friday 1pm"
    Received --> Parsing: Twilio webhook → Flask
    Parsing --> Extracted: Gemini NLP
    Extracted --> Validating: {title, time, attendees}
    Validating --> Clarify: ⚠️ ambiguous date
    Clarify --> Parsing: user replies
    Validating --> Scheduled: ✅ Google Calendar API
    Scheduled --> [*]: 📅 event created
```

---



<img src="https://raw.githubusercontent.com/Anmol-Baranwal/Cool-GIFs-For-GitHub/main/assets/Matrix.gif" width="100%" height="3"/>

## `~/whoami $ ./run_snake.sh   # eating the contribution grid`

<div align="center">
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Vijayxx/Vijayxx/output/snake-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Vijayxx/Vijayxx/output/snake.svg">
  <img alt="snake eating contribution graph" src="https://raw.githubusercontent.com/Vijayxx/Vijayxx/output/snake.svg">
</picture>
</div>

<img src="https://raw.githubusercontent.com/Anmol-Baranwal/Cool-GIFs-For-GitHub/main/assets/Matrix.gif" width="100%" height="3"/>

## `~/whoami $ top -stats`

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=Vijayxx&show_icons=true&hide_border=true&count_private=true&bg_color=0D1117&title_color=00FF41&icon_color=00FF41&text_color=39d353&border_radius=8" width="49%">
<img src="https://github-readme-streak-stats.herokuapp.com/?user=Vijayxx&hide_border=true&background=0D1117&stroke=00FF41&ring=00FF41&fire=39d353&currStreakLabel=00FF41&sideLabels=39d353&dates=39d353&sideNums=00FF41&currStreakNum=00FF41&border_radius=8" width="49%">

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Vijayxx&layout=compact&hide_border=true&bg_color=0D1117&title_color=00FF41&text_color=39d353&border_radius=8" width="45%">

<br><br>

<img src="https://github-profile-trophy.vercel.app/?username=Vijayxx&theme=matrix&no-frame=true&no-bg=true&row=1&column=7&margin-w=6" width="95%">

</div>

<img src="https://raw.githubusercontent.com/Anmol-Baranwal/Cool-GIFs-For-GitHub/main/assets/Matrix.gif" width="100%" height="3"/>

## `~/whoami $ ping --connect`

<div align="center">

[![Resume](https://img.shields.io/badge/%F0%9F%93%84_RESUME-0D1117?style=for-the-badge&labelColor=000000&color=00FF41)](https://drive.google.com/file/d/1cTLbskZDVTtZIVK_c6CGWRfneKLqH_Je/view?usp=drive_link)
[![LinkedIn](https://img.shields.io/badge/LINKEDIN-0D1117?style=for-the-badge&logo=linkedin&logoColor=00FF41&labelColor=000000)](https://linkedin.com/in/vijay-vs-103389271)
[![Email](https://img.shields.io/badge/EMAIL-0D1117?style=for-the-badge&logo=gmail&logoColor=00FF41&labelColor=000000)](mailto:vijay080504@gmail.com)
[![GitHub](https://img.shields.io/badge/GITHUB-0D1117?style=for-the-badge&logo=github&logoColor=00FF41&labelColor=000000)](https://github.com/Vijayxx)

<br>

![Profile Views](https://komarev.com/ghpvc/?username=Vijayxx&color=00FF41&style=for-the-badge&label=JACKED+IN)

</div>

<div align="center">

```
[ session closed ] — follow the white rabbit. keep building. > _
```

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:00FF41,50:003B00,100:000000&height=120&section=footer" width="100%"/>

</div>
