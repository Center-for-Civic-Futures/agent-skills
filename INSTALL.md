# Installing a Skill

How to install any skill from this repository in **Claude**, **ChatGPT**, or **Gemini** on a Windows PC or Mac. No technical experience needed.

*Steps last checked October 2026. These apps change their menus often. If a button has moved, see the official help pages linked under [Troubleshooting](#troubleshooting).*

---

## Contents

- [Step 1: Download the skill](#step-1-download-the-skill)
- [Step 2: Install it in your AI app](#step-2-install-it-in-your-ai-app)
  - [Claude](#claude)
  - [ChatGPT](#chatgpt)
  - [Gemini](#gemini)
- [Step 3: Use the skill](#step-3-use-the-skill)
- [Troubleshooting](#troubleshooting)

---

## Step 1: Download the skill

Each skill has its own ZIP file. Click the download link for the skill you want:

| Skill | What it does | Download |
|---|---|---|
| [AI Use Case Evaluator](./skills/ai-use-case-evaluator/) | Scores proposed AI projects and vendor solutions against the AI-Ready evaluation framework | [⬇️ ai-use-case-evaluator.zip](https://github.com/Center-for-Civic-Futures/agent-skills/releases/latest/download/ai-use-case-evaluator.zip) |

The file saves to your **Downloads** folder. **Keep it as a ZIP. Don't open or unzip it.**

> [!WARNING]
> **Mac users:** Safari sometimes unzips downloads automatically. If you see a **folder** instead of a ZIP file, right-click the folder (or hold **Control** and click) and choose **Compress**. That turns it back into a ZIP.

<details>
<summary><strong>Download link not working?</strong> Click here for a backup method.</summary>

1. Go to the [main page of this repository](https://github.com/Center-for-Civic-Futures/agent-skills).
2. Click the green **Code** button, then **Download ZIP**.
3. Open the downloaded `agent-skills-main.zip`. On a PC, click **Extract All**.
4. Open the `skills` folder and find the folder for your skill (for example, `ai-use-case-evaluator`).
5. Turn **that folder** (not the outer folders) into a ZIP:
   - **Mac:** Right-click the folder and choose **Compress**.
   - **Windows 11:** Right-click the folder and choose **Compress to ZIP file**.
   - **Windows 10:** Right-click the folder and choose **Send to → Compressed (zipped) folder**.
6. Use the new ZIP in Step 2.

</details>

---

## Step 2: Install it in your AI app

> [!CAUTION]
> Only install skills from sources you trust. Skills give your AI assistant instructions to follow. You can read everything a skill contains in its `SKILL.md` file in this repository.

### Claude

**Available on:** All plans. Use claude.ai or the Claude desktop app.

**First, turn on the required setting** (Free, Pro, and Max plans):

1. Click your name in the bottom-left corner, then **Settings → Capabilities**.
2. Turn on **Code execution and file creation**.

> [!NOTE]
> **Team or Enterprise plan?** Your organization's Claude administrator controls this setting. If you don't see the Skills options below, ask them to enable Skills.

**Then install the skill:**

1. In the left sidebar, click **Customize → Skills**.
2. Click **+**, then **Create skill → Upload a skill**.
3. Choose the skill's ZIP file and click **Open**.
4. Confirm the skill's switch is turned **on**.

### ChatGPT

**Available on:** ChatGPT **Business, Enterprise, Healthcare, and Edu** plans. (Using Free, Plus, or Pro? See the workaround below.)

> [!NOTE]
> **Work or school account?** Your administrator may need to turn on Skills and skill uploading first.

1. In the left sidebar, click **Plugins**, then the **Skills** tab.
2. Click **Create → Upload from your computer**.
3. Choose the skill's ZIP file and click **Open**.
4. Wait a moment while ChatGPT scans the skill. It's ready when the scan finishes.

ChatGPT doesn't sync skills between its desktop app and the website or phone. If you use both, install the skill in each one.

<details>
<summary><strong>On ChatGPT Free, Plus, or Pro?</strong> Use a Project instead.</summary>

This isn't a full skill, but it captures the core instructions.

1. In ChatGPT, create a new **Project** named after the skill.
2. In this repository, open the skill's folder, then its `SKILL.md` file. Click the **Copy raw file** button (two overlapping squares, top-right of the file).
3. Paste the text into the project's **Instructions**.
4. If the skill's README lists reference documents, add them to the project's **Files**.
5. Start your chats inside that project.

</details>

### Gemini

**Available on:** Personal Google accounts, ages 18+, with Gemini Apps Activity ("Keep Activity") turned on. Use [gemini.google.com](https://gemini.google.com) in any browser, or the Gemini app on Mac.

1. Go to [gemini.google.com](https://gemini.google.com).
2. In the left sidebar, click **Customize** (if you don't see it, click **More** first), then **Skills** at the top.
3. Click **Create → Upload**.
4. Choose the skill's ZIP file and click **Open**.
5. Review the details, then click **Create** at the top.

> [!NOTE]
> **Using Gemini through work (Gemini Enterprise)?** Go to **Skills** in the navigation menu, click the **+** icon, then **Upload skill**. Your administrator may need to enable this.

---

## Step 3: Use the skill

Open a new chat and ask for what you need. Each skill's README suggests a prompt to get started. The assistant uses the skill automatically when it fits.

If the assistant doesn't seem to pick up the skill, name it directly, for example: *"Use the ai-use-case-evaluator skill."* In Gemini, you can also type **/** in the chat box and select the skill.

---

## Troubleshooting

| Problem | What to try |
|---|---|
| **I don't see a Skills menu** | Check that your plan supports skills (see each app's section above). On a work account, ask your administrator. Try the website if the desktop app looks different. |
| **Claude: no Skills section** | Turn on **Code execution and file creation** in **Settings → Capabilities**. |
| **"Invalid skill" or upload error** | Make sure you're uploading the skill's own ZIP, not the full repository ZIP (`agent-skills-main.zip`). |
| **Mac: the upload fails** | Re-download the ZIP. In Gemini, you can also upload the unzipped skill folder directly. |
| **The skill installed, but nothing happens** | Make sure it's switched **on**, then try the starter prompt from the skill's README. |
| **The menus look different from these steps** | See the official help pages: [Claude](https://support.claude.com/en/articles/12512180-use-skills-in-claude) · [ChatGPT](https://help.openai.com/en/articles/20001066-skills-in-chatgpt) · [Gemini](https://support.google.com/gemini/answer/17094296) |

Still stuck? [Open an issue](https://github.com/Center-for-Civic-Futures/agent-skills/issues) or [contact us](https://www.centerforcivicfutures.org/contact).
