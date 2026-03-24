<p align="center">
  <img src="assets/banner.png" width="100%" />
</p>

# 🤖 Claude Code Guide

A complete beginner-to-advanced guide to using **Claude Code**, including subagents, workflows, and real-world examples.

---

## 🚀 What is Claude Code?

Claude Code is an AI-powered coding assistant that allows you to:

* Create **custom AI subagents**
* Automate development workflows
* Analyze and modify code intelligently
* Run parallel AI tasks

---

## 🧩 Key Features

* 🔹 Built-in agents (Explore, Plan, General-purpose)
* 🔹 Custom subagents with YAML config
* 🔹 Tool control (Read, Write, Bash, etc.)
* 🔹 Persistent memory system
* 🔹 Background task execution

---

## ⚡ Quick Start

### 1. Open Claude Code

```bash
claude
```

### 2. Create a Subagent

```bash
/agents
```

### 3. Example Prompt

```
Use the code-reviewer agent to analyze this project
```

---

## 🛠 Example Subagent

```yaml
---
name: code-reviewer
description: Reviews code for quality and best practices
tools: Read, Grep, Glob
model: sonnet
---

You are a senior code reviewer. Analyze code and suggest improvements.
```

---

## 📂 Documentation

* 📘 [Subagents Guide](docs/subagents.md)
* ⚙️ [Setup Guide](docs/setup.md)
* 💡 [Examples](docs/examples.md)

---

## 🎯 Use Cases

* Code Review Automation
* Debugging Assistance
* Data Analysis
* DevOps Automation
* AI Workflow Systems

---

## 🌟 Why This Repo?

This repo simplifies the official Claude Code docs into:

* Easy explanations
* Real examples
* Practical workflows

---

## 🧑‍💻 Author

**Ayan Karmakar**

---

## ⭐ Support

If you found this helpful:

* ⭐ Star this repo
* 🍴 Fork it
* 🔗 Share with others

---
