# Swarmploy Brand Guidelines

**Status:** Draft  
**Version:** 0.1

Swarmploy is an open-source deployment platform based on Dokploy, extended with additional features and functionality.

These guidelines define the current direction of the Swarmploy brand. They are intentionally flexible and should evolve as the project develops.

---

## 1. Brand Foundation

### What is Swarmploy?

Swarmploy is a deployment platform for managing applications and infrastructure with Docker.

It is a fork of Dokploy that builds on the upstream project while developing its own features, identity, and direction.

### Brand idea

**Swarm + Deploy = Swarmploy**

The name directly communicates the project's relationship with Docker Swarm and deployment.

The brand should communicate:

- **Control**: Users understand and control their infrastructure.
- **Simplicity**: Complex deployment workflows should remain approachable.
- **Reliability**: Infrastructure software should feel predictable and dependable.
- **Openness**: The project is open source and transparent about how it works.
- **Extensibility**: Swarmploy should provide a foundation that can grow with its users.

### Brand personality

Swarmploy should feel:

- Technical, but approachable
- Confident, but not arrogant
- Practical, rather than overly polished
- Modern, without chasing trends
- Calm and reliable
- Developer-oriented
- Occasionally playful

Swarmploy should **not** feel:

- Corporate
- Overly sales-driven
- Buzzword-heavy
- Childish
- Aggressively "revolutionary"
- Dependent on jokes or mascots to communicate its identity

---

## 2. Brand Principles

### Open by default

Prefer transparency, inspectability, and user control.

Do not use marketing language to hide limitations or trade-offs.

### Show, don't exaggerate

Describe what Swarmploy actually does.

Prefer:

> Deploy and manage your applications with Docker Swarm.

Over:

> The revolutionary future of cloud-native infrastructure.

### Developer first

Technical users should be able to understand what is happening.

Documentation, interfaces, logs, errors, and CLI output should favor useful information over decorative copy.

### Simple does not mean simplistic

Swarmploy should make infrastructure easier to operate without hiding important controls or behavior.

### Upstream-aware, independently branded

Swarmploy originates from Dokploy, but its identity should be clearly distinguishable from Dokploy.

Do not imitate Dokploy's branding, logo, color system, or visual identity.

---

# 3. Naming

## Official name

**Swarmploy**

Use the capitalized name in normal prose.

Examples:

- "Swarmploy makes Docker deployments easier."
- "Install Swarmploy on your server."
- "The Swarmploy dashboard"

## Technical name

Use lowercase `swarmploy` where the surrounding technical convention requires it.

Examples:

- `swarmploy`
- `swarmploy` CLI
- `swarmploy` package
- `swarmploy` repository

Do not write:

- Swarm Ploy
- Swarm-Ploy
- Swarm-ploy
- SwarmPloy
- SWARMPLOY
- Swarmp
- SwarmPLOY
- SWARMPloy

or anything similar, unless a technical system explicitly requires uppercase text.

## Pronunciation

**SWARM-ploy**

Do not rely on pronunciation as part of the brand identity; it is primarily relevant when discussing the project verbally.

## Short forms

There is currently no official abbreviation for Swarmploy.

Avoid creating one unless the project establishes it intentionally.

---

# 4. Relationship to Dokploy

Swarmploy should describe itself accurately as a **Dokploy fork**.

Preferred wording:

> Swarmploy is an open-source fork of Dokploy with additional features and its own development direction.

Avoid implying that Swarmploy is an unrelated project.

At the same time, avoid presenting Swarmploy as an official Dokploy product, subsidiary, or affiliated service unless such a relationship actually exists.

### Attribution

Attribution requirements must follow the applicable upstream license and repository requirements.

Do not hard-code a specific attribution sentence into the brand guidelines unless the project's legal/licensing review establishes that it is required.

When attribution is useful but not legally required, keep it factual and concise.

For example:

> Swarmploy is based on Dokploy.

The exact wording can be adapted to the context.

---

# 5. Visual Identity

## Visual direction

The visual identity should be based around the concepts of:

- Swarms
- Nodes working together
- Containers
- Infrastructure
- Networks
- Deployment
- Modular systems
- Hexagonal geometry

Hexagons and honeycomb patterns may be used as supporting visual elements.

They should **not** dominate every surface.

The visual identity should still work without bee or honey imagery.

### Design principle

**Infrastructure first, metaphor second.**

A user should recognize Swarmploy as deployment/infrastructure software before noticing the swarm metaphor.

---

# 6. Logo

The final logo has not been established yet.

The following are design directions, not finalized logo specifications.

### Potential direction: Swarm / node mark

A geometric mark built from multiple connected or tessellating shapes could represent:

- Swarm nodes
- Containers
- Distributed infrastructure
- Collaboration
- Deployment

