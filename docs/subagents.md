# 🤖 Understanding Subagents in Claude Code

## 🧠 What are Subagents?

Subagents are specialized AI assistants designed to handle specific tasks like:

* Code review
* Debugging
* Data analysis

Each subagent:

* Runs independently
* Has its own system prompt
* Can use specific tools

---

## 🔹 Built-in Subagents

### 🔍 Explore

* Read-only agent
* Used for searching code

### 📊 Plan

* Used for research before execution

### ⚙️ General-purpose

* Handles complex multi-step tasks

---

## 🛠 Creating a Subagent

Subagents are defined using YAML:

```yaml
---
name: code-reviewer
description: Reviews code for quality
tools: Read, Grep, Glob
model: sonnet
---

You are a senior developer reviewing code.
```

---

## 🔐 Tool Control

You can restrict tools:

```yaml
tools: Read, Grep
```

Or block tools:

```yaml
disallowedTools: Write, Edit
```

---

## 🧠 Memory Support

```yaml
memory: project
```

This allows the agent to:

* Learn patterns
* Store insights
* Improve over time

---

## 🎯 Why Use Subagents?

* Keep main context clean
* Improve performance
* Modular AI workflows
* Better control & security
