# Agent log

Add a dated entry each time you work with your AI coding agent, with the newest entry at the bottom. Each entry records what you asked the agent, what it produced, and what you checked or changed. Paste your key prompts in exactly as you typed them. Include at least one time the agent got something wrong, and how you caught it.

Copy this outline for each entry:

```markdown
## YYYY-MM-DD: What you worked on

- **Asked:** "Paste your prompt here."
- **Agent produced:** What it made or changed.
- **Checked or changed:** How you checked it, and what you fixed.
```

## 2026-11-10: College-town housing dashboard

- **Asked:** "Read AGENTS.md and docs/data_description_sheet.md first.\
\
I'm working on Part 1 of my college-town home sales website assignment. Build a clean, modern, responsive housing dashboard using the provided dataset.\
\
Requirements:\
1\. Replace the placeholder index.html page.\
2\. Display total home sales and median sale prices.\
3\. Create a bar chart comparing median sale prices across cities.\
4\. Add a dropdown to filter the dashboard by city.\
5\. Calculate all statistics from the actual dataset, not invented numbers.\
6\. Exclude sales below $10,000 from price statistics and explain this rule on the website.\
7\. Use HTML, CSS, and JavaScript compatible with the existing GitHub Pages workflow.\
8\. Do not modify the original dataset files in data/.\
9\. Document this session in AGENT_LOG.md.\
\
Implement the changes and test the website. Summarize what you changed. Do not merge directly into main; I want to review the changes first."
- **Agent produced:** Replaced the placeholder with a responsive dashboard. It loads the canonical CSV in the browser, computes sales counts and city and overall medians, and renders a city filter and median-price bar chart. It explains the $10,000 price cutoff.
- **Checked or changed:** Read both required project documents and confirmed the CSV header. Independently calculated 35,442 total sales, 35,402 sales at or above $10,000, 18 cities, and an overall median of $410,000; the page JavaScript parses successfully. The dataset description uses a $1,000 floor for its published medians, while this page follows the assignment’s $10,000 threshold. No dataset file was edited. The dashboard has not yet been checked in a browser.
