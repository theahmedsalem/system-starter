# Starter template: set up your own system

This template gives your Claude two workflows to build your own system with:

- **Design a Workflow** turns a need that keeps coming back into a formal workflow. You build it together with Claude, in four checkpoints.
- **Continuous Improvement** turns every gap you find into a flag, so that your workflows get better each time you use them.

It also gives Claude a short set of working rules ([`CLAUDE.md`](CLAUDE.md)). These rules include clear writing (Simplified Technical English) and a visual first in every explanation. Everything else, you build yourself.

## Before you start

- You need a GitHub account.
- You need a Claude plan that includes Claude Code, for example Pro or Max.
- You need the Claude app on your iPhone, signed in to your Claude account.

## Set it up on your iPhone (about 10 minutes)

1. **Make your own copy.** Open the link to this template in Safari, signed in to GitHub. Tap *Use this template*, then *Create a new repository*. Give it a name, for example `my-system`. Choose **Private**. Tap *Create repository*. If you can't see *Use this template*, tap the **aA** button in the address bar, then *Request Desktop Website*.
2. **Give Claude access to your repo.** The first time you open the **Code** tab, the Claude app asks you to connect GitHub. Follow its steps. If GitHub asks which repositories Claude can use and you choose *Only select repositories*, add your new repo. If you connected GitHub before, see *If Claude can't reach your repo* below.
3. **Start a session.** In the Claude app, open the **Code** tab. Tap *New session*. Choose your new repo and the branch `main`. The first time, the app can ask you to set up an environment. Accept the default.
4. **Start.** Write: *Let's design my first workflow.* Claude asks what keeps coming back in your work, and builds the workflow with you.

Your copy does not stay linked to this template. It is yours alone.

## If Claude can't reach your repo

- Check that your GitHub account is connected to Claude.
- Check that Claude's GitHub app can use your repo. In Safari, open github.com. Tap your picture, then *Settings*, *Applications*, *Installed GitHub Apps*. Next to **Claude**, tap *Configure*. Under *Repository access*, add your repo, then tap *Save*.
- Then start a new session and try again.

## How it grows

- Every new workflow you need goes through **Design a Workflow**.
- When something does not work as you want, say so. Claude raises a flag and proposes the fix in exact words. Nothing in your workflows or rules changes until you confirm.
- You can change any rule in `CLAUDE.md` the same way, for example the writing style. Tell Claude what you want changed, and it goes through Continuous Improvement.
- Claude names your open flags at the start of each session. When you want to work through them, write: *Let's do an improvement session.*
- When you finish working, write: *I am done.* Claude closes the session and notes where the next session picks up.
- Often Claude saves your work to a branch of the session. Then, at the end of the session, Claude asks you to merge it into `main`. Do this before your next session:
  1. Open the link Claude gives you.
  2. If you see *Create pull request*, tap it. If a form opens, tap *Create pull request* again.
  3. Tap *Merge pull request*, then *Confirm merge*. Keep the default, *Create a merge commit*.
  4. Tap *Delete branch*.
- If you forget to merge, Claude asks you at the start of the next session.

## What is in the repo

| File | What it is |
|---|---|
| `README.md` | This guide |
| `CLAUDE.md` | The working rules Claude follows in your repo |
| `NEXT.md` | The index Claude reads at the start of every session |
| `improvement/flags.md` | The list of improvement flags, empty to start |
| `.claude/skills/design-workflow/SKILL.md` | The Design a Workflow workflow |
| `.claude/skills/continuous-improvement/SKILL.md` | The Continuous Improvement workflow |
