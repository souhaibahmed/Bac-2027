# BAC Algeria 2027 - Product Requirements Document (PRD)

## 📌 Project Overview

- **Project Name**: BAC Algeria 2027 - Study Resources Repository
- **Purpose**: A private GitHub repository containing YouTube channels, websites, AI tools, AI prompts, and study resources to help Algerian BAC 2027 students prepare for their exams
- **Target Users**: Algerian BAC students (all streams: Sciences, Math, Letters, Philosophy, Gestion, etc.)
- **Status**: Private repository (until completion)

---

## 📁 Folder Structure

```
bac2027/
├── README.md                    # Arabic introduction + how to use
├── Youtube_Channels/            # YouTube channels by subject
│   ├── Math.txt               # (placeholder - will edit later)
│   ├── Physics.txt
│   ├── Chemistry.txt
│   ├── SVT.txt
│   ├── Arabic.txt
│   ├── French.txt
│   ├── Philosophy.txt
│   └── English.txt
├── Websites/                  # Educational websites
│   ├── README.md
│   ├── Revizly.md
│   ├── BacFlix.md
│   ├── BacZoneDZ.md
│   ├── BacDzNet.md
│   ├── Khabech.md
│   └── Mon_Bac.md
├── Apps/                     # Mobile applications
│   ├── README.md
│   ├── Afidni_BAC.md
│   ├── كل_ما_تحتاجه_في_البكالوريا.md
│   └── الناجح_في_البكالوريا.md
├── AI_Tools/                 # AI tools for study
│   ├── README.md
│   ├── ChatGPT.md
│   ├── Claude.md
│   ├── Copilot.md
│   └── Gemini.md
├── AI_Prompts/                # Ready-to-use AI prompts
│   ├── README.md
│   ├── 01_explain_concept.md
│   ├── 02_generate_notes.md
│   ├── 03_practice_mcqs.md
│   ├── 04_quiz_mode.md
│   ├── 05_study_plan.md
│   ├── 06_solve_past_papers.md
│   └── 07_revision_sheet.md
├── Past_Papers/               # Previous BAC exams
│   └── README.md
└── Study_Schedule/            # Study schedule templates
    └── README.md
```

---

## 🎬 YouTube Channel Display Format

Each channel file will have this structure:

```markdown
## Channel Name

![Channel Photo](photo_url)

[Channel Name](youtube_link)

Description: Brief description of the channel content
```

---

## 📝 Content Requirements

### 1. YouTube Channels
- Channels sorted by subject
- Each channel: name, photo placeholder, description, link
- Only Algerian-relevant channels

### 2. Websites
- Each website: name, description, link, features
- Focus on Algerian platforms

### 3. Apps
- Each app: name, platform (Android/iOS), description, download link

### 4. AI Tools
- Each tool: name, description, link, how to use for study

### 5. AI Prompts
- Ready-to-use prompts in Arabic
- Examples for each prompt type

---

## 🔧 Technical Notes

- **Language**: Arabic content
- **GitHub Connection**: Local folder → Git remote private repo
- **Updates**: All changes made locally will be pushed to GitHub

---

## ✅ TODO List

- [ ] Initialize Git in local folder
- [ ] Connect to private GitHub repository
- [ ] Create folder structure
- [ ] Add YouTube channels files (from user input)
- [ ] Populate Websites folder
- [ ] Populate Apps folder
- [ ] Create AI Prompts
- [ ] Create Past Papers placeholder
- [ ] Create Study Schedule template
- [ ] Make repository public (after completion)

---

## 📅 Project Timeline

1. **Phase 1**: Setup folders + connect GitHub
2. **Phase 2**: Add YouTube channels (subject by subject)
3. **Phase 3**: Add websites + apps
4. **Phase 4**: Create AI prompts
5. **Phase 5**: Add past papers + study schedule
6. **Phase 6**: Review + make public

---

## 🔗 GitHub Connection Instructions

### Option 1: Using GitHub CLI (if installed)
```bash
# Check if gh is installed
gh --version

# Login to GitHub
gh auth login

# Create repo (if not exists)
gh repo create bac2027 --private --source=. --push
```

### Option 2: Manual connection
1. Go to GitHub → New Repository
2. Name: `bac2027`
3. Set as Private
4. Run these commands in local folder:
```bash
git init
git add .
git commit -m "Initial commit"
git remote add origin https://github.com/YOUR_USERNAME/bac2027.git
git push -u origin main
```

---

*Document created for BAC Algeria 2027 preparation project*
*Last updated: April 2026*