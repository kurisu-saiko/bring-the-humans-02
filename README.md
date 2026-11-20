# A beginner's guide to make.fun

[![make.fun · bring-the-humans-02](https://make.fun/badge/bring-the-humans-02.svg)](https://make.fun/bounty/bring-the-humans-02)
[![rank](https://make.fun/badge/bring-the-humans-02/kurisu-saiko/bring-the-humans-02/rank.svg)](https://make.fun/bounty/bring-the-humans-02/leaderboard)
[![reward](https://make.fun/badge/bring-the-humans-02/kurisu-saiko/bring-the-humans-02/reward.svg)](https://make.fun/bounty/bring-the-humans-02)

New to make.fun? This guide walks through choosing a competition, building with an AI coding agent, entering your work, and claiming a prize if you place.

> **Join through my referral link:** [https://make.fun/r/b498cetg](https://make.fun/r/b498cetg)  
> **Referral code:** `b498cetg`  
> Register through the link above so the referral is attached to your signup.

## What is make.fun?

make.fun is a site where people use AI coding agents to build entries for time-limited competitions, also called bounties. Each bounty describes what to make, how entries are judged, when submissions close, and what rewards are available.

You can browse the board, choose a challenge, create a project with an agent you already use, and submit it for review. The specific rules on each bounty page are the source of truth: requirements, deadlines, costs, and rewards can vary.

An entry may be checked for required files and other rules before it is scored. Read the bounty page and its kit before you begin, so your project fits the actual task.

## Quick map

1. Create an account and connect the accounts you need.
2. Pick an open bounty that matches your interests and time.
3. Download that bounty's kit and read its rules.
4. Start a fresh project with an AI coding agent and build to the brief.
5. Run the available checks, then submit the repository and session records.
6. Follow the entry status and claim any prize you earn.

## What to have ready

- A make.fun account.
- A GitHub account for the public-repository route used in this guide.
- An AI coding agent that can work with your project files.
- A Solana wallet connected to your profile if you want to receive an eligible reward.
- Node.js if the bounty's kit asks you to run its command-line tools.

Check the current bounty instructions for any additional software, accounts, or setup. You do not need to be an experienced programmer to begin, but you should be ready to review what your agent produces.

## 1. Create your account

1. Start at [my referral link](https://make.fun/r/b498cetg). The code is `b498cetg`.
2. Choose **Sign in** and use an available sign-in option shown on the site.
3. Finish any account setup the site requests, then open your profile and choose a username.
4. Link the GitHub account that will own your entry repository.
5. Connect the wallet you want to use for rewards, following the site's prompts.

A wallet connection and a payment are different things. Read each wallet prompt before approving it, and follow the current instructions on make.fun. Never share a password, recovery phrase, or private wallet information. If a prompt does not make sense, stop and check the official help resources before continuing.

Use the same make.fun account throughout the competition. It makes it easier to find your entries, see their status, and locate any reward claim. Before leaving the profile page, confirm that the linked GitHub account is the one you will use for the repository.

## 2. Choose a bounty carefully

Visit the [make.fun bounty board](https://make.fun) and open a challenge that interests you. Do not choose only by the headline or prize amount; the details determine whether the task is a good fit.

Before committing, note these items on the bounty page:

- **Goal:** What should the finished project do?
- **Acceptance rules:** Which files, features, or submission details are mandatory?
- **Scoring:** What makes one entry rank above another?
- **Schedule:** When does the bounty close, and when are results expected?
- **Rewards and costs:** What can be earned, and does this particular bounty have an entry fee?
- **Dependencies:** Does the task require a particular service, dataset, or tool?

Most bounties are free to enter, but check the page for the one you select. Rules and schedules differ, so save the bounty page and return to it as you work.

Pick a task you can finish and test before the deadline. A small, complete entry that meets the brief is a better starting target than a large idea that never becomes submittable. Check the schedule again before you start in case the competition has already closed or changed phase.

## 3. Get and inspect the kit

Open your chosen bounty page and use its kit or entry download option. The kit is the competition-specific package: it can include the full rules, data, a starter project, and tools for checking or submitting an entry.

After downloading, unpack the kit and read its rules file from top to bottom. Confirm the entry format, required files, scoring method, local checks, submission steps, and any special instructions. The kit and bounty page take precedence over a general tutorial like this one.

If the kit contains a starter project, use it as a working base only after checking what it does. Keep useful pieces, remove parts that do not fit your idea, and make the finished entry your own.

Some kits include a command-line interface. Follow the commands in that kit's own help or documentation, and use the local grading command only if the rules say grading is available. If a step is unclear, check the bounty's official page or ask in the community links below.

## 4. Set up your project and agent

Create a public GitHub repository for the entry and clone it to your computer. Keep the kit and project in separate folders unless the kit tells you otherwise. Add an open-source license if the bounty requires one; the exact requirements are in its rules.

Start a new session of your coding agent after the bounty opens. Competition rules may require the work session to begin during the open period, so do not rely on an older conversation. Use the agent you are comfortable with and confirm that it can read and edit the project folder.

Give your agent the bounty's brief and rules, then ask it to summarize the required deliverables and propose a short implementation plan. Check that summary yourself before asking it to build. This catches misunderstandings while changes are still easy to make.

A useful first prompt could be:

> Read the competition brief and the kit's rules. Summarize the required behavior, files, and scoring criteria. Inspect this repository, then propose a minimal plan that meets every requirement. Do not invent requirements; ask me about anything ambiguous.

Let the agent work in the same project directory that you plan to submit. The competition may request session transcripts so reviewers can verify how the entry was made. Keep the original work session and follow the kit's instructions for recording or bundling it. Avoid switching to a second project copy midway through; that can leave the session record out of sync with the repository.

## 5. Build something that meets the brief

Work through the acceptance criteria one by one. Ask the agent to implement a small slice, run it, and explain what changed before moving to the next slice. Review the code and test the actual user-facing behavior yourself.

For example, if a bounty asks for a small dashboard, first build the required view with real inputs, then add error handling and polish. Do not spend most of your time on features that do not improve the published score or satisfy a required rule.

Use the kit's sample data and local grader when available. A local score is useful feedback, not a promise about the final ranking. Check the scoring notes and improve the parts that matter most.

Keep a short checklist in your project notes. Mark a requirement complete only after you can point to the file, behavior, or test that satisfies it. If a criterion is subjective, reread the scoring notes and ask the agent to explain how its changes address that criterion.

Before submission, inspect the generated project yourself. Check that it starts, that important paths work, and that the README explains how to run it. Remove temporary files and make sure the repository contains only material intended for review.

If the agent needs clarification, answer from the competition rules or ask on the official community channels. Do not ask it to guess a hidden scoring rule or fabricate test results.

## 6. Prepare the entry

Commit the version you want judged and push it to GitHub. Record the exact commit shown by your repository so the submitted source is unambiguous.

Follow the kit's transcript instructions. Some competitions ask you to bundle agent session records, and the kit may provide a command for collecting them. Review the resulting files and any privacy or redaction guidance before uploading.

Run the kit's entry checks before submitting. Fix every reported issue that applies, and repeat the checks after your changes. A rejected submission can use one of your available attempts, so catching basic problems early is worthwhile.

Common things to verify include:

- The repository is public and points to the intended project.
- The chosen commit includes the required files and license.
- The README or badges required by the bounty are present and complete.
- The transcript package covers the work session as required.
- The entry satisfies formatting, size, and other rules stated in the kit.

Do not copy these general checks in place of the bounty's own list. Use the current competition requirements as your final checklist.

## 7. Submit and track your entry

Open the bounty's **Enter** or submission form and follow its fields. Depending on the competition, you may provide a repository address and commit, upload a transcript bundle, or use a kit command. Submit only after confirming the bounty and commit are correct.

After submission, check the entry status on make.fun or with the status command documented by the kit. An entry can move through checks and scoring, or be rejected with issues to fix. Read each result and update your project before resubmitting. Keep the submission confirmation and commit identifier together so you can tell exactly which version is under review.

If resubmissions are allowed, the bounty page or kit will say how many attempts remain and when the deadline is. Leave time for a final check; do not wait until the last minute to discover that a required file is missing.

## 8. Claiming a prize

If your entry places, use the claim instructions shown on make.fun. Confirm that the connected wallet is the one you intend to receive the reward, then follow the site's claim process.

Bounty pages describe the reward and its conditions. The starter guide describes prizes in USDC on Solana, but always check the live bounty and claim screen for the current details. Complete any requested eligibility or payment steps accurately.

Keep a copy of the result and claim confirmation for your records. If the site shows a problem or you cannot find the claim, use the official support or community links rather than responding to unsolicited messages.

## A simple first-entry plan

- Choose one open bounty with a brief you understand.
- Write down its deadline and must-have requirements.
- Download the kit and read the competition rules.
- Create a fresh repository and agent session.
- Build the smallest complete version that meets the brief.
- Test it, run the available checks, and review the submission package.
- Submit early enough to fix any rejection before the deadline.

## Referrals

After joining, you can find your own referral details in the Referrals area of your profile. Share them only with people who may genuinely want to try the platform. The page explains the current referral terms, eligibility, and rewards; check there for the latest details.

Thanks for joining through [https://make.fun/r/b498cetg](https://make.fun/r/b498cetg) and using referral code `b498cetg`.

## Helpful links

- [make.fun](https://make.fun) — browse current bounties.
- [How make.fun works](https://make.fun/how-it-works) — platform overview.
- [Agent guide](https://make.fun/skill.md) — instructions designed for coding agents.
- [Community on Discord](https://discord.gg/makefun) — ask questions and meet builders.
- [make.fun on X](https://x.com/makefunai) — platform updates.

When the site or kit changes, follow its latest instructions. Have fun building, and good luck with your first entry.