Hexagonal geometry is a natural candidate, but it is not mandatory.

### Potential direction: S-based mark

An abstract `S` integrated into a geometric or modular shape could provide a more distinctive standalone symbol.

### Mascot

A bee or swarm-related mascot may be used as optional community or decorative artwork.

If introduced, it should remain secondary to the primary logo.

The mascot must never be required to understand or identify Swarmploy.

---

# 7. Logo Usage

Once the final logo is established, provide at minimum:

- Primary logo
- Monochrome logo
- Symbol/mark
- Wordmark
- Horizontal lockup where useful
- Favicon/application icon

### General rules

Do:

- Maintain the logo's proportions.
- Preserve sufficient clear space.
- Use approved logo variants.
- Ensure sufficient contrast against the background.

Do not:

- Stretch or distort the logo.
- Rotate it without an intentional design reason.
- Add arbitrary effects.
- Recolor it outside approved variants.
- Place it on backgrounds where it becomes difficult to recognize.
- Recreate the logo manually using approximate shapes.

Exact minimum sizes and clear-space measurements should be defined once the final logo is designed.

---

# 8. Color

The following palette is a **proposed starting point**, not a finalized production color system.

## Primary colors

| Name | Hex | Purpose |
|---|---|---|
| Honey | `#FFB224` | Primary brand accent |
| Nectar | `#FFD76A` | Secondary highlight |
| Hive Ink | `#131518` | Dark backgrounds and primary dark surfaces |
| Comb White | `#FAF7F0` | Light backgrounds and high-contrast surfaces |

Honey should be used as an accent rather than covering entire interfaces.

## Semantic colors

Semantic colors must communicate state rather than branding.

| Purpose | Proposed color |
|---|---|
| Success | `#34D399` |
| Warning | `#F59E0B` |
| Error | `#EF4444` |
| Information | `#3B82F6` |
| Muted | `#9CA3AF` |

Semantic colors must remain visually distinguishable from the primary brand palette.

For example, **Warning should not rely on Honey alone**, because Honey is also a brand color.

### Accessibility

All production color combinations must be checked for sufficient contrast.

Do not assume that a color is accessible simply because it looks readable.

In particular:

- Do not use Honey as normal-sized body text on light backgrounds.
- Do not use low-contrast gray text for essential information.
- Do not use color as the only indicator of state.
- Error, warning, and success states should have additional textual or visual indicators where necessary.

The exact production palette should be validated against the actual UI before being considered final.

---

# 9. Typography

Typography should prioritize readability and availability across the project's interfaces.

### Recommended type system

| Purpose | Font | Weight |
|---|---|---|
| Display / major headings | Space Grotesk | Bold |
| Headings | Space Grotesk | Medium / Semibold |
| Body | Inter | Regular |
| UI | Inter | Regular / Medium |
| Code / CLI | JetBrains Mono | Regular / Medium |

These fonts are suitable as a proposed open-source-friendly type system, but the project may substitute them where platform constraints require it.

### Rules

- Keep body text highly readable.
- Use typography hierarchy consistently.
- Do not use display typography for large amounts of text.
- Use monospace typography for commands, code, logs, and technical identifiers.
- Avoid excessive font-weight variation.

---

# 10. Voice & Tone

Swarmploy communicates like a technically competent developer who values clarity.

## Core rules

### Be direct

Say what something does.

> Deploy your application to your swarm.

Not:

> Experience a revolutionary new way to orchestrate your applications.

### Be precise

Prefer concrete technical language.

> The deployment failed because the target node does not have enough available resources.

Not:

> Something went wrong with your deployment infrastructure.

### Be honest

If something is experimental, limited, unsupported, or potentially destructive, say so.

### Be concise

Remove words that do not add information.

### Be human

Swarmploy does not need to sound robotic or corporate.

A small amount of personality is encouraged.

---

# 11. Humor & Swarm Metaphors

Swarm-related language can be used as a secondary branding element.

Examples:

- swarm
- node
- hive
- worker
- deploy
- coordinated
- connected

However, technical clarity always takes priority.

Avoid forcing bee-related language into ordinary UI.

For example, prefer:

> Deployment failed

over:

> The swarm got stung 🐝

Humor is appropriate for:

- Community announcements
- Marketing illustrations
- Empty states
- Easter eggs
- Occasional documentation moments
- Mascot artwork

Humor is generally inappropriate for:

- Error messages
- Security warnings
- Destructive actions
- Critical infrastructure states
- Permission failures
- Data-loss warnings

---

# 12. Taglines

No tagline is currently considered official.

Potential phrases may be explored during branding work, but they should not be treated as established brand copy until intentionally selected.

Possible directions include:

