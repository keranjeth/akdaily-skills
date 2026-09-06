# AK Daily Skills

A personal Claude Code marketplace for reusable AI skills.

## Available plugin

### $100M Offers

An operational offer-development skill built from the working frameworks in Alex Hormozi's *$100M Offers*. It helps Claude build, audit, package, price, strengthen, and name offers using a structured workflow rather than treating the book as a general summary.

The plugin includes the main skill router plus a decision cheatsheet, glossary, routing patterns, and source/fidelity notes.

## Install in Claude Code

Add this repository as a marketplace:

```text
/plugin marketplace add keranjeth/akdaily-skills
```

Then install the plugin:

```text
/plugin install 100m-offers@akdaily-skills
```

Then try:

```text
Use the $100M Offers framework to audit this offer. Diagnose it before rewriting it:
[paste your offer]
```

## Repository structure

```text
akdaily-skills/
├── .claude-plugin/
│   └── marketplace.json
└── plugins/
    └── 100m-offers/
        ├── .claude-plugin/
        │   └── plugin.json
        ├── README.md
        └── skills/
            └── 100m-offers/
                ├── SKILL.md
                ├── cheatsheet.md
                ├── glossary.md
                ├── patterns.md
                └── sources.md
```

## Important: private repository

This repository is currently private. Claude Code must be authenticated to GitHub with access to `keranjeth/akdaily-skills` before it can add this marketplace. If Claude Code cannot access private GitHub repositories in your setup, make the repository public before installing it.

## Source note

The plugin contains structured working notes and workflows derived from a user-provided copy of the book. It does not include the original PDF.
