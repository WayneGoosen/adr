# ADR - A decision records experiment

This repository uses log4brains to publish all ADRs within this repository.

The experiment: Use ADRs to track all decisions made on any projects within my github profile. If any project gets big enough move all the relevant ADRs to its repository.

## Why?

1. Log of all decisions for history and recall purposes. Sometimes we forget WHY we did something a certain way.
2. Visibility... Decisions around software are just trade offs and depend on the situation & context. This will help understand certain decisions.
3. Practise crafting ADRs. Thought provoking process which will I hope help make better decisions.
4. Bring in a level of professionalism with side projects.

# Architecture Decision Records

ADRs are automatically published to our Log4brains architecture knowledge base:

🔗 **<https://waynegoosen.github.io/adr/log4brains/>**

Please use this link to browse them.

## Development

If not already done, install Log4brains:

```bash
npm install -g log4brains
```

To preview the knowledge base locally, run:

```bash
log4brains preview
```

In preview mode, the Hot Reload feature is enabled: any change you make to a markdown file is applied live in the UI.

To create a new ADR interactively, run:

```bash
log4brains adr new
```

## More information

- [Log4brains documentation](https://github.com/thomvaill/log4brains/tree/master#readme)
- [What is an ADR and why should you use them](https://github.com/thomvaill/log4brains/tree/master#-what-is-an-adr-and-why-should-you-use-them)
- [ADR GitHub organization](https://adr.github.io/)
