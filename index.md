# Personal Site Template

## Site structure

**Top navigation**

* Home
* Neurophysics
* Trust
* Implementation Science
* Bio
* Contact

---

## Suggested file map for GitHub Pages / Jekyll

```text
index.md
neurophysics.md
trust.md
implementation-science.md
bio.md
contact.md
assets/images/profile.jpg
assets/files/CV.pdf
```

Optional `_config.yml` navigation snippet:

```yaml
header_pages:
  - index.md
  - neurophysics.md
  - trust.md
  - implementation-science.md
  - bio.md
  - contact.md
```

---

# HOME

```markdown
---
layout: page
title: Home
permalink: /
---

<div style="display:flex; gap:2rem; align-items:flex-start; flex-wrap:wrap; margin-bottom:2rem;">
  <div style="flex:0 0 260px;">
    <img src="/assets/images/profile.jpg" alt="Scott Allen" style="width:100%; max-width:260px; border-radius:6px;">
  </div>
  <div style="flex:1 1 420px; min-width:280px;">

# Scott Allen

I study how neural systems drive human behavior. My work focuses on how distinct information representations in different learning systems produce distinct error modes, learning dynamics, and behavioral patterns. I use that framework to connect neural mechanisms to education, trust, and implementation in real-world settings.

**Current affiliation:** [Future of Learning Lab, Cornell University](#)

**Research areas:** Neurophysics · Trust Research · Implementation Science

[CV](#/assets/files/CV.pdf) · [Google Scholar](#) · [ORCID](#) · [GitHub](#) · [Email](mailto:your_email_here)

  </div>
</div>

## Research Overview

My research is organized around three connected programs.

### Neurophysics
I develop mechanistic models of human learning based on multiple neural systems that operate over different kinds of information structure. This work aims to identify the right state variables for connecting neural representations to cognition, behavior, and educational design.

[Read more about Neurophysics →](/neurophysics/)

### Trust Research
I study trust as a learning-dependent phenomenon rather than only a static judgment of personal attributes. This work examines how separate neural learning mechanisms contribute to the development, maintenance, and revision of trust in human relationships.

[Read more about Trust Research →](/trust/)

### Implementation Science
I examine how mechanistic models of learning can inform instructional design, educational change, and organizational implementation. This work focuses especially on the gap between sound design and successful real-world adoption.

[Read more about Implementation Science →](/implementation-science/)

## Selected Work

### Publications
- **[Publication title placeholder]**. *Journal placeholder*. [PDF](#) [DOI](#)
- **[Publication title placeholder]**. *Journal placeholder*. [PDF](#) [DOI](#)
- **[Publication title placeholder]**. *Journal placeholder*. [PDF](#) [DOI](#)

[Full publication list →](/bio/)

### Current Projects
- **Mechanistic models of learning:** [1–2 sentence placeholder]
- **Trust and neural information processing:** [1–2 sentence placeholder]
- **Implementation in education:** [1–2 sentence placeholder]

### News / Updates
- [Placeholder: invited talk, paper submission, award, preprint, conference presentation]
- [Placeholder: new manuscript, job market update, workshop, panel]
- [Placeholder: major collaboration or project milestone]
```

---

# NEUROPHYSICS

```markdown
---
layout: page
title: Neurophysics
permalink: /neurophysics/
---

# Neurophysics

My work in neurophysics focuses on how distinct neural systems learn different kinds of information and how those differences shape cognition and behavior. A central goal of this research is to identify the right state variables for linking neural mechanisms to observable human behavior.

## Core Question

How can we build mechanistic models of learning that connect neural representations to educationally and behaviorally meaningful outcomes?

## Central Idea

I argue that human behavior is governed by multiple interacting learning and decision systems operating in different state spaces with different geometries, dynamics, and constraints. Each system learns a different kind of information regularity, and those differences matter for what is learned, how errors arise, and what kinds of interventions are likely to succeed.

## Research Themes

### Multiple learning systems
- [Placeholder: brief description of perceptual, instinctual, procedural, and deliberative systems]
- [Placeholder: brief note on parallel action selection / interaction among systems]

### Information regularities
- [Placeholder: categorical relationships]
- [Placeholder: predictive relationships]
- [Placeholder: sequential relationships]
- [Placeholder: causal / structural relationships]

### State spaces and dynamics
- [Placeholder: how topology / geometry / dynamics enter the framework]
- [Placeholder: why this matters for behavior and design]

## Why this matters

A major challenge in the science of learning is that we often lack the correct variables for propagating from principles to design. By identifying the kinds of information each system learns and the structural properties of those representations, this work aims to make educational and behavioral prediction more mechanistically grounded.

## Selected Publications
- **[Paper title placeholder]**. *Journal placeholder*. [PDF](#) [DOI](#)
- **[Paper title placeholder]**. *Journal placeholder*. [PDF](#) [DOI](#)
- **[Paper title placeholder]**. *Journal placeholder*. [PDF](#) [DOI](#)

## Ongoing Projects
- **[Project title placeholder]** — [2–3 sentence summary]
- **[Project title placeholder]** — [2–3 sentence summary]
- **[Project title placeholder]** — [2–3 sentence summary]

## Talks
- **[Talk title placeholder]**, [Institution / Conference], [Year]
- **[Talk title placeholder]**, [Institution / Conference], [Year]

## Related links
- [Preprints](#)
- [Slides](#)
- [Code / models](#)
```

