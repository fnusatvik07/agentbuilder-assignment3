# 📣 Assignment 3 is live: Build **LaunchLens**

*(Attach `assignment3-thumbnail.png` as the post image / video thumbnail.)*

---

**You are the founding engineer of a startup.** Your mission: build **LaunchLens**, an AI agent that tells a founder whether a product is worth launching.

Here is the idea. Demand data lives on Google (what people search for, what is trending). Supply data lives on the marketplaces (what is actually selling on Amazon, at what price, with what complaints in the reviews). Nobody connects the two. **LaunchLens does**, and it answers one question: *should you launch this?*

Everything you need is on the page below. Watch the 60-second brief first. 👇

🌐 **Landing page (start here):** https://fnusatvik07.github.io/agentbuilder-assignment3/
💻 **Starter repo:** https://github.com/fnusatvik07/agentbuilder-assignment3
🎬 **60-sec brief video:** on the landing page, or the repo's Releases tab

---

## 🛠 What you will build

A command-line chat agent. A founder types a product idea, your agent researches it live and replies with a **Go / No-Go / Niche** verdict, then keeps chatting with memory.

**Your agent must:**
- Take a founder's question in a CLI chat loop
- Pull **demand** data from **SerpApi** (2+ engines: Trends, Shopping, News, Search)
- Pull **supply** data from **Oxylabs** (2+ sources: amazon_search, product, pricing, bestsellers, reviews)
- **Fuse both sides** into one combined answer (not two separate features)
- Output a clear **Go / No-Go / Niche** verdict (demand, price band, positioning)
- Remember the conversation and summarize it when it gets long

**Your LangGraph graph must contain all 5 (this is 45 of 100 marks):**
1. Graph + state (a typed `StateGraph`)
2. Routing (conditional edges by intent)
3. Fan-out (parallel nodes, then merge)
4. Agent node + tools (SerpApi & Oxylabs)
5. Short-term memory (checkpointer + summarization node)

> Stick to the concepts we have covered. Anything extra (like long-term memory) is bonus, never a substitute.

---

## 📦 What to deliver (one public GitHub repo)

- ✅ Working code that runs from your README (CLI is enough)
- ✅ README with setup + a concept map (file/function/line for each of the 5 concepts) + demo prompts
- ✅ `.env.example` (never commit real keys)
- ✅ A graph diagram
- ✅ Slides (PDF / PPT / Google Slides)
- ✅ A 2-minute screen-recorded demo video (explain it + show it running, with memory)
- ✅ `SUBMISSION.md` (copy from the template in the repo)

**How to submit:** reply on this thread with your public repo link.

---

## 🎯 How it is graded (100 marks + 10 bonus)

| Area | Marks |
|---|---|
| LangGraph mastery (all 5 concepts) | **45** |
| Data integration (SerpApi + Oxylabs, fused) | 20 |
| Code quality & scalability | 20 |
| Presentation, demo video & docs | 15 |

A missing required concept scores 0 for that row, so cover all five.

---

## ⏰ Deadline

**Saturday, 28 June 2026, 11:59 PM (EOD).**
Late: −10% per day, up to 3 days.

You may work solo or in pairs (max 2). AI assistants are allowed, but you must be able to explain every line.

Now go build something a real founder would pay for. 🚀
