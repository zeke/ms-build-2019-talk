# Building thriving open source communities with GitHub

A talk by [@nerdneha](https://github.com/nerdneha) and [@zeke](https://github.com/zeke).

MS Build 2019, Seattle

https://mybuild.techcommunity.microsoft.com/sessions/77051

We used this README to prepare an outline for our talk, then made a [slide deck](https://docs.google.com/presentation/d/1zZ2GYFAWiAYFC_9OqaWqDViVqDKfVijH24C9A6Wkk-Q/edit?usp=sharing) using Google Slides, the results of which are captured in [slides.pdf](slides.pdf)

---

:point_down: Notes / Talk Outline

## Overview

- Desktop Project (Neha)
- Electron Project (Zeke)
- Close your eyes, part 1 (Neha)
- Beginning
    - GitHub Flow (Zeke)
    - Open Source Basics (Neha)
- Growing
    - Shared Ownership (Zeke)
    - Diversity (Neha)
- Automating
    - Marketplace (Neha)
    - Roll your own (Zeke)

- Close your eyes, part 2 (Neha)

## Topics

### Desktop Project (Neha)

- I'm Neha. Lowering barriers / Empowering Marginalized / Agile that works 
- What is Desktop?
- Why does it exist. "quintessential cross-platform app"
- Basic characteristics: language, geodistribution and composition of the team, cross-platformness, project duration. Eng / QA / support.
- History: Transitioning from a private repo to an open source community
- Six months ago vs Now
- Stats: user, OSS contributors in last x, etc
- Personal perspective/goals: find the balance between growing the product and growing the community without being reliant on any individuals or scaling our team. i.e. "This will work as long as so-and-so is still around". balancing burnout, progress, and company support
- Consumer of electron and personal fan

### Electron Project (Zeke)

- I'm Zeke. Open Source / Community Building / Automation / Node.js <3
- I use Desktop!
- What is Electron?
- Apps running on Electron
- Companies using Electron
- On the docs team now! (private for now)
- Personal perspective/goals: be able to disappear

### Close your eyes, part 1 (Neha)

Close your eyes. Imagine what your team or your project to look like in six months. Imagine the biggest barriers to getting there. Write it down! 

### GitHub Flow (Zeke)

- Happens entirely on GitHub
- Create a branch
- Add commits
- Open a Pull Request
- Discuss and review your code
- Deploy
- Merge

### Open Source Basics (Neha)

- Community Checklist
- README (most important) - many people will decide whether to use your project based on the README. Tell people what the project needs!
- CoC
- CONTRIBUTING.md - another opportunity to tell people what the project needs.
- License
- Issue templates and PR templates
- `good-first-issue` labels: https://www.firsttimersonly.com
- Open issues before PRs (conversation before implementation)
- Draft PRs (new feature)
- Pinned issues (beta) to surface priorities

### Beginning Conclusion / Growing Intro
Your goal is to grow. 
What is their goal? Why are they interested in your project?

I experience this as a manager all the time. My job is to grow the business and the product but I can't do that effectively until I take an interest in people. 

Our job as an open source repository is to create a construct so that people can grow while we are growing and find that happy medium. 

These tools are about HOW we can do that. 

### Shared Ownership (Zeke)

- move your projects to orgs (no individual person owns the project)
- invite contributors and give them generous permissions
- Use branch protection for safety
- Use CODEOWNERS for safety
- all-contributors
- Give credit in the changelogs (VSCode changelog is a good example)
- 

### Diversity and Inclusion (Neha)

Diversity:
As your project grows, it gets easier and easier to reinforce the status quo. 
This is about taking a step back and understanding the composition of your team and how that affects who you're able to attract.

Diversity: experience, ability, background, location, language, cultural upbringing, tenure, age. 
1. People on the team
2. Users you interview
3. Open Source contributions


Inclusion:
If you feed a leaky pipeline, you're gonna get the same thing at the other end. What can you do as a project to be more inclusive?
 - Enforcing the Code of Conduct
     - Having a public track record of addressing toxic issues in an empathetic but firm way
     - Having allies to step in so the emotional labor is distributed
 - Personal touch
     - Seeing people respond and be helpful encourages newcomers
     - Don't assume gender
     - Ablelist langauge
     - Attribute credit
 - Offer mentorship
     - Ambassadors, pairs
     - First time contributor badge
 - Pay / reward
 - Get Feedback

### Marketplace (Neha)

"write less code; click fewer buttons" - @chobberoni

- Add CI (Travis, Circle, Azure Pipelines, GitHub Actions
- Review apps (for web apps): Open a PR, get a staging instance. No matter who you are. (supported by Heroko, Zeit Now, Netlify, Azure)
- welcome-bot (first issue on repo, first PR on repo, first landed PR on repo) - great starting point until you have the bandwidth for more human touch.
- accesslint
- [twitter-together](https://github.com/marketplace/actions/twitter-together)
- LGTM
- Codacy
- Dependabot
- Semantic Pull Requests

## Roll your own (Zeke)
- Webhooks - https://github.com/octokit/webhooks.js/blob/master/lib/webhook-names.json
- Probot
- GitHub Actions
    - arbitrary code execution
    - respond to any webhook event
    - run on a schedule
    - Secrets API
    - Docker
    - explicit: The configuration is right in the repo

### Engaging Users in different ways

- lead with a thanks / recognize effort
- "lean into the pain" / "kill with kindness"
- twitter engagement SOMETIMES NOT ALWAYS
- electron has a beta program

### Diversity: How to do better

- End on a Challenge
- This can happen at any step of your process, it's not a "once we make it" kind of thing
- Close your eyes
- What genders do you see there? What backgrounds? What ages? What roles?
- What are the next three things you wanna do?

### Audience: What's next?

Close your eyes

Think about the next steps in your open source journery.

- Are you going to reach out to someone new?
- Are you going to add documentation?
- Are you thinking about ways to improve your communication with OSS contributors?
- Are you focusing on scaling?
- Are you ready to try some new tools to automate your workflows?

Now: Take out your phone or your notebook or your steno pad.

## Audience participation ideas

- close your eyes
- write something down
- tweet something with a hashtag
- talk to your neighbor - exchange contact information
- collective selfie
- extra credit activity
- What are the biggest challenges you might have open-sourcing a project?
- Prompt: What project would you like to open source? Find a partner and share.
- Prompt: What do you want your project to look like in three years?
- Prompt: what does shared ownership look like for you? 
- Prompt: Write down two tools you wanna check out

## Other topics and concepts

- geodistribution
- diversity
- BUS factor
- Onion skin. The more layers you peel off, the more you cry.
- If I do my job right, you never see it
- Jake replaced herself with a machine
- Cumulative list of tools and practices (see youtube video: https://youtu.be/WzghfjjjKvA?t=3064)
- https://github.com/desktop/desktop/blob/development/docs/process/what-is-desktop.md

Resources:

https://github.com/desktop/desktop/blob/development/docs/process/roadmap.md
https://github.com/customer-stories/jessfraz
https://www.firsttimersonly.com/
http://hood.ie/blog/welcoming-communities.html

> Use simple language (Hemingway can help). List all professions like “Design”, “Editorial”, “Documentation” instead of saying “Non-Coding”. Use gender-neutral language, prefer “them” and “they” over “him” and “she”. Avoid phrases like “Hey guys”. If you use Slack, you can configure slackbot to suggest alternatives, as we do in our Hoodie Chat. This is your chance to “set a tone” in your community. It helps to limit unfriendly, over-demanding and self-entitled requests from strangers.

## Semantic Release

- SemVer
- https://www.conventionalcommits.org - A specification for adding human and machine-readable meaning to commit messages
- https://github.com/semantic-release - Fully automated version management and package publishing
- https://github.com/conventional-changelog/standard-version - Automate versioning and CHANGELOG generation, with semver.org and conventionalcommits.org

drop a hint about upcoming permissions improvements at satellite

create an environment where different types of contributions are valued

1. make the person know you see them
2. give them feedback that is useful for your project and helps them understand why they should do something differently
3. when they get the thing merged, when should they expect to see this live in the app

being seen by a bot is not as meaningful as being seen by a human

managing burnout - managing a community can be exhausting. have cognizence of that fact and have a process around letting maintainers step down.