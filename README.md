# Bearings Skills

A small collection of the Claude skills I actually use in my work, shared from [Bearings](https://ourbearings.substack.com). The first one is the hypothesis review.

## Hypothesis Review Sparring Partner

Most product reviews reward the activity instead of the outcome. They grade a polished readout when the only thing that matters is whether the bet underneath is right. My teams stopped running them. In their place we run a hypothesis review, and this is the skill we use to prepare for one.

It is not a template. A template is passive: it waits to be filled and never pushes back, so it collects confident narratives in tidy boxes. This is a conversation that argues with you. You hand it a rough idea, a Slack message, half a thought, and it comes back with the hardest questions a sharp cross-functional room would ask, before you are in the room.

Underneath it are the six things you have to be able to answer to think clearly about any bet: a problem statement sharp enough to say in one breath, real evidence the problem exists, a named hypothesis with an honest confidence level, a success metric that ladders all the way to a business outcome, a cheap way to learn you are wrong, and real alternatives considered. On top of that sits the Council of Five, five deliberately different lenses (Evidence and Research, Customer and Design, GTM and Commerce, Architecture and Engineering, and the Pragmatist who owns the bet) that each catch a different kind of failure. Two house rules run through all of it: evidence before opinion, and stopping is a celebrated outcome.

## Install it

### In Cowork (claude.ai)

Open **Customize** in the sidebar, choose **Plugins**, then **Add marketplace**, and paste this repository's URL (`https://github.com/cwinf/bearings-skills`). The plugin then appears under **Discover**. Select it and click **Install**. It is saved to your account and also available in chat and Claude Code.

### In Claude Code

```bash
claude plugin marketplace add cwinf/bearings-skills
claude plugin install hypothesis-review@bearings-skills
```

Once installed, just describe a bet you are pressure-testing, or ask Claude to "pressure test this hypothesis" or "poke holes in this before my review," and the skill takes over.

## What's inside

```
bearings-skills/
├── .claude-plugin/
│   └── marketplace.json
└── plugins/
    └── hypothesis-review/
        ├── .claude-plugin/
        │   └── plugin.json
        └── skills/
            └── hypothesis-review-sparring-partner/
                └── SKILL.md
```

## License

Shared for anyone to use and adapt. If you build on it, a note back to Bearings is appreciated, not required.