---

# TRUST

```markdown
---
layout: page
title: Trust
permalink: /trust/
---

# Trust Research

My research on trust develops a mechanistic account of how trust forms, stabilizes, and changes. Rather than treating trust only as a collection of trait judgments or survey factors, I examine how multiple neural learning systems contribute to cooperation, suspicion, confidence, and revision.

## Core Question

What are the learning mechanisms that generate trust in real human relationships?

## Central Idea

I argue that trust cannot be fully understood as a static evaluation of competence, benevolence, or integrity alone. Trust also depends on distinct pathways through which people learn from prediction, interaction, structure, and experience.

## Research Themes

### Beyond trait taxonomies
- [Placeholder: contrast with standard factor models]
- [Placeholder: why attribute-based frameworks are incomplete]

### Learning pathways to trust
- [Placeholder: predictive learning and expectation]
- [Placeholder: sequential learning and habit / procedural stability]
- [Placeholder: causal / deliberative interpretation]
- [Placeholder: affective / instinctual influences such as threat and safety]

### Trust revision
- [Placeholder: what changes trust]
- [Placeholder: why some trust failures generalize and others do not]

## Why this matters

Mechanistic models of trust can help explain cooperation, conflict, institutional confidence, and breakdowns in relationships in ways that are difficult to capture with purely descriptive taxonomies.

## Selected Publications
- **[Paper title placeholder]**. *Journal placeholder*. [PDF](#) [DOI](#)
- **[Paper title placeholder]**. *Journal placeholder*. [PDF](#) [DOI](#)
- **[Paper title placeholder]**. *Journal placeholder*. [PDF](#) [DOI](#)

## Ongoing Projects
- **[Project title placeholder]** — [2–3 sentence summary]
- **[Project title placeholder]** — [2–3 sentence summary]

## Related links
- [Preprint: taxonomy of trust placeholder](#)
- [Talks / presentations](#)
- [Collaborators](#)
```

---

# IMPLEMENTATION SCIENCE

```markdown
---
layout: page
title: Implementation Science
permalink: /implementation-science/
---

# Implementation Science

My work in implementation science examines how strong ideas survive contact with real institutions. I focus on the gap between instructional or organizational designs that look compelling in theory and the practical conditions required for those designs to succeed in real settings.

## Core Question

How do we move from sound design to successful adoption, sustainment, and revision in the real world?

## Central Idea

I draw on implementation science to study the mechanisms by which educational and organizational interventions succeed or fail. This includes planning, leadership support, revision cycles, stakeholder relationships, and the handling of unforeseen barriers during rollout.

## Research Themes

### Design-to-implementation gap
- [Placeholder: why good ideas often fail in practice]
- [Placeholder: why mechanism matters for implementation]

### Revision and sustainment
- [Placeholder: importance of iterative adaptation]
- [Placeholder: why early setbacks should not drive abandonment]

### Human and relational factors
- [Placeholder: buy-in, emotion, trust, and leadership]
- [Placeholder: stakeholder coordination and institutional support]

### Educational applications
- [Placeholder: active learning reform]
- [Placeholder: collaborative learning]
- [Placeholder: restorative practices or other implementation case]

## Why this matters

Many reforms fail not because the core ideas are wrong, but because implementation requires forms of coordination, monitoring, and revision that are often underappreciated. Mechanistic approaches can help make implementation more understandable and more effective.

## Selected Publications
- **[Paper title placeholder]**. *Journal placeholder*. [PDF](#) [DOI](#)
- **[Paper title placeholder]**. *Journal placeholder*. [PDF](#) [DOI](#)

## Ongoing Projects
- **[Project title placeholder]** — [2–3 sentence summary]
- **[Project title placeholder]** — [2–3 sentence summary]
- **[Project title placeholder]** — [2–3 sentence summary]

## Case Examples
- **[Case placeholder: SCALE-UP or course reform]** — [2–3 sentence summary]
- **[Case placeholder: restorative discipline / district rollout]** — [2–3 sentence summary]

## Related links
- [Perspective pieces](#)
- [Talks / workshops](#)
- [Supplementary materials](#)
```

