# Use Plausible for website analytics

- Status: accepted
- Date: 2024-06-03
- Tags: analytics

## Context and Problem Statement

We need to choose an analytics solution for all our websites. The main options we are considering are Google Analytics and Plausible. We need to evaluate these options and make a decision.

## Decision Drivers

- Ease of implementation (time to implement)
- Data privacy and compliance
- Feature set
- Performance

## Considered Options

- Google Analytics
- Plausible

A PoC was done with the Astro blog website, unfortunately Google Analytics was not working within the time limit and Plausible worked straight out of the box.

## Decision Outcome

Chosen option: "Plausible", because it provides a lightweight and privacy-focused analytics solution that was the fastest to implement.

### Positive Consequences

- Improved data privacy and compliance
- Lightweight and fast-loading analytics script

### Negative Consequences

- Limited feature set compared to Google Analytics
- Less integration options with other tools
- Paid plans only.

## Links

- [Plausible website](https://plausible.io/)
- [Google Analytics website](https://analytics.google.com/)