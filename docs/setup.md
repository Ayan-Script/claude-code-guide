# ⚙️ Setup Guide for Claude Code

## 🚀 Installation

Install Claude Code using:

```bash
npm install -g @anthropic-ai/claude-code
```

---

## ▶️ Start Claude Code

```bash
claude
```

---

## 🧩 Create Your First Subagent

Run:

```bash
/agents
```

Follow the steps:

* Choose **Create new agent**
* Select **Personal**
* Describe your agent

Example:

```
A code reviewer that checks for performance, readability, and best practices
```

---

## ⚡ Run a Subagent

Example usage:

```
Use the code-reviewer agent to analyze this project
```

---

## 🛠 CLI Alternative

```bash
claude --agents '{
  "code-reviewer": {
    "description": "Expert code reviewer",
    "prompt": "You review code for quality and security"
  }
}'
```

---

## ✅ You're Ready!

Now you can:

* Create AI agents
* Automate coding workflows
* Build intelligent dev systems
