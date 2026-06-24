# OpenSource-Plan

# 🌍 Open Source Contribution Roadmap
### 3-Month Learning & Contribution Plan

---

## 📌 Goal

> اتعلم Open Source كـ فكرة، concept، وـ resource، وتعمل أول مساهمة حقيقية — تبني project مع team، تفتح issues، وتعمل PRs.

---

## 🗓️ Timeline Overview

| Sprint | Duration | Focus |
|--------|----------|-------|
| Sprint 1 | Week 1–2 (3 Sessions) | Know About Open Source |
| Sprint 2 | Week 3–4 | First Contribution: 2 Issues |
| Sprint 3 | Week 5–8 | Build & Collaborate on a Project |
| Sprint 4 | Week 9–12 | Own PRs, Code Review & Community |

---

## 🟢 Sprint 1 — Know About Open Source
**Duration:** 2 Weeks | 3 Sessions

### 🎯 Goal
فهم Open Source كـ فكرة وازاي تشارك فيه.

### 📚 Sessions

#### Session 1 — What is Open Source?
- [ ] ما هو Open Source وليه مهم
- [ ] الفرق بين Open Source و Closed Source
- [ ] أمثلة على مشاريع كبيرة: Linux, VS Code, React, Python
- [ ] مفهوم الـ License (MIT, Apache, GPL)
- [ ] إزاي بيشتغل الـ community

