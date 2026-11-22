---
name: profile-optimizer
description: Use when the person's LinkedIn or Instagram profile does not say who they help. Reads the profile text they paste and rewrites it so the right person understands them in a few seconds.
---

# Profile Optimizer

**The problem it solves:** "People visit my profile and still cannot tell what I do or who I help."

## Before you start
1. Follow the rules in `CLAUDE.md`. Read `profile/profile.md`.
2. The niche and the ideal customer should be filled in. If not, suggest /niche-finder or /ideal-customer-interviewer first, or ask the person to tell you in two lines who they help and with what problem, and use only that.
3. Say in one line what you are about to do: "I will read your current profile text and rewrite it so a stranger sees who you help in a few seconds."

## What to ask for
Ask ONE question at a time and wait.
1. Which platform is this for: LinkedIn or Instagram?
2. Please paste your current text. For LinkedIn: your headline and your About section. For Instagram: your name line and your bio. (If it is empty, say so. That is fine.)
3. Check the length limit shown on the screen where you edit it, and tell me. (Limits change, so do not guess them.)
4. What do you want a visitor to do after reading it? For example: send a message, book a call, read a post.

## The result
Use only facts the person has given you. Never add a degree, a client name, an award, a number or a result they did not tell you.

**A. The 5-second test.** Read the current text as a stranger would. In two lines, say what a stranger understands about who they help, and what is unclear.

**B. Three rewrites** of the headline or name line and bio, each different in style (plain, warm, direct), each within the length limit the person gave. Each says who they help and with what problem.

**C. A rewritten About section (LinkedIn) or a short extended bio (Instagram)** in the person's own voice (read `profile/voice-samples.md`). Short paragraphs. First line about the reader's problem, not about the person.

**D. A short checklist of what to change** on the profile, in the order the person should do it. Photo and links only if the person mentioned them.

## Save and finish
- Save in `outputs/profile-optimizer/<today's date>-<platform>.md`.
- Tell the person: "Nothing has been changed on your profile. Copy the version you like and paste it yourself."
- Ask: "May I note in your profile which version you chose?" Only after a yes, update the "My profiles online" part of `profile/profile.md`.
- Finish with the file name in one line, and: "Next: run /post-writer."

## Do not
- Do not state that something is true for every reader because it was true for one person. Ask the reader a question, or start with "If you ...".
- Do not promise income, clients or results in the profile text.
- Do not claim anything the person did not tell you.
