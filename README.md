# TG Pranav Hathwar

**Full Stack Developer** · MCA @ RV College of Engineering, Bengaluru

Python and FastAPI backends on SQL I model deliberately, containerised and deployed — with AI models chosen for the problem, not the hype. I build for real businesses: the systems below run a working restaurant during service.

📍 Bengaluru, India &nbsp;·&nbsp; ✉️ [pranav4hathwar@gmail.com](mailto:pranav4hathwar@gmail.com) &nbsp;·&nbsp; 💼 [LinkedIn](https://www.linkedin.com/in/pranav-hathwar)

---

## What I want to be interviewed on

| | |
|---|---|
| **Python** | My primary language — backend services, data pipelines, automation, and the glue around AI models. Typed with Pydantic, tested, containerised. |
| **FastAPI** | APIs designed as a contract first: typed request/response models, dependency-injected auth, explicit status codes, generated OpenAPI docs. |
| **SQL & data modelling** | Schema before endpoint. Normalised design, deliberate indexes, constraints that enforce invariants in the database rather than in application code. |
| **Cloud & deployment** | Everything here is containerised and deployed, not left on localhost. Docker Compose, nginx reverse proxy, GitHub Actions CI/CD with automated security scanning. |
| **Computer networks** | TCP/IP, DNS, the TLS handshake, HTTP semantics, CORS, caching, and where latency actually comes from — the difference between guessing at a 502 and diagnosing one. |

Everything else — MongoDB, Node, Express, React, TypeScript — I picked up because a project called for it. Productive in all of them; they're just not where my depth sits.

---

## AI, in practice

I pick the kind of model the problem calls for instead of routing everything through one chat API.

| Model family | Used for | Code |
|---|---|---|
| **Large language models** — Gemini, LLM APIs | Audit-chat endpoint that lets a reviewer interrogate a risk assessment | [VendorLens](https://github.com/Pranav-Hathwar/Socgen_Packetloss_hackathon) |
| **Embedding & retrieval** — vector embeddings, RAG | Grounding answers in real documents rather than letting a model improvise | — |
| **Computer vision** — MediaPipe landmark networks, OpenCV | Real-time gesture recognition from 21 tracked hand landmarks | [Hand_Signal](https://github.com/Pranav-Hathwar/Hand_Signal) |

---

## Shipped

| Project | What it does | Stack | Live |
|---|---|---|---|
| **Hotel Management System** | Staff attendance and operations platform for Mint Masala — RBAC, real-time tracking, automated reporting. Cut manual attendance errors 40%, raised throughput 50%. | MongoDB · Express · React · Node | [hms.mintmasala.in](https://hms.mintmasala.in/login) |
| **[MenuMind Pro](https://github.com/Pranav-Hathwar/Menu_Engineering)** | Menu engineering SaaS. Classifies POS sales into a BCG matrix (Stars / Plowhorses / Puzzles / Dogs) and simulates ±20% price moves against demand elasticity. | FastAPI · Python · PostgreSQL · Pandas · Docker | — |
| **Kitchenflow** | Restaurant inventory with a 12-stage approval workflow across 3 roles, chef shortage request → owner approval → automatic stock write-back. 308 tests, 90% backend coverage, 38 vulnerabilities closed via automated scanning. | FastAPI · PostgreSQL · Docker · GitHub Actions | — |
| **[VendorLens](https://github.com/Pranav-Hathwar/Socgen_Packetloss_hackathon)** | Third-party risk platform with a Gemini-backed audit chat. Canonical Pydantic models mirrored into the TypeScript front end so schemas can't drift. | FastAPI · Python · Gemini · Next.js | [Live](https://socgen-packetloss-hackathon.vercel.app) |
| **[Wi-Fi Placement Optimizer](https://github.com/Pranav-Hathwar/CN-and-Math-EL_pranav)** | Finds the optimal indoor router position by modelling RF propagation — log-distance path loss, ray-cast wall attenuation, RSSI heatmaps. | Python · signal modelling | — |
| **[Chemical Virtual Lab](https://github.com/Pranav-Hathwar/chemical-vlab)** | Virtual chemistry lab for web and Android, built with a team for a professor in the chemical engineering dept. JWT + Google Sign-In, AES-256 encrypted answers, 100+ student sessions. | Flutter · Node · Express · PostgreSQL | — |

### Client work

**[Mint Masala](https://mintmasala.in/)** — digital restaurant menu and the management system above, delivered end to end.
**[Munagru Homestays](https://home-stay-two.vercel.app)** — full site for a homestay business.
**[Swaathi](https://swaathi-portfolio-six.vercel.app)** — portfolio for a makeup artist (in progress).

---

## Toolbox

`Python` `TypeScript` `JavaScript` `SQL` · `FastAPI` `Pydantic` `Pandas` `SQLAlchemy` · `React` `Next.js` `Node.js` `Express` · `PostgreSQL` `MongoDB` · `Docker` `Docker Compose` `GitHub Actions` `nginx` `Vercel` · `Git`

---

<sub>Open to full-stack and backend roles, internships, and freelance work — particularly anything with real operational weight behind it.</sub>
