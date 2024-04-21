<!-- This file is the homepage of your Log4brains knowledge base. You are free to edit it as you want -->
# Architecture knowledge base

Welcome 👋 to the architecture knowledge base for Wayne Goosen's GitHub profile.
You will find here all the Architecture Decision Records (ADR) for all projects.

## An Experiment with Architecture Decision Records

This repository employs Log4Brains to publish all Architectural Decision Records (ADRs) within it.

The experiment: Use ADRs to keep track of all decisions made across projects within my GitHub profile. If a project grows significantly, move all relevant ADRs to its own repository.

### Why?

1. To maintain a log of all decisions for historical and recall purposes. It's easy to forget WHY a certain approach was taken.
2. For visibility... Decisions in software development are trade-offs that depend on the situation and context. This will help in understanding certain decisions.
3. To practice crafting ADRs. This thought-provoking process will ideally lead to better decision-making.
4. To instill a level of professionalism in side projects.

### Structure

There are two distinct levels of ADRs:
- Global: Decisions that impact all repositories.
- Repository specific: Decisions exclusive to a particular project or product within a repository.

The repository-specific ones are added as 'packages' within the Log4Brains structure. You can identify these by the package name next to the title within the user interface.

## ADRs

### Definition and purpose

> An Architectural Decision (AD) is a software design choice that addresses a functional or non-functional requirement that is architecturally significant.
> An Architectural Decision Record (ADR) captures a single AD, such as often done when writing personal notes or meeting minutes; the collection of ADRs created and maintained in a project constitutes its decision log.

An ADR is immutable: only its status can change (i.e., become deprecated or superseded). That way, you can become familiar with the whole project history just by reading its decision log in chronological order.
Moreover, maintaining this documentation aims at:

- 🚀 Improving and speeding up the onboarding of a new team member
- 🔭 Avoiding blind acceptance/reversal of a past decision (cf [Michael Nygard's famous article on ADRs](https://cognitect.com/blog/2011/11/15/documenting-architecture-decisions.html))
- 🤝 Formalizing the decision process of the team

### Usage

This website is automatically updated after a change on the `master` branch of the project's Git repository.
In fact, the developers manage this documentation directly with markdown files located next to their code, so it is more convenient for them to keep it up-to-date.
You can browse the ADRs by using the left menu or the search bar.

The typical workflow of an ADR is the following:

![ADR workflow](/l4b-static/adr-workflow.png)

The decision process is entirely collaborative and backed by pull requests.

### More information

- [Log4brains documentation](https://github.com/thomvaill/log4brains/tree/master#readme)
- [What is an ADR and why should you use them](https://github.com/thomvaill/log4brains/tree/master#-what-is-an-adr-and-why-should-you-use-them)
- [ADR GitHub organization](https://adr.github.io/)
