### Hi, I'm Bereket (Beki) 👋

I build tools that test AI models and the data they learn from, and I build full-stack web apps that real businesses use.

I'm a 2026 Computer Science graduate from St. Mary's University in Addis Ababa, and I also hold a BSc in Biology from Addis Ababa University. I'm looking for roles in **AI evaluation, LLM testing, and full-stack web development**.

🌐 **Portfolio:** [beki-hck.github.io](https://beki-hck.github.io) · 💼 **LinkedIn:** [bereket-abebe](https://www.linkedin.com/in/bereket-abebe-a76248169)

---

### 🧪 AI evaluation projects

Each one is open source, runs on free local models through Ollama, and reports real results, including what went wrong.

| Project | What it does | A result it found |
|---|---|---|
| [**evalforge**](https://github.com/Beki-hck/evalforge) | LLM evaluation harness with 7 scorers, including unit tests and LLM-as-judge | Llama 3.2 3B and Qwen 2.5 3B both scored 91% on 45 tasks; Qwen led on math, Llama on format rules |
| [**preference-studio**](https://github.com/Beki-hck/preference-studio) | RLHF preference-labeling web app (FastAPI, React, PostgreSQL) with agreement stats built from scratch | Llama 3.2 3B flipped 45% of its verdicts when the answer order was swapped, vs 8% for Qwen 2.5 3B |
| [**amharic-llm-bench**](https://github.com/Beki-hck/amharic-llm-bench) | 113-item Amharic benchmark with chrF scoring and bootstrap confidence intervals | Gemma 3 4B answered 92% of reading questions but drifted into other scripts in 34% of its Amharic writing |
| [**rag-eval-assistant**](https://github.com/Beki-hck/rag-eval-assistant) | RAG question answering, plus the evaluation that checks it | Hybrid search found the right passage in the top 3 for 93% of 43 questions (keyword search: 84%) |
| [**label-auditor**](https://github.com/Beki-hck/label-auditor) | Finds mislabeled examples in a dataset with confident learning | 93% (iris) and 99% (digits) of its flags were real planted errors |

More: [judge-bias-lab](https://github.com/Beki-hck/judge-bias-lab) (is a small LLM a fair judge?) · [prompt-regression-ci](https://github.com/Beki-hck/prompt-regression-ci) (fails a pull request when a prompt change makes answers worse) · [notes-to-fhir](https://github.com/Beki-hck/notes-to-fhir) (clinical notes to FHIR records, scored against gold labels, synthetic data only)

### 💻 Web development

- **Baltina:** inventory and accounting app for a family business with 7 shops and 2 warehouses. Works offline, in Amharic and English, with Ethiopian dates. Built on Supabase (PostgreSQL) as a PWA. The code is private; a [video walkthrough](https://beki-hck.github.io) is on my portfolio.
- [**Askwell**](https://github.com/Beki-hck/askwell): a support assistant that answers from a business's own documents and shows its source. [Live demo](https://askwell-flax.vercel.app)
- [**Edge Ledger**](https://github.com/Beki-hck/edge-ledger): a trading journal with an AI coach that I use myself. Runs as one HTML file; nothing leaves your computer.
- [**Replay Desk**](https://github.com/Beki-hck/Replay-desk): a bar-by-bar trading replay simulator in one HTML file.

### 🛠️ Tools I use

- **AI:** LLM evaluation (LLM-as-judge, unit tests, chrF), RAG, RLHF data, Ollama, Claude API
- **Web:** JavaScript, React/TypeScript, FastAPI, PHP, HTML/CSS, Supabase/PostgreSQL, MongoDB, offline PWAs
- **Other:** Python, SQL, Docker, Git, GitHub Actions, AI-assisted development (Claude Code)