- **Deploy as one.**
- **Deploy across your swarm.**
- **Simple deployment for Docker Swarm.**
- **Your swarm. Your infrastructure.**
- **Deploy. Manage. Scale.**

A tagline should describe the product rather than make unsupported claims.

Do not use multiple competing taglines throughout the product.

---

# 13. Product Interface

Swarmploy's UI should feel like infrastructure software first.

## General principles

- Prioritize information density without creating clutter.
- Make system state obvious.
- Make destructive operations explicit.
- Keep navigation predictable.
- Use consistent terminology.
- Prefer functional visual hierarchy over decoration.
- Avoid unnecessary animations.
- Use brand colors primarily for emphasis and interaction.

## Dark and light themes

Both themes should be treated as first-class interfaces if supported.

A dark theme may serve as the primary visual direction, but this should be determined by the actual product UX rather than the assumption that deployment users exclusively prefer dark interfaces.

The two themes should share the same:

- semantic colors
- spacing system
- component hierarchy
- interaction patterns
- typography

---

# 14. CLI

The CLI should be minimal, readable, and useful.

Example style:

    swarmploy v0.1.0

    Deploying application...
    ✓ Image pulled
    ✓ Service updated
    ✓ Deployment completed

Avoid decorative output that pushes useful information off the screen.

### CLI branding

The CLI may use:

- the Swarmploy mark
- approved brand colors
- subtle swarm/hexagonal elements
- restrained emoji where appropriate

Branding must never interfere with:

- scripting
- machine-readable output
- logs
- error messages
- accessibility
- terminal compatibility

Provide a non-decorative output mode where appropriate.

---

# 15. Documentation

Swarmploy documentation should prioritize discoverability and technical accuracy.

Documentation should:

- Use consistent terminology.
- Prefer examples over vague descriptions.
- Clearly distinguish supported functionality from experimental functionality.
- Explain prerequisites.
- Include commands users can actually run.
- Keep warnings close to the operation they describe.
- Avoid unnecessary marketing copy.

Documentation should not require users to understand the brand metaphor.

---

# 16. Errors & System Messages

Errors should help users resolve problems.

Use this structure where applicable:

1. **What happened**
2. **Why it happened**
3. **What the user can do**

Example:

> Deployment failed because the target node is missing the required image.
>
> Pull the image on the node and retry the deployment.

Avoid:

> The hive encountered an unexpected disturbance.

Technical clarity takes priority over personality.

---

# 17. GitHub & Open Source

Swarmploy's GitHub presence should feel like a serious open-source project.

Use:

- consistent project naming
- clear repository descriptions
- concise README introductions
- consistent issue/PR terminology
- recognizable Swarmploy branding
- accessible documentation
- accurate upstream attribution where required

Do not assume that a particular GitHub organization, domain, social account, or repository structure exists.

Those are project-management decisions, not brand requirements.

---

# 18. Community Branding

Community-created content may use Swarmploy branding to identify or discuss the project, subject to the project's eventual brand/trademark policy.

Examples include:

- Tutorials
- Blog posts
- Community projects
- Presentations
- Stickers
- Wallpapers
- Meetups
- Integrations

Until a formal trademark policy exists, do not make unsupported legal claims about what third parties may or may not do with Swarmploy branding.

If a formal trademark policy is introduced later, document it separately from these general brand guidelines.

---

# 19. Assets

The project may eventually maintain:

- Logo SVGs
- Wordmark SVGs
- Favicon
- Application icon
- Social/community artwork
- Dark/light logo variants
- Monochrome variants
- Brand color tokens
- Typography specifications
- CLI branding assets

Exact asset dimensions should be defined when the corresponding assets are actually created.

Do not create requirements for assets that the project does not currently use.

---

# 20. What This Guide Does Not Define

This document is a **brand guide**, not a:

- Technical architecture document
- Product specification
- Contribution guide
- Licensing document
- Trademark policy
- Marketing strategy
- Infrastructure guide
- UI component specification

Those concerns should be documented separately when necessary.

---

# 21. Current Brand Decisions

The following are intentionally left open until the project makes an explicit decision:

- Final logo
- Final wordmark
- Final color palette
- Official tagline
- Domain
- Social-media handles
- Mascot
- Formal trademark policy
- Exact brand asset repository
- Final typography implementation
- Final dark/light theme defaults

This prevents proposed ideas from accidentally becoming project requirements.

---

## Summary

Swarmploy should look and sound like **modern, capable open-source infrastructure software**.

Its identity can draw from swarms, nodes, and hexagonal geometry, but those metaphors should support the product rather than define it.

The central brand principles are:

> **Clear. Open. Practical. Deployable.**

Swarmploy should communicate what it does first, establish its personality second, and use visual metaphors only where they strengthen the experience.
