---
name: ideal-customer-interviewer
description: Use when the person has a niche but cannot picture the one person they help. Interviews them and builds the ideal customer, with questions to ask a real person.
---

# Ideal Customer Interviewer

**The problem it solves:** "I know roughly who I help, but I cannot picture one real person, so I do not know what to say to them."

## Before you start
1. Follow the rules in `CLAUDE.md`. Read `profile/profile.md`.
2. The "My niche" part must be filled in. If it is empty, say: "I need your niche first. Run /niche-finder, then come back." Stop there.
3. Say in one line what you are about to do: "I will ask you about one real person who fits your niche, then write down who they are and what to ask them."

## The interview
Ask ONE question at a time and wait. Ask about ONE real person the speaker knows or has helped, not an imagined average person. If they have nobody in mind, ask them to think of the nearest real person (a colleague, a friend, a former client). Do not make anyone up.
1. Who is this person? (job, situation, age if it matters)
2. What is the problem they keep coming back to? Use their words if they said them.
3. What have they already tried to fix it?
4. What stopped them, or what did not work?
5. What would they want to be different? What would a good result look like for them?
6. Where do they spend time online or in real life?
7. What do they worry about when they think of paying someone for help?

## Check the fit first
Before you write the result, compare the person they described with the niche in the profile. If they do not match (for example the niche is about managers and the person is a job-seeker), say so in one line and ask which one to use: the niche in the profile, or this person. Do not carry on until they answer.

## The result
Use only what the person told you. Mark clearly any line that is your guess with "(to check with a real person)".

**A. My ideal customer.** Who they are, what keeps them stuck, what they have tried, what they want, where they spend time, what worries them. Short lines.

**B. Questions to ask a real person.** Write a friendly script for a 15-minute conversation:
- A 30-second opening that is NOT a sales pitch.
- 10 open questions about their situation, about things that really happened, not opinions.
- 3 questions about what they have already tried.
- A polite closing.
Do not ask them to buy anything and do not mention a price.

**C. One thing to do this week.** Book ONE conversation with a real person like this. Say it in one line.

## Save and finish
- Save everything in `outputs/ideal-customer-interviewer/<today's date>-run.md`.
- Ask: "May I save your ideal customer in your profile?" Only after a yes, fill in the "My ideal customer" part of `profile/profile.md`.
- Finish with the file name in one line, and: "Next: run /offer-builder. Better still, have your real conversation first and bring what you heard."

## Do not
- Do not invent a person, quotes, numbers or results.
- Do not call a guess a fact.
