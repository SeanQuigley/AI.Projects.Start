# AI.Projects.Start

# 🤖 AI Coding Best Practices, Main Coding LLM's, IDE's and Setup  

Coding with AI Best Practices, IDE's / Agents / Setup / and Project Management

---

## 📑 Table of Contents

- [🧠 1. Understand AI’s Role](#1-understand-ais-role)
- [🧪 2. Prompting Principles](#2-prompting-principles)
- [🔍 3. Code Review & Testing](#3-code-review--testing)
- [🔐 4. Security & Ethics](#4-security--ethics)
- [📝 5. Documentation & Maintenance](#5-documentation--maintenance)
- [💡 Additional Tips](#6-additional-tips)
##
- [🔑 Golden Rules](#7-golden-rules)
##
- [📲 TOP LLM's for Coding (As of 2025/4, needs updating regularly)](#8-planning-phase)
##
- [💻 AI Coding IDE's and Agents](#9-planning-phase)
##
- [✅ Planning & Task Management](#10-planning-phase)
##


---

## 🧠 1. Understand AI's Role

- **AI as a Collaborator**: Utilize AI tools as partners to enhance productivity, not as replacements for human developers.
- **Prompt Engineering**: Craft clear and specific prompts to obtain optimal results from AI assistants.
- **Iterative Development**: Continuously refine AI-generated code through testing and feedback loops.

---

## 🔍 2. Code Review & Testing

- **Manual Review**: Always inspect AI-generated code to ensure it aligns with project requirements.
- **Automated Testing**: Implement unit, integration, and regression tests to validate functionality.
- **Static Analysis**: Use linters and code analyzers to maintain code quality and consistency.

---

## 🔐 3. Security & Ethics

- **Data Privacy**: Avoid exposing sensitive information to AI tools; understand their data handling policies.
- **Bias Awareness**: Be vigilant of potential biases in AI outputs and address them proactively.
- **Access Control**: Limit AI tools' access to only necessary data and systems.

---

## 📝 4. Documentation & Maintenance

- **Comprehensive Docs**: Document AI-generated code thoroughly for future reference and onboarding.
- **Version Control**: Use systems like Git to track changes and collaborate effectively.
- **Continuous Learning**: Stay updated with evolving AI tools and best practices.

---

## 📚 Additional Resources

- [AI Code Generation Tools: Best Practices](https://toxigon.com/ai-code-generation-tools-best-practices)
- [Best Practices for Coding with AI](https://blog.codacy.com/best-practices-for-coding-with-ai)
- [Secure Coding Practices for AI Applications](https://www.linkedin.com/advice/3/what-most-important-secure-coding-practices-artificial-3yzoc)
- [Great Youtube Channel on latest AI Coding](https://www.youtube.com/@Codewello/videos)
- [Code 100x Faster with AI (youtube vid)](https://youtu.be/SS5DYx6mPw8?si=fF-crKscqfuQOa4R)  
- [Full AI Coding Assistant Workflow](https://docs.google.com/document/d/12ATcyjCEKh8T-MPDZ-VMiQ1XMa9FUvvk2QazrsKoiR8/) (doc with breakdown from above youtube vid)

---

## 🔑 7. Golden Rules

*   **Use markdown files to manage the project and refer the LLM to these files** (README.md, PLANNING.md, TASK.md).

*   **Use GIT to track changes**
    
*   **Keep files under 500 lines.** Split into modules when needed.
    
*   **Start fresh conversations often.** Long threads degrade response quality.
    
*   **Don’t overload the model.** One task per message is ideal.
    
*   **Test early, test often.** Every new function should have unit tests.
    
*   **Be specific in your requests.** The more context, the better. Examples help a lot.
    
*   **Write docs and comments as you go.** Don’t delay documentation.
    
*   **Implement environment variables yourself.** Don’t trust the LLM with API keys.

---

## 📲 8. TOP LLM's for Coding (As of 2025/4, needs updating regularly)

Some of the current Top coding LLM's  

*   [Gemini 2.5 Pro](https://aistudio.google.com/)  
[Gemini 2.5 Pro Setup with VS Code](https://)

*   [Claude 3.7 Sonnet](https://www.anthropic.com/claude/sonnet)  
[Claude 3.7 Sonnet Setup with VS Code](https://youtu.be/Y9JoWcyp0FY?si=9n2JB6-hkklj71_s)

*   [Deepseek v3.1](https://deepseek.ai/blog/deepseek-v31)  
[Deepseek v3.1 Setup with VS Code](https://youtu.be/Hlz93KRJv00?si=mnbV9U7cZaEEqJxV)

    
Also see here for a list of top LLM"s used for Coding that's regularly updated but doesn't detail why or go in depth  
[OpenRouter Programming Rankings](https://openrouter.ai/rankings/programming)

---

## 💻 9. AI Coding IDE's and Agents

To code with AI we usually want an IDE like VS Code and an Agent/Assistant that helps connect the LLM and the IDE.  

VS Code is the main IDE  
[VS Code](https://code.visualstudio.com/)  

Currently Roo Code seems to be agreed on as a top agent to work with VS Code.  
[Roo-Code v3.8](https://youtu.be/g9sq25ECJMQ?si=mX0GXMh56VSDr2Pp)  

Some other top IDE's and Agents are  
[Trae IDE](https://www.trae.ai/)  
[Cursor](https://www.cursor.com/ja/features)  
[Qodo Gen](https://www.qodo.ai/products/qodo-gen/)  
  
Other AI Coding tools of note  
[V0](https://v0.dev/)  
[Bolt](https://bolt.new/)  

---

## ✅ 10. Planning & Task Management

Before writing any code, it’s important to have a conversation with the LLM to plan the initial scope and tasks for the project.  
Scope goes into PLANNING.md, and specific tasks go into TASK.md.  
These should be updated by the AI coding assistant as the project progresses.

### **PLANNING.md**

*   Purpose: High-level vision, architecture, constraints, tech stack, tools, etc.
*   Prompt to AI: _“Use the structure and decisions outlined in PLANNING.md.”_
*   Have the LLM reference this file at the beginning of any new conversation.
    

### **TASK.md**

*   Purpose: Tracks current tasks, backlog, and sub-tasks.
*   Includes: Bullet list of active work, milestones, and anything discovered mid-process.
*   Prompt to AI: _“Update TASK.md to mark XYZ as done and add ABC as a new task.”_
*   Can prompt the LLM to automatically update and create tasks as well (through global rules).

---

more to add soon on setting up an MCD etc  
  









