# LENS Program

**Learning, Estimation, and Nonidentifiability in Statistics**

A collaboration exploring what we can learn when our data and models cannot tell us everything.
We bring together researchers across institutions and disciplines to advance our understanding
of **identifiability, recoverability, and learning in complex statistical models**.

> **Our central question:** What can we learn from the available data and models — even when
> full identification is impossible?

<img src="docs/lens_logo.png" width="200" align="right" alt="LENS Program logo">

## Upcoming meeting

**LENS Monthly Group — Tuesday, October 6, 2026, 3:00–4:00 pm Eastern, via Zoom**

The monthly group meets the first Tuesday of each month, 3:00–4:00 pm Eastern.

## Why this matters

Identifiability is treated differently across statistics, optimization, and mathematical
modeling. Many important scientific quantities may be learnable even when models are not fully
identifiable — but we need a common language, and new methods, for understanding what is
recoverable and why.

## Two connected groups

**LENS Monthly Group** — a cross-institutional forum, open to collaborators at any institution,
meeting monthly via Zoom. Short talks on current projects and methods, work-in-progress
presentations, new ideas and tools, discussion and feedback, and building connections for
future collaboration.

**PRISM Working Group (Emory)** — a focused, hands-on group of students, postdocs, and faculty
meeting weekly on campus or via Zoom. Deep dives into technical problems, method development
and analysis, code sharing, and preparing work to share with the monthly LENS group.

## Questions we explore

- What are the relationships among identifiability, partial identifiability, practical
  identifiability, and recoverability?
- Which parameters or functionals remain recoverable when a full model is nonidentifiable?
- How can recoverability be characterized or diagnosed?
- How do priors, constraints, measurement error, and external information affect what can be
  learned?
- How do spatial and hierarchical structures influence identifiability?
- How do likelihood-based and objective-function approaches relate?
- How should we represent uncertainty when information varies across model components?

## Application areas

Small-area estimation · spatial and spatiotemporal models · measurement error and
misclassification · data integration and fusion · hierarchical and multilevel modeling ·
generalized Bayesian and objective-function approaches

## Who should join

Faculty, postdocs, and graduate students with interests in Bayesian methods, small-area
estimation, spatial statistics, measurement error, hierarchical modeling, identifiability
theory, optimization and objective functions, or data integration.

## Get involved

We welcome anyone interested in these questions. To join the mailing list or learn more,
please contact:

- **Emily N. Peterson, PhD**, Emory University — emily.nancy.peterson@emory.edu
- **Lance Waller, PhD**, Emory University — lwaller@emory.edu

## Program flyer

<a href="docs/LENS_poster.png"><img src="docs/LENS_poster_web.jpg" width="450" alt="LENS Program flyer"></a>

[Download the full-resolution flyer](docs/LENS_poster.png)

## How we use this repository

**You do not need to know git.** Everything here can be added from the browser: on any folder
page, use **Add file → Create new file**, type a filename, write in Markdown, and commit. That
is the expected way for most members to contribute — cloning is optional.

| path | what it holds |
|---|---|
| `meetings/` | Agendas and notes from LENS meetings, as `YYYY-MM-DD-<group>.md` |
| `talks/` | Slides and materials from presentations, one folder per talk |
| `readings/` | Running reading list — citations, links, and PDFs |
| `docs/` | Flyer, logo, shared materials |
| `index.md` | Source for the project website |

**Issues are our running agenda.** If you want to raise a topic, propose a paper, or ask a
question between meetings, [open an issue](../../issues) rather than sending email. It threads,
it is searchable, and it survives everyone forgetting what was raised three meetings ago.

**Discussions are for open-ended conversation.** Questions that are not tasks — "does anyone know
of work on X", "how do people think about Y" — belong in
[Discussions](../../discussions). Anyone can join, including people outside Emory, which is the
point of the monthly group.

**Code lives in its own repository once it grows up.** Prototypes and scratch work belong in the
PRISM working repository. When something matures into a method implementation, a package, or a
paper's reproduction materials, it gets its own public repository in the
[lens-program](https://github.com/lens-program) organization and is linked from here. This keeps
the front door readable instead of turning it into a junk drawer.

See [CONTRIBUTING.md](CONTRIBUTING.md) for details.
