This is a great initiative. Tracking your application of CFAR (Center for Applied Rationality) techniques is the best way to move them from "interesting concepts" to "actual life skills."

Since I cannot directly access your GitHub account to create the repo, I have designed a comprehensive **Template and Setup Guide** for you.

Follow these steps to build a personal rationality record.

### 1. Repository Structure
I recommend the following folder structure to keep your practice organized.

```text
rationality-practice/
├── README.md               # Overview of your goals and current focus
├── journal/                # Daily or weekly logs of rationality wins/fails
│   ├── 2024-01-entry.md
│   └── ...
├── techniques/             # Deep dives into specific CFAR units
│   ├── TAPs/               # Trigger-Action Plans
│   ├── Murphyjitsu/        # Pre-mortems and planning
│   ├── Goal_Factoring/     # Analyzing motivations
│   ├── Inner_Simulator/    # Forecasting and gut-checks
│   ├── Double_Crux/        # Disagreement resolution logs
│   ├── Focusing/           # Gendlin's Focusing sessions
│   └── CoZE/               # Comfort Zone Expansion challenges
├── projects/               # Large life projects where you apply multiple techniques
│   └── career-change/
│       └── planning.md
├── reading-notes/          # Notes on the Handbook, Sequences, or Scout Mindset
└── templates/              # Blank forms to copy-paste for new sessions
    ├── daily-review.md
    └── debugging-session.md
```

---

### 2. Files to Create

#### A. The `README.md`
Create a file named `README.md` in the root folder. Paste this text:

```markdown
# My Rationality Practice Record

This repository serves as a personal laboratory for applying techniques from [rationality.org](https://www.rationality.org/) (CFAR).

## 🎯 Current Focus
*   **Habit I'm building:** (e.g., Checking for "fake frameworks")
*   **Technique I'm practicing:** (e.g., TAPs for morning routine)
*   **Reading:** (e.g., The Scout Mindset)

## 🧠 Core Techniques Directory
*   [Trigger Action Plans (TAPs)](./techniques/TAPs)
*   [Murphyjitsu](./techniques/Murphyjitsu) - Making plans robust.
*   [Goal Factoring](./techniques/Goal_Factoring) - Understanding my true drivers.
*   [Focusing/Inner Simulator](./techniques/Focusing) - Consulting System 1.
*   [Double Crux](./techniques/Double_Crux) - Finding the truth in disagreements.

## 📝 Status
*   **Started:** [Date]
*   **Last Review:** [Date]
```

#### B. The Debugging Template
Create a file at `templates/debugging-session.md`. You can copy this file whenever you feel "stuck" or "ugh" about a task.

```markdown
# 🐛 Rationality Debugging Session
**Date:** YYYY-MM-DD
**Topic:** (e.g., Why am I procrastinating on the taxes?)

## 1. The Felt Sense (Focusing)
*What does the problem feel like in my body? (e.g., A tightness in the chest, a grey fog?)*
> 

## 2. Murphyjitsu (The Pre-Mortem)
*If I try to solve this and fail, what was the surprise cause?*
> 

## 3. Goal Factoring
*What do I actually want here? (List both noble goals and "shadow" goals like comfort)*
*   
*   

## 4. TAPs (Trigger Action Plan)
*New Plan:*
*   **Trigger:** When I [specific sensation or event]...
*   **Action:** Then I will [small, concrete action].
```

#### C. The Daily Review Template
Create a file at `templates/daily-review.md`.

```markdown
# 📅 Daily Rationality Review

## 5-Second Level Checks
- [ ] **Surprise:** Did anything surprise me today? Did I update my beliefs?
- [ ] **Arguments:** Did I try to win an argument rather than find the truth?
- [ ] **System 1:** Did I ignore a "gut check" feeling?

## Analysis
**Moment of irrationality:**
> (e.g., I bought the expensive coffee because I was tired, not because I decided to.)

**Moment of rationality:**
> (e.g., I noticed I was angry, paused, and asked "What is this emotion trying to tell me?")

## TAPs for Tomorrow
*   **If** [situation], **Then** [action].
```

---

### 3. How to Set This Up on GitHub

If you are comfortable with the command line (Terminal), use **Option A**. If you prefer using the website, use **Option B**.

#### Option A: Command Line (Fastest)
1.  Open your terminal.
2.  Run the following commands one by one:

```bash
# 1. Create the directory
mkdir rationality-practice
cd rationality-practice

# 2. Initialize Git
git init

# 3. Create the directory structure
mkdir journal techniques projects reading-notes templates
mkdir techniques/TAPs techniques/Murphyjitsu techniques/Goal_Factoring techniques/Double_Crux

# 4. Create the README
echo "# My Rationality Practice" >> README.md

# 5. Commit the changes locally
git add .
git commit -m "Initial commit: Set up CFAR practice structure"

# 6. Link to GitHub (Create a new empty repo on GitHub.com first!)
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/rationality-practice.git
git push -u origin main
```

#### Option B: Web Interface (Easiest)
1.  Go to [github.com/new](https://github.com/new).
2.  Repository name: `rationality-practice`.
3.  Check **"Add a README file"**.
4.  Click **Create repository**.
5.  Click the **"Add file"** button -> **"Create new file"**.
6.  Type `templates/debugging-session.md` (typing the slash `/` automatically creates the folder).
7.  Paste the template code from step 2B above.
8.  Commit the file.
9.  Repeat for other folders/files.

### 4. How to use this effectively
*   **Don't just read, do:** If you read about "Goal Factoring" on the website, go to your `techniques/Goal_Factoring/` folder, create a file named `attempt-01.md`, and actually do the exercise on a real problem.
*   **The "Ugh" Field:** If you feel an "Ugh" field (aversion) around updating this repo, use that *itself* as practice. Open a journal entry and investigate why you feel aversion.
