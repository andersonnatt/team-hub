# The New Dimension — Speaker Notes

Navigation: **Space/Right Arrow** = next | **Left Arrow** = back | **F** = fullscreen | **Click** right/left half

---

## Slide 1: Boot Sequence

**On screen:** Terminal initializing, "НОВИЙ ВИМІР" title reveal

**Talking points:**
- Let the boot sequence play out. Don't talk over it — let the aesthetic set the mood.
- Once the title appears, brief pause, then:
- "I built this presentation with AI, in about an hour. That's a small example of what we're going to talk about today."
- Press space when ready.

---

## Slide 2: You Got Promoted

**On screen:** "Вас підвищили." / You got promoted. You're not coders anymore. You're engineers, architects, leaders. Your team just got bigger.

**Talking points:**
- Let "Вас підвищили" land before continuing. Pause.
- "I mean this literally. The role changed. What makes you valuable changed. And it changed in your favor."
- "The things that make you great — your judgment, your architecture instincts, your domain knowledge — those are now the most important part of the job."
- "The part that used to take 80% of your time — writing the actual code — that's now something you can delegate."

---

## Slide 3: The Old Dimension

**On screen:** For 50 years, one constraint: humans write code. Better tools, same bottleneck. That constraint is gone.

**Talking points:**
- "Think about it — every tool we've ever adopted was about making *humans* write code faster or with fewer bugs."
- "TypeScript, React, better IDEs, linters, formatters — all of it assumes a human is typing the code."
- "That assumption is no longer true. And when a fundamental constraint disappears, everything built around it has to be rethought."

---

## Slide 4: The New Dimension

**On screen:** AI didn't make coding faster. It made coding a commodity. Things that didn't make business sense now do.

**Talking points:**
- "This is the key insight. It's not about speed. It's about what becomes *possible*."
- "Before: 'Should we build a custom architecture analysis tool?' Answer: no, that's months of work for a nice-to-have."
- "Now: 'Should we build it?' Answer: yes, it takes days and it'll pay for itself immediately."
- "That's the new dimension. Not doing the same things faster — doing things that didn't used to make sense."

---

## Slide 5: The Spectrum

**On screen:** Four stages: РУЧНИЙ (Manual) → AI-АСИСТЕНТ (AI-Assisted) → СИСТЕМНИЙ (Compound) → АВТОНОМНИЙ (Autonomous), with descriptions.

**Talking points:**
- Walk through each level briefly:
- **Manual:** "This is where most of us started. You ask ChatGPT a question, copy the answer, paste it in. AI helps with research."
- **AI-Assisted:** "This is where most teams are now. Cursor, Copilot, Claude Code — AI writes code *in* your project. But you review every single change. You're faster, but you're still the bottleneck."
- **Compound:** "This is the unlock. Instead of reviewing every output, you build a *system* — rules, skills, memory, verification hooks — that improves itself over time. Each task you do makes the next one easier."
- **Autonomous:** "This is the frontier. Defined workflows run without you. Automated verification catches issues before you see them. Deployments, monitoring, testing — automatic."
- "This isn't a judgment. It's a map. I just want you to know where you are and where the opportunity is."

---

## Slide 6: The Stats

**On screen:** Industry is moving right. 84% adoption, 41% AI-generated code, 4% GitHub commits from Claude Code. Most teams at AI-Assisted, unlock is Compound.

**Talking points:**
- "These numbers are from 2025-2026 industry data. They're moving fast."
- "84% — adoption is basically universal at this point."
- "41% — nearly half of all new code is AI-generated. Think about that."
- "4% of all public GitHub commits are from a single tool — Claude Code. They expect 20% by end of year."
- "Most teams are stuck at AI-Assisted. The teams pulling ahead are the ones who figured out the Compound stage."

---

## Slide 7: Discussion Pause #1

**On screen:** Where are you on this spectrum? Where do you want to be in 6 months?

**Talking points:**
- Open it up. Go around the room or let people volunteer.
- "No wrong answer here. I'm genuinely curious where you feel you are."
- Listen. Don't correct. This is about getting them to self-assess.
- If the room is quiet: "Be honest — when you use AI tools, do you review every single line it produces? That's AI-Assisted. Nothing wrong with it. But there's a level beyond it."
- Spend 3-5 minutes here. This is where buy-in starts.

