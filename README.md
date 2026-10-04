# App Store Optimization (ASO) Specialist Skill for Claude

A professional-grade agent skill designed to maximize app visibility, metadata search relevancy, and organic conversion rates across both the **Apple App Store** and **Google Play Store**. 

This skill leverages over 10 years of simulated user acquisition experience to deliver copy-paste ready metadata blocks while strictly respecting platform-specific character caps and target-country localization parameters.

---

## 🚀 Installation & Sync

You can inject this skill globally into your local terminal-based AI agents, code editors, or directly sync it into your Claude desktop application workspace using the public repository source path.

### Method 1: Global Terminal Installation (via npx)
To install and provision this skill across your locally supported AI environments, navigate to your work directory and execute:
```bash
npx skills add your-github-username/your-repo-name
```
*Note: Make sure to replace `your-github-username/your-repo-name` with the actual public path to this repository.*

### Method 2: Claude Desktop Integration
1. Open your **Claude Desktop** application interface.
2. Navigate to **Customize > Plugins** (or **Skills**) in your settings dashboard.
3. Click on **Add marketplace** or **Add local source**.
4. Paste the repository identifier string (`your-github-username/your-repo-name`) directly into the sync input bar and click confirm.

---

## 🛠️ Main Capabilities & Features

Once enabled, the skill monitors user optimization prompts to systematically execute a standard 4-step metadata creation layout:

* **Strict Character Caps Enforcement:** Automatically measures and truncates metadata lines to guarantee strict compliance with store limits (App Store 30-ch titles/subtitles, 100-ch keyword fields; Google Play 30-ch titles, 80-ch short descriptions, and 4,000-ch structured long descriptions).
* **Multi-Country Localization Framework:** Adapts underlying keyword mapping, regional spelling adjustments (e.g., US vs. UK/Commonwealth), and local cultural intent benchmarks based on your specified target country.
* **Metadata Copy-Paste Blocks:** Outputs all localized results inside explicit, cleanly labeled markdown data tracking panels (`[TRACKING DATA-FIELD: ...]`) for immediate entry into your developer consoles.
* **Validation Checkpoints:** Filters against malicious search behaviors (such as Google Play keyword stuffing rules) and generates baseline performance projections to map organic download visibility.

---

## 📖 How to Use the Skill

To initiate the ASO workflow, simply provide the agent with your baseline application details, target country, and primary focus areas.

### Example Prompts:
> *"Optimize my upcoming fitness tracking app for the United States storefront. Here is a brief description of my key features..."*

> *"Review my current Google Play store title and short description, and adjust it for a United Kingdom release using strict character limits."*

---

## 📄 License
This custom skill repository is open-source and distributed under the **MIT License**. Feel free to fork, expand, or adapt the prompt settings for your personal application workflows.
