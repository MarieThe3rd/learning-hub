# 🎓 Learning Hub

A multi-topic, AI-mentored learning repository powered by GitHub Copilot. Pick a topic, chat with your mentor, take notes, and build projects — all in one place.

---

## 📚 Topics

| Topic | Folder | Status |
|-------|--------|--------|
| 🤖 [GitHub Copilot](./topics/github-copilot/) | `topics/github-copilot/` | ⚪ Not Started |
| 🟣 [.NET Development](./topics/dotnet-development/) | `topics/dotnet-development/` | ⚪ Not Started |
| 🌐 [Modern Web Development](./topics/modern-web-development/) | `topics/modern-web-development/` | ⚪ Not Started |
| 🗄️ [SQL](./topics/sql/) | `topics/sql/` | ⚪ Not Started |
| ☁️ [Azure Development](./topics/azure-development/) | `topics/azure-development/` | ⚪ Not Started |
| 🏛️ [Architecture](./topics/architecture/) | `topics/architecture/` | ⚪ Not Started |
| 💙 [PowerShell](./topics/powershell/) | `topics/powershell/` | ⚪ Not Started |
| ✨ [Dev Principles & Practices](./topics/dev-principles-and-practices/) | `topics/dev-principles-and-practices/` | ⚪ Not Started |

**Progress Legend:** ⚪ Not Started &nbsp;|&nbsp; 🟡 In Progress &nbsp;|&nbsp; 🟢 Confident &nbsp;|&nbsp; ✅ Complete

---

## 🤖 Available Mentors (Prompt Files)

### General Mentors

| Prompt File | Use For |
|-------------|---------|
| [`@mentor`](./.github/prompts/mentor.prompt.md) | General learning guidance for any topic |
| [`@quiz-me`](./.github/prompts/quiz-me.prompt.md) | Test your knowledge with adaptive quizzes |
| [`@explain`](./.github/prompts/explain.prompt.md) | Deep, structured explanations of any concept |
| [`@review-my-work`](./.github/prompts/review-my-work.prompt.md) | Constructive code review and feedback |
| [`@project-ideas`](./.github/prompts/project-ideas.prompt.md) | Hands-on project suggestions for any topic |

### Topic Specialists

| Prompt File | Speciality |
|-------------|------------|
| [`@dotnet-mentor`](./.github/prompts/dotnet-mentor.prompt.md) | C#, ASP.NET Core, Entity Framework Core |
| [`@web-dev-mentor`](./.github/prompts/web-dev-mentor.prompt.md) | HTML, CSS, JavaScript, TypeScript, React |
| [`@sql-mentor`](./.github/prompts/sql-mentor.prompt.md) | SQL queries, database design, optimisation |
| [`@azure-mentor`](./.github/prompts/azure-mentor.prompt.md) | Azure services, deployment, DevOps |
| [`@architecture-mentor`](./.github/prompts/architecture-mentor.prompt.md) | Patterns, DDD, microservices, system design |
| [`@powershell-mentor`](./.github/prompts/powershell-mentor.prompt.md) | PowerShell scripting and automation |
| [`@dev-principles-mentor`](./.github/prompts/dev-principles-mentor.prompt.md) | Clean Code, OOP, SOLID, Design Patterns |

---

## 🚀 How to Use This Repository

1. **Pick a topic** from the table above and open its folder
2. **Read the topic README** for the learning roadmap and goals
3. **Open Copilot Chat** and attach a prompt file as your mentor
4. **Take notes** in the topic's `notes/` folder as you learn
5. **Complete exercises** in the topic's `exercises/` folder
6. **Update your status** in the topics table above as you progress

### Example: Starting a learning session

```
1. Open .github/prompts/dotnet-mentor.prompt.md in Copilot Chat
2. Set topic focus: "ASP.NET Core Web APIs"
3. Ask: "Can you give me an overview of how routing works in ASP.NET Core?"
4. Take notes in topics/dotnet-development/notes/
```

---

## ➕ Adding a New Learning Topic

Follow these steps to add a new topic to this learning hub:

### Step 1: Create the Topic Folder Structure

```bash
# Replace {topic-name} with your topic slug (e.g., "kubernetes", "python")
mkdir -p topics/{topic-name}/notes
mkdir -p topics/{topic-name}/exercises
touch topics/{topic-name}/notes/.gitkeep
touch topics/{topic-name}/exercises/.gitkeep
```

### Step 2: Create the Topic README

Create `topics/{topic-name}/README.md` using this template:

```markdown
# {Emoji} {Topic Name}

One-line description of this topic.

## 🎯 Learning Goals

- [ ] Goal 1
- [ ] Goal 2
- [ ] Goal 3

## 🗺️ Learning Path

### Stage 1: {Stage Name}
- Subtopic / concept
- Subtopic / concept

### Stage 2: {Stage Name}
- Subtopic / concept

## 📁 Folder Structure

topics/{topic-name}/
├── notes/       ← Add your markdown notes here
├── exercises/   ← Practice files
└── README.md    ← This file

## 🔗 Related Topics

- **{Related Topic}** — Why it's related

## 🤖 Mentor

Use `@mentor` with `topic = "{Topic Name}"`, or the topic-specific mentor if one exists.
```

### Step 3: (Optional) Create a Topic-Specific Mentor Prompt

If the topic benefits from a specialist mentor, create `.github/prompts/{topic-name}-mentor.prompt.md`:

```markdown
---
description: "{Topic} specialist mentor"
---

You are an expert {topic} mentor with deep knowledge of...

## Your Expertise

- Area 1
- Area 2

## Teaching Approach

- Guideline 1
- Guideline 2

## Useful References

- My notes: `/topics/{topic-name}/notes/`
- My exercises: `/topics/{topic-name}/exercises/`

## Session Context

Topic focus: `${focus}`
My skill level: `${level:beginner}`
```

### Step 4: Update This README

Add a row to the **Topics** table:

```markdown
| {Emoji} [{Topic Name}](./topics/{topic-name}/) | `topics/{topic-name}/` | ⚪ Not Started |
```

If you added a topic-specific mentor prompt, add a row to the **Topic Specialists** table:

```markdown
| [`@{topic-name}-mentor`](./.github/prompts/{topic-name}-mentor.prompt.md) | {Short description} |
```

### Step 5: Update `copilot-instructions.md`

Add your new topic to the **Current Learning Topics** list in `.github/copilot-instructions.md`:

```markdown
- `{topic-name}` - Brief description of what this topic covers
```

---

## 🔗 Topic Connections

```
Dev Principles & Practices
        ↓ (foundation for everything)
    ┌───┴────────────────────┐
    ↓                        ↓
.NET Development      Modern Web Dev
    ↓         ↘          ↙
   SQL      Architecture
    ↓              ↓
Azure Development ←──────────────────
        ↑
   PowerShell (automation)
```

GitHub Copilot enhances every topic — use it as your learning companion throughout!

---

## 💡 Tips for Success

- **Small sessions beat marathon sessions** — 30 focused minutes beats 3 distracted hours
- **Write notes in your own words** — don't just copy explanations; rephrase them
- **Build things** — use `@project-ideas` to get practical exercise ideas for every topic
- **Connect the dots** — ask your mentor how a concept relates to other topics you know
- **Use `@quiz-me` regularly** — retrieval practice is one of the most effective learning techniques
- **Commit your notes and exercises** — version control your learning journey
