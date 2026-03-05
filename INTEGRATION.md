# 🛠 Integration & Prompting Guide

This guide explains how to integrate these rules into your existing projects and how to use them effectively during your AI interactions.

## 🔗 How to Integrate with Your Project

### 1. Identify Your AI Tool
Based on the tool you're using, choose the corresponding rule set from `tools/`:
- **Cursor**: Use `tools/cursor/.cursorrules`.
- **Claude Code**: Use `tools/claude/CLAUDE.md`.
- **Antigravity**: Refer to `tools/antigravity/instructions.md`.
- **Windsurf**: Use `tools/windsurf/.windsurfrules`.

### 2. Copy the Rules
For most tools, simply copy the contents of the relevant tool-specific file into your project's root directory with the appropriate filename.

Example for Cursor:
```bash
cp /path/to/agent-rules/tools/cursor/.cursorrules /your/project/root/
```

### 3. Link Language Guidelines
Since your project likely uses specific languages, you can tell the AI to always refer to the relevant file in the `languages/` directory.

---

## 💬 How to Use Rules in Prompts

When starting a task or a conversation with an AI agent, you can explicitly point to these rules to set the ground truth for the session.

### Strategy 1: The "Manual Reference" Prompt
If you haven't integrated the files directly into the project root, you can paste the rules or provide the path in your initial prompt:
> *"I want you to follow the coding standards defined in `/path/to/agent-rules/languages/typescript.md` for this task. Also, keep the security principles from `/path/to/agent-rules/prompts/global_rules.md` in mind."*

### Strategy 2: The "Context Injection" Prompt
For tools that can read your filesystem (like Claude Code or Cursor), you can say:
> *"Read the guidelines in my rules repository at `~/agent-rules/languages/python.md` before refactoring this module."*

### Strategy 3: The "Always-On" Integration
By having `.cursorrules` or `CLAUDE.md` in your project root, the AI will automatically load those instructions at the start of every session. You should include a line in those files that points to your global rules repository:
> *"Refer to the global standards at `~/agent-rules/` for all tool and language-specific best practices."*

---

## 💡 Pro Tips for Prompting

1. **Be Specific**: If you're working on a Flutter app, don't just say "make it better." Say: *"Review my widget structure based on the best practices in `languages/dart.md` and suggest improvements."*
2. **Combine Rules**: You can combine tool-specific flow rules with language-specific patterns. For example: *"Use the Antigravity task_boundary flow but implement the logic using the Swift Concurrency patterns found in `languages/swift.md`."*
3. **Verify by Rule**: After the AI generates code, ask it to verify its own work: *"Check this code against the accessibility guidelines in `languages/html_css.md`. Is there anything missing?"*
