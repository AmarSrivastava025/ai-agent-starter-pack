# START HERE: your AI Agent Starter Pack

You have five helpers in this folder. Each one solves one problem: not knowing what to sell, not picturing your customer, having no clear offer, a profile that does not say who you help, and not knowing what to post.
They work in Claude Code, inside VS Code. Setup takes about 30 minutes, once.

## What you need
- A Windows or Mac computer and an internet connection.
- **VS Code.** It is free.
- **A Claude Pro subscription.** This is the one paid item. It includes Claude Code. Check the current price on claude.ai, because prices change.

## Set up (once)
1. **Install VS Code.** Go to code.visualstudio.com, download it and install it. You need version 1.94 or newer.
2. **Get Claude Pro.** Go to claude.ai, sign in or create an account, and choose the Pro plan.
3. **Install the Claude Code extension.** Open VS Code. Press Ctrl+Shift+X (on a Mac: Cmd+Shift+X). In the search box type `Claude Code`. Choose the one from Anthropic and click Install.
4. **Unzip this pack.** Right-click the ZIP file and choose Extract All (on a Mac, double-click it). You get a folder called `AI-Agent-Starter-Pack`. Put it somewhere easy to find, for example in Documents.
5. **Open the folder in VS Code.** In VS Code choose File, then Open Folder, and pick `AI-Agent-Starter-Pack`. If VS Code asks "Do you trust the authors", choose Yes.
6. **Open Claude Code.** Press Ctrl+Shift+P (Mac: Cmd+Shift+P), type `Claude Code`, and choose "Open in New Tab".
7. **Sign in.** The first time, click Sign in. Your browser opens. Log in with your Claude account and allow it.
   If the sign-in screen does not appear, press Ctrl+Shift+P, type `Developer: Reload Window`, and press Enter.

## Tell it who you are (once, 15 minutes)
Open `profile/profile.md` in VS Code and fill in what you can. Short answers are fine. If you do not know a part yet, leave it empty: the agents will help you find it.
Then open `profile/voice-samples.md` and paste 3 to 5 things you have really written (a post, a message, an email). The agents use them so that what they write sounds like you.

## Use your agents
In the Claude Code box, type the name of an agent, starting with `/`, and press Enter. Do them in this order:

| Order | Type this | What it does |
|---|---|---|
| 1 | `/niche-finder` | Interviews you and names the niche to test first. |
| 2 | `/ideal-customer-interviewer` | Helps you picture one real customer and what to ask them. |
| 3 | `/offer-builder` | Writes your one-page offer. |
| 4 | `/profile-optimizer` | Rewrites your LinkedIn or Instagram profile text. |
| 5 | `/post-writer` | Turns one real experience into a post. |

Each agent asks you one question at a time. Answer in your own words. Short answers are fine.
Each one saves its result in the `outputs` folder, and tells you the file name and what to do next.
Claude may ask permission to create a file in this folder. Allow it for this folder.

## Good to know
- Nothing is posted or changed anywhere for you. You copy what you like and use it yourself.
- Your answers are saved as files on your own computer, in this folder.
- Please do not type in private details about other people, or anything confidential from your employer.
- The agents are helpers for education and practice. They do not promise money, clients or income.
- Claude Pro has daily usage limits. If it tells you to wait, come back later.
- The `examples` folder shows what the results look like, for a made-up person.
- The folder `guides` has a short page for each agent.
