---
name: ai-browser-walkthrough
description: 'Use an AI agent driving a real browser to attempt tasks on a live site or prototype and report where it got stuck, before testing with people. Use when someone wants a quick automated usability pass, a keyboard only walkthrough, a pre test of a flow, or to check a prototype works end to end with Claude in Chrome, Playwright or a similar browser tool.'
---

# AI browser walkthrough

An AI agent can't tell you what people feel, but it can try your flow in a real browser in minutes and show you where it breaks. Use it before a usability test, never instead of one.

## Steps

1. **Write the tasks as scenarios**, exactly as you would for people ("Find out if you could pay less for car insurance"), plus success criteria.
2. **Run each task in a real browser** (Claude in Chrome, Playwright, or similar). For each step record: what the agent looked for, what it clicked or typed, what happened, and a screenshot at every decision point.
3. **Run it three ways:**
   - As a first time visitor, using only what's visible on screen
   - Keyboard only: Tab, Shift Tab, Enter, Space, arrows and Escape, noting where focus is lost or invisible
   - On a phone sized window (about 390 pixels wide)
4. **Flag friction:** steps that needed guessing, labels that didn't match the goal, dead ends, errors, slow loads, missing states (empty, loading, error), and anything that only worked by luck.
5. **Check the basics on each page:** headings, labels on form fields, alt text, contrast on key text, and console errors.

## Output

Per task: success or failure, the step by step path with screenshots, and friction points ranked by severity. Then a list of hypotheses to test with real people.

## Be honest about the limits

The agent reads pages differently from people: it may find things a person wouldn't and miss confusion a person would feel. Label every finding "AI walkthrough", and never report it as user research.

## Don't

- Don't run it on production with real accounts, payments or personal data. Use test accounts and sample data.