---

# BIO

```markdown
---
layout: page
title: Bio
permalink: /bio/
---

# Bio

<div style="display:flex; gap:2rem; align-items:flex-start; flex-wrap:wrap; margin-bottom:2rem;">
  <div style="flex:0 0 260px;">
    <img src="/assets/images/profile.jpg" alt="Scott Allen" style="width:100%; max-width:260px; border-radius:6px;">
  </div>
  <div style="flex:1 1 420px; min-width:280px;">

Scott Allen is [current position placeholder] at [institution placeholder]. His research connects neural mechanisms of learning to behavior, trust, education, and implementation in real-world settings.

He works at the intersection of [physics / neuroscience / education / implementation science placeholder]. His research develops mechanistic models of how distinct neural systems learn different kinds of information and how those distinctions shape human cognition, social behavior, and instructional design.

  </div>
</div>

## Short Bio

[150-word bio placeholder for conference programs, websites, and invited talks.]

## Longer Bio

[300–500 word professional biography placeholder. Include training, current role, broad research program, major collaborations, and main application areas.]

## Education
- **Ph.D.**, [Field placeholder], [Institution placeholder], [Year placeholder]
- **M.S.**, [Field placeholder], [Institution placeholder], [Year placeholder]
- **B.S.**, [Field placeholder], [Institution placeholder], [Year placeholder]

## Appointments
- [Title placeholder], [Institution], [Years]
- [Title placeholder], [Institution], [Years]
- [Title placeholder], [Institution], [Years]

## Selected Publications
- **[Publication title placeholder]**. *Journal placeholder*. [PDF](#) [DOI](#)
- **[Publication title placeholder]**. *Journal placeholder*. [PDF](#) [DOI](#)
- **[Publication title placeholder]**. *Journal placeholder*. [PDF](#) [DOI](#)
- **[Publication title placeholder]**. *Journal placeholder*. [PDF](#) [DOI](#)
- **[Publication title placeholder]**. *Journal placeholder*. [PDF](#) [DOI](#)

## CV
- [Download CV (PDF)](/assets/files/CV.pdf)

## Collaborators
- [David Redish](#)
- [René Kizilcec](#)
- [Collaborator placeholder](#)
```

---

# CONTACT

```markdown
---
layout: page
title: Contact
permalink: /contact/
---

# Contact

I am happy to discuss research collaborations, invited talks, postdoctoral opportunities, and conversations related to learning, trust, neuroscience, education, and implementation.

## Contact information

**Email:** [your_email_here]  
**Institution:** [institution placeholder]  
**Location:** [city, state placeholder]  

## Professional links
- [Google Scholar](#)
- [ORCID](#)
- [GitHub](#)
- [LinkedIn](#)
- [CV (PDF)](/assets/files/CV.pdf)

## Research inquiries

For research-related inquiries, please include a brief note about the topic you would like to discuss.

## Collaboration areas
- Mechanistic models of learning
- Trust and social behavior
- Educational design and implementation
- Neuroscience-informed theory building
```

---

# Style guidance

* Keep each page readable at a glance.
* Use short sections and informative headers.
* Avoid long unbroken blocks of text.
* Put your strongest conceptual framing near the top of each page.
* Keep publication lists selective on topic pages; put the fuller list on Bio or a future Publications page.
* Use placeholders now rather than filling with weak material.

---

# Immediate next steps

1. Replace placeholder links.
2. Add your profile image at `assets/images/profile.jpg`.
3. Add your CV at `assets/files/CV.pdf`.
4. Create one markdown file per page.
5. Paste the relevant page template into each file.
6. Update `_config.yml` so the top navigation appears.
7. Publish and then refine page-by-page.
