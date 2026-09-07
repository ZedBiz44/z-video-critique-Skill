# Z Video Critique Skill

This repository is the authoritative technical source for `z-video-critique`, a ZedBiz skill for independent creative review of complete playable videos.

## When to Use

The skill supports three related jobs:

- deciding whether a ZedBiz video is creatively ready;
- explaining the observable choices that may help a successful reference video work; and
- comparing a ZedBiz video with a reference without copying it.

It automatically chooses a Quick Review, Focused Review, or Full Review from the request and business importance. VAs do not need to learn special commands or fill out a form for ordinary reviews.

## Do Not Use

The skill does not create, edit, render, publish, or deliver videos. It does not authorize spending or release, and it does not certify technical, legal, rights, accessibility, or platform requirements that were not checked.

Use `z-video-production` for production work and `z-creative-asset-critique` for standalone thumbnails and still graphics.

The package contains no secrets and must not store passwords, tokens, private keys, or complete environment files. Human approval is required for spending, material creative-direction changes, client delivery, and publication.

## Package

- `SKILL.md` contains the trigger contract, core workflow, verdicts, boundaries, and completion checks.
- `references/video-checklists.md` contains detailed creative review prompts.
- `references/response-patterns.md` contains concise review formats.
- `references/production-handoff.md` defines the companion agreement with video production.
- `references/channel-and-platform-notes.md` contains evidence-safe channel guidance.
- `tests/` contains fresh-session trigger, readiness, correction, revision, and successful-reference acceptance tests.

## Validation

Run the ZedBiz AI Skill Developer validator against the repository:

```bash
python /path/to/z-ai-skill-developer-Skill/scripts/validate_skill.py --repository /path/to/z-video-critique-Skill
```

Before a broader rollout, install the exact committed package on one approved test agent, verify OpenClaw discovery, and run a fresh-session critique using a real playable approved video. Record the source commit, package checksum, deployment path, discovery output, test prompt, response, and result in GitHub.

## Source of Truth

GitHub contains the executable skill and change history. The ZedBiz Notion SOP explains how humans and agents should use the skill and links back to this repository; it is not a competing runtime copy.

