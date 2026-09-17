# 🤖 Build a Portfolio Generation Agent

In this hands-on activity, you will create and use a custom **Portfolio Generation Agent** with **GitHub Copilot CLI**.

The agent will analyze a user's CV or profile information and use the verified information to create a professional, responsive personal portfolio website.

By completing this activity, you will learn how to:

* Create a custom GitHub Copilot CLI Agent
* Create a reusable `SKILL.md`
* Understand the difference between an Agent and a Skill
* Run a custom Agent using GitHub Copilot CLI
* Provide a CV as input
* Analyze CV information
* Generate a professional portfolio website
* Review and improve an AI-generated portfolio
* Validate the final website
* Work safely with AI-assisted development

---

# 📚 Content

| Step                                                        | Activity                              | Description                                                    |
| ----------------------------------------------------------- | ------------------------------------- | -------------------------------------------------------------- |
| [Step 01](#step-01---prepare-the-workshop-project)          | Prepare the Workshop Project          | Create or open the project used for the activity.              |
| [Step 02](#step-02---create-the-agent-directory)            | Create the Agent Directory            | Create `.github/agents/` for the custom Agent.                 |
| [Step 03](#step-03---create-the-agent) | Create the Portfolio Generation Agent | Add the provided Agent configuration.                          |
| [Step 04](#step-04---create-the-skill-directory)            | Create the Skill Directory            | Create the directory for the Portfolio Generation Skill.       |
| [Step 05](#step-05---create-the-skillmd)                    | Create the `SKILL.md`                 | Add the detailed portfolio-generation instructions.            |
| [Step 06](#step-06---start-github-copilot-cli)              | Start GitHub Copilot CLI              | Launch Copilot CLI and load the Agent and Skill.               |
| [Step 07](#step-07---verify-the-agent-and-skill)            | Verify the Agent and Skill            | Confirm that the custom Agent and Skill are available.         |
| [Step 08](#step-08---provide-and-analyze-your-cv)           | Provide and Analyze Your CV           | Give the CV to the Agent and verify the extracted information. |
| [Step 09](#step-09---generate-the-portfolio)                | Generate the Portfolio                | Create the portfolio from the verified CV information.         |
| [Step 10](#step-10---review-the-portfolio)                  | Review the Portfolio                  | Ask the Agent to inspect the generated website.                |
| [Step 11](#step-11---improve-the-portfolio)                 | Improve the Portfolio                 | Apply approved improvements.                                   |
| [Step 12](#step-12---final-testing-and-evidence)            | Final Testing and Evidence            | Test the website and capture required evidence.                |

---

# ⚠️ Important

Complete this activity using **GitHub Copilot CLI**.

You should understand and review the commands, plans, file changes, and code proposed by the AI before approving them.

Do not blindly approve AI-generated changes.

## 🛠️ Step-by-Step Activities

<a id="step-01---prepare-the-workshop-project"></a>

## Step 01 - Prepare the Workshop Project

Create or open a dedicated project folder for this activity.

For example:

```powershell
mkdir Portfolio-Agent
cd Portfolio-Agent
```

Open the project in Visual Studio Code:

```powershell
code .
```

Your project can initially be empty.

Expected structure:

```text
Portfolio-Agent/
```

---

<a id="step-02---create-the-agent-directory"></a>

## Step 02 - Create the Agent Directory

Custom Agents are stored inside the project's `.github/agents` directory.

Create the required directories:

```powershell
mkdir .github
mkdir .github\agents
```

You can verify the directory:

```powershell
Get-ChildItem .github
```

Expected structure:

```text
Portfolio-Agent/
└── .github/
    └── agents/
```

> **Important:** Do not assume that GitHub Copilot CLI will automatically create `.github/agents` when it is launched for the first time.

---

<a id="step-03---create-the-portfolio-generation-agent"></a>

## Step 03 - Create the Portfolio Generation Agent

This repository provides a **Portfolio Generation Agent** configuration.

The provided Agent resource is located in the workshop repository:

[Open `agent.md`](resources/Portfolio%20Generation%20Agent/agent.md)

Copy the provided Agent configuration into `agents` file.

Expected structure:

```text
Portfolio-Agent/
└── .github/
    └── agents/
        └── agent.md
```

---

<a id="step-04---create-the-skill-directory"></a>

## Step 04 - Create the Skill Directory

The Portfolio Generation Skill will be stored separately from the Agent.

Create the Skill directory:

```powershell
mkdir .github\skills
```

Expected structure:

```text
Portfolio-Agent/
└── .github/
    ├── agents/
    │   └── agent.md
    └── skills
```

---

<a id="step-05---create-the-skillmd"></a>

## Step 05 - Create the `SKILL.md`

This repository provides a **SKILL** configuration.

The provided SKILL resource is located in the workshop repository:

[Open `SKILL.md`](resources/Portfolio%20Generation%20Agent/SKILL.md)


Copy the provided Portfolio Generation Skill instructions into the file.

The final location must be:

```text
Portfolio-Agent/
└── .github/
    ├── agents/
    │   └── agent.md
    └── skills
        └── SKILL.md
```

---

<a id="step-06---start-github-copilot-cli"></a>

## Step 06 - Start GitHub Copilot CLI

Make sure you are in the project root:

```powershell
cd Portfolio-Agent
```

Start GitHub Copilot CLI:

```powershell
copilot
```

You should now be inside the Copilot CLI environment.

---

<a id="step-07---verify-the-agent-and-skill"></a>

## Step 07 - Verify the Agent and Skill

Open the available custom Agents:

```text
/agent
```

Select:

```text
portfolio-agent
```
---
<a id="step-08---provide-and-analyze-your-cv"></a>

## Step 08 - Provide and Analyze Your CV

Exit Copilot CLI:

```text
/exit
```

Place your CV inside the project root.

For example:

```text
Portfolio-Agent/
│
├── CV.pdf
│
└── .github/
    ├── agents/
    │   └── portfolio-generation.agent.md
    │
    └── skills/
        └── portfolio-generation/
            └── SKILL.md
```
---

<a id="step-09---generate-the-portfolio"></a>

## Step 09 - Generate the Portfolio

Start Copilot CLI again:

```powershell
copilot
```

Select the Portfolio Generation Agent:

```text
/agent
```

After analysis the CV and confirming that the extracted information is accurate, provide the following prompt:

```text
Using the verified information from my CV and following the portfolio-generation skill, create my professional personal portfolio website.

Requirements:

1. Use my CV as the primary source of information.

2. Do not invent any personal, educational, professional, project, certification, achievement, or technical information.

3. Create appropriate sections based on the information available in my CV.

4. Highlight my relevant projects and technical skills.

5. Create a modern and professional UI.

6. Make the website responsive for desktop, laptop, tablet, and mobile.

7. Use appropriate images and visual elements where they improve the design.

8. Include my relevant professional links.

9. Use clean and maintainable code.

10. Follow semantic HTML and accessibility best practices.

11. Preserve the existing project structure where possible.

12. Do not delete important files.

13. Do not unnecessarily replace working functionality.

14. Explain the proposed implementation plan before making changes.

15. Identify the files that will be created or modified.

First create the implementation plan.

Do not make changes until I approve the plan.
```

Review the implementation plan carefully.

Check:

* Files to be created
* Files to be modified
* Technologies
* Portfolio sections
* Design approach
* Images
* Responsive approach
* Navigation
* Accessibility
* Existing functionality

If the plan is acceptable, tell Copilot:

```text
The plan looks good. Proceed with the implementation.

Follow the approved plan and the Portfolio Generation Agent and Skill instructions.

Do not invent information.

Do not delete important files.

Do not unnecessarily remove working functionality.
```

Copilot will then create or modify the portfolio files.

---

###  Expected Result

A functional portfolio website generated from the verified information contained in your CV.

---

<a id="step-10---review-the-portfolio"></a>

## Step 10 - Review the Portfolio

After the portfolio has been generated, ask Copilot to review it.

Use:

```text
Review the portfolio you just created according to the portfolio-generation skill.

Analyze:

- Content accuracy
- UI/UX
- Visual hierarchy
- Typography
- Spacing
- Navigation
- Responsiveness
- Accessibility
- Project presentation
- Mobile layout
- Code quality
- HTML quality
- CSS quality
- JavaScript quality
- Broken links
- Missing assets
- Console errors
- Button functionality

Identify the five most important improvements.

Do not make changes yet.

Explain each improvement and why it is needed.
```

Review the recommendations before making changes.

---

<a id="step-11---improve-the-portfolio"></a>

## Step 11 - Improve the Portfolio

After reviewing the recommendations, ask Copilot:

```text
Apply the approved improvements.

Requirements:

- Preserve the existing project structure.
- Do not delete important files.
- Do not invent information.
- Preserve working functionality.
- Follow the portfolio-generation skill.
- Make targeted improvements without unnecessarily rewriting working code.

After making the changes, verify that the portfolio still works correctly.
```

Review the changes proposed by Copilot before approving them.

---

<a id="step-12---final-testing-and-evidence"></a>

## Step 12 - Final Testing and Evidence

Before completing the activity, verify the portfolio.

---

# 🎓 Learning Outcome

After completing this activity, participants should understand how to combine a **custom GitHub Copilot CLI Agent** with a reusable **Skill** to perform a structured AI-assisted development workflow.