**Resources:**
- [opensource.guide](https://opensource.guide)
- [firstcontributions.github.io](https://firstcontributions.github.io)

---

#### Session 2 — Git & GitHub for Open Source
- [ ] Git basics: clone, branch, commit, push
- [ ] GitHub: Fork, Star, Watch
- [ ] فهم الـ repository structure
- [ ] قراءة `README.md` و `CONTRIBUTING.md`
- [ ] فهم الـ Issues و Labels

**Practice:**
```bash
git clone <repo-url>
git checkout -b my-first-branch
git add .
git commit -m "feat: add my name to contributors"
git push origin my-first-branch
```

---

#### Session 3 — How to Contribute?
- [ ] ازاي تختار project مناسب
- [ ] نوع الـ Issues: `good first issue`, `bug`, `documentation`, `enhancement`
- [ ] خطوات الـ contribution كاملة
- [ ] عمل Pull Request صح
- [ ] Code Review — ازاي تتعامل مع feedback

**Checklist قبل أي PR:**
- [ ] قرأت الـ CONTRIBUTING.md
- [ ] الكود بيشتغل locally
- [ ] الـ branch اسمه descriptive
- [ ] الـ commit message واضح
- [ ] الـ PR description بيشرح ايه اللي عملته ولييه

---

## 🟡 Sprint 2 — First Contributions
**Duration:** Week 3–4

### 🎯 Goal
تساهم في **2 Issues** في مشاريع حقيقية.

### 🔍 ازاي تلاقي issues مناسبة

**المواقع دي بتساعدك:**
- [goodfirstissue.dev](https://goodfirstissue.dev)
- [up-for-grabs.net](https://up-for-grabs.net)
- [codetriage.com](https://codetriage.com)
- GitHub Search: `label:"good first issue" language:python`

### 📋 Contribution Tracker

| # | Repository | Issue Title | Type | Status | PR Link |
|---|-----------|-------------|------|--------|---------|
| 1 | | | | 🔄 In Progress | |
| 2 | | | | ⏳ Pending | |

**Status Legend:** ⏳ Pending → 🔄 In Progress → 👀 In Review → ✅ Merged

### 📝 Contribution Steps (per Issue)

```
1. اقرأ الـ Issue كويس
2. اعمل comment: "I'd like to work on this"
3. Fork الـ repo
4. Clone locally
5. افتح branch باسم: fix/issue-title أو feat/feature-name
6. اعمل الـ changes
7. اكتب commit message واضح
8. افتح Pull Request
9. استنى الـ review وـ respond عليه
```

---

## 🔵 Sprint 3 — Build a Team Project
**Duration:** Week 5–8

### 🎯 Goal
تبني project مع team ويبقى Open Source على GitHub.

### 📁 Project Structure

```
my-project/
├── README.md          ← شرح المشروع
├── CONTRIBUTING.md    ← ازاي الناس تساهم
├── LICENSE            ← نوع الـ license
├── .github/
│   ├── ISSUE_TEMPLATE/
│   │   ├── bug_report.md
│   │   └── feature_request.md
│   └── PULL_REQUEST_TEMPLATE.md
├── src/               ← الكود
└── docs/              ← الـ documentation
```

### 🏷️ GitHub Setup Checklist
- [ ] إنشاء الـ repository على GitHub
- [ ] كتابة README.md واضح
- [ ] إضافة LICENSE
- [ ] إنشاء `CONTRIBUTING.md`
- [ ] إعداد Issue Templates
- [ ] إضافة Labels: `bug`, `feature`, `good first issue`, `documentation`
- [ ] إنشاء Project Board (Kanban)
- [ ] دعوة الـ team كـ collaborators

### 👥 Team Workflow

```
main branch (protected)
    ↑
develop branch
    ↑
feature/fix branches ← كل شخص بيشتغل هنا
```

**Branch Naming Convention:**
```
feat/add-login-page
fix/broken-navbar
docs/update-readme
refactor/cleanup-utils
```

### 📌 Issues to Open in Your Project (Minimum 5)
- [ ] `feat: Setup project structure`
- [ ] `docs: Write README`
- [ ] `feat: Add main feature X`
- [ ] `fix: Handle edge case Y`
- [ ] `docs: Add CONTRIBUTING guide`

---

## 🟣 Sprint 4 — Code Review, PRs & Community
**Duration:** Week 9–12

### 🎯 Goal
تبقى active community member — تعمل PR review، تشارك في discussions، وتوصل لـ 5+ contributions.

### 🔁 PR Review Skills
- [ ] ازاي تقرأ code بتاع حد تاني
- [ ] تكتب feedback constructive
- [ ] تستخدم GitHub review features: Comment, Approve, Request Changes
- [ ] تفرق بين blocking و non-blocking feedback

**Good PR Review Comment:**
```
✅ "This function works, but consider extracting it 
    for reusability — not blocking though!"
    
❌ "This is wrong, rewrite it."
```

### 📊 Final Goals Tracker

| Goal | Target | Achieved |
|------|--------|----------|
| Issues Contributed To | 2+ | |
| PRs Merged | 3+ | |
| Project Repo Created | 1 | |
| Issues Opened in Own Project | 5+ | |
| PR Reviews Done | 2+ | |
| Stars Received | any 🌟 | |

---

## 🛠️ Essential Tools

| Tool | Purpose |
|------|---------|
| Git | Version control |
| GitHub | Code hosting & collaboration |
| VS Code | Code editor |
| GitHub CLI (`gh`) | GitHub from terminal |
| Markdown | Writing READMEs & docs |

---

## 📖 Learning Resources

### باللغة العربية
- [Elzero Web School - Git & GitHub](https://elzero.org)
- [Arabic Programmers Discord](https://discord.gg/arabicprogrammers)

### بالإنجليزي
- [The Odin Project](https://www.theodinproject.com)
- [GitHub Skills](https://skills.github.com)
- [How to Contribute to Open Source](https://opensource.guide/how-to-contribute)
- [First Contributions Repo](https://github.com/firstcontributions/first-contributions)

### فيديوهات
- "Git and GitHub for Beginners" — freeCodeCamp (YouTube)
- "Open Source Contribution for Beginners" — Traversy Media

--

## 🏆 Milestones

```
Week 2  ✅ → Understand Open Source + Git basics
Week 4  ✅ → First 2 contributions merged
Week 8  ✅ → Team project live on GitHub
Week 12 ✅ → 5+ contributions + active community member
```

---

*Made with ❤️ | Open Source Journey — 3 Month Plan*
