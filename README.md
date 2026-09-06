# AK Daily Skills

A personal Claude Code marketplace for reusable AI skills.

## Available plugin

### $100M Offers

An operational offer-development skill built from the working frameworks in Alex Hormozi's *$100M Offers*. It helps Claude build, audit, package, price, strengthen, and name offers using a structured workflow rather than treating the book as a general summary.

The plugin contains one skill with its own router, chapter reference notes, glossary, patterns, and cheatsheet.

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
                ├── sources.md
                └── chapters/
```

## Private repository note

This repository is currently private. Claude Code must have GitHub access to this repository for marketplace installation to work. If the machine/session cannot authenticate to this private repository, make the repository public or configure GitHub authentication before adding the marketplace.

## Source note

The plugin contains structured working notes and workflows derived from a user-provided copy of the book. It does not include the original PDF.