---

## Slide 8: The Trap

**On screen:** Most teams adopted AI to move faster, then added review on every output. Moved the bottleneck from writing code to reviewing code. That "someone" is tireless and works at machine speed.

**Talking points:**
- "This is the trap I fell into myself. Four terminal panes open, AI writing code in all of them, and I'm the bottleneck trying to review it all."
- "You adopted AI to go faster. Then you added a human review layer on top of every AI output. You didn't eliminate work — you moved the bottleneck."
- "The AI produces at machine speed. You review at human speed. The math doesn't work."
- "The answer isn't 'stop reviewing.' The answer is 'stop reviewing *everything* and start building systems that verify for you.'"

---

## Slide 9: The Reframe

**On screen:** Stop thinking "AI assistant I supervise." Start thinking "engineer I lead." Set direction. Design verification. The code is your team's job now.

**Talking points:**
- "This is the mindset shift. It's the difference between being a senior dev who uses an AI tool, and being an engineering manager who leads an AI team."
- "Think about what a good engineering manager does. They don't write every line of code. They set direction, design the process, review where it matters, and improve the system when things break."
- "That's your new job. You got promoted."
- "The AI is your team. A very fast, very tireless team that doesn't get bored, doesn't context-switch, and doesn't skip tests at 5pm on a Friday."

---

## Slide 10: What Humans Do Now

**On screen:** Three things: Direction (what/why), Verification Design (design the system, don't be it), System Improvement (fix the system, not the output).

**Talking points:**
- **Direction:** "What to build and why. The AI can't decide your product strategy. It doesn't know your users, your market, your constraints. This is where your taste and judgment matter most."
- **Verification Design:** "This is the key one. Don't review code line by line. Design the *systems* that review code — rules, hooks, automated tests, acceptance criteria. Design the verification system. Don't *be* the verification system."
- **System Improvement:** "When something goes wrong, don't just fix the output and move on. Fix the system so that *category* of problem never happens again. Add a rule. Update a skill. Write a hook."
- "Everything else — the actual coding, the boilerplate, the implementation details — the AI handles it. And honestly, it handles it better than we do for most tasks."

---

## Slide 11: Proof

**On screen:** `$ ls ./built-with-ai/` — Altitude + Horizon, Roundtable Reviews, Pods.

**Talking points:**
- "Let me show you three things I built in the last few months. Solo. All three exist only because AI changed what's possible."
- **Altitude + Horizon:** "These are custom architecture analysis tools for GiftPal. They map every module, track dependencies, surface invariants, measure blast radius before you touch a file. Before AI, this is a team project spanning months. With AI, it took days. I would *never* have built these otherwise."
- **Roundtable Reviews:** "Every feature goes through a roundtable of 15 specialized AI agents. Security reviewer, performance reviewer, accessibility reviewer, QA, domain expert — they actually collaborate, share findings, and gate the work. No company in the world would assign 15 reviewers to every feature. But now it's free, so why wouldn't you?"
- **Pods:** "I needed to run multiple AI engineers working on the same codebase in parallel. So I built a desktop app to orchestrate them — git worktree isolation, session management, diff review. This tool literally has no reason to exist in a world without AI. That's the new dimension."

---

## Slide 12: Discussion Pause #2

**On screen:** Think about your current project. What would you build if staffing were free? What process would you add if it cost nothing?

**Talking points:**
- This is the most important discussion. Give it 5+ minutes.
- "Forget feasibility for a moment. If you had unlimited engineers who work 24/7 and never get tired — what would you build? What process would you add?"
- Prompt if needed: "What manual process do you hate? What review do you wish happened but nobody has time for? What tool would make your life easier but you'd never justify the dev time?"
- Write down what people say. These are your team's first AI projects.

---

## Slide 13: The Counterpart

**On screen:** Not a junior to babysit. A counterpart. Impact magnifier. Diff between micromanaging vs. leading.

**Talking points:**
- "The most common mistake: treating the AI like a junior developer. Giving it tiny, specific instructions. 'Write me a function that does X.' Then reviewing every line."
- "That's micromanagement. It works, but it doesn't scale."
- "The alternative: lead. 'Here's what we need to achieve. Here are the constraints. Here's how we'll know it's right. Build it.'"
- "Give it the what and why. Let it figure out the how. You'll be surprised how often it gets it right — and when it doesn't, that's a signal to improve your system, not to micromanage harder."

---

## Slide 14: The Compound Effect

**On screen:** The real unlock isn't speed — it's compounding. Bug fixes become rules, patterns become skills, preferences become memory. Half shipping, half improving.

**Talking points:**
- "This is the thing that separates AI-Assisted from Compound."
- "Every time you correct the AI, don't just fix the output. Teach the system. Add a rule so it never makes that mistake again."
- "Over time, bugs become rules, patterns become skills, your preferences become memory. The system gets smarter with every interaction."
- "The rule I follow: spend half your time shipping features, half improving the system. It feels wrong at first — feels like you're wasting time on infrastructure. But by week three, the compound effect kicks in. Tasks that took 20 minutes take 2."
- "The goal: never do the same manual correction twice."

---

## Slide 15: The Signal

**On screen:** Spotify (directing AI from phones), StrongDM ($1K/day/engineer on tokens), GitHub (Claude Code 4% → 20% of commits).

**Talking points:**
- "This isn't just me experimenting on a side project. This is happening at the biggest companies in the world."
- **Spotify:** "Their best engineers haven't written a line of code since December. They direct AI agents from their phones via Slack. They review and merge before arriving at the office. They shipped 50+ features this way."
- **StrongDM:** "They spend a thousand dollars per day per engineer on AI tokens. Their company rule — literally a rule — is 'code must not be written by humans. Code must not be reviewed by humans.' Their AI validates code against behavioral clones of Okta, Jira, Slack, and Google Docs."
- **GitHub:** "4% of all public commits on the planet come from one tool. By end of year, one in five commits. Think about what that means for the industry."
- "This isn't experimental. This is the new baseline. The question isn't whether this is happening — it's whether we're positioned for it."

---

## Slide 16: The Challenge

**On screen:** Two challenges, one week. At work: encode one workflow. At home: find something that wasn't possible before. Storybook factory example.

**Talking points:**
- "I want to leave you with two challenges."
- **At work:** "Pick one thing you do more than once a week. Something repetitive. Encode it — write the rules, the process, the acceptance criteria — and teach the AI to do it. Stop doing it manually. Even if it's small. The point is to start building the muscle."
- **At home:** "This one is more open-ended. Find something in your life that wasn't possible before AI. Not 'do something faster.' Something *new*."
- **The example:** "Here's mine. I built a storybook factory for my daughter. Every night, I give it a few words about her day — she went to the park, she played with her friend — and it writes a new chapter in an ongoing personalized story. Then it reads it aloud to her at bedtime. Every night. Personalized. Compounding. That's not 'write stories faster.' That thing didn't exist before."
- "That's the new dimension I want you to find. Not faster — *new*."
- "Bring both back next week. We'll share what everyone found."

---

## Slide 17: Open Discussion

**On screen:** "Давайте поговоримо." / Let's talk.

**Talking points:**
- Open the floor. Let it breathe.
- If people are quiet, seed with: "What's the biggest thing holding you back from using AI more?"
- Or: "What's something you heard today that surprised you?"
- Or: "What's the scariest part of this shift?"
- Let the conversation go where it goes. This is where the real buy-in happens.
- If the identity concern comes up ("will AI replace us"): "AI made the things that make you *you* more valuable, not less. It commoditized the part of the job that was already becoming commodity — the typing. Your taste, your judgment, your domain expertise — that's what matters now. And that's what's always made you great."

---

## Key Stats Reference (if needed during Q&A)

| Stat | Source Context |
|------|---------------|
| 84% AI tool adoption | Developer survey data 2025 |
| 41% AI-generated code | Industry analysis 2025-2026 |
| 46% distrust AI output | Developer survey 2025 |
| 4% → 20% GitHub commits | Claude Code trajectory 2026 |
| $1K/day/engineer | StrongDM AI token spend |
| 453 commits in 53 days | Article author's personal data |
| 50+ features shipped | Spotify AI-assisted development |
