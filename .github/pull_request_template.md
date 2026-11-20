## What I'm adding

<!-- Name, section, and a one-line summary. -->

## Why this helps the open source ecosystem

<!-- Not what it is (the entry covers that). Why it helps others: who benefits, what they can reuse, fork, or learn from it, and what gap it fills next to listed entries. PRs without this are not reviewed. -->

## A2A conformance (Agents section only)

<!-- Agents must pass the A2A TCK (must level). Fill in the a2a-target line below with ONE of:
  - a container image that starts with no secrets (a mock or echo mode is fine), plus the port it serves A2A on:
      a2a-target: ghcr.io/owner/agent:1.0.0 port=8080
  - a public https endpoint whose /.well-known/agent-card.json is reachable:
      a2a-target: https://agent.example.org
  The URLs in the agent card must point at that same host and port. Leave it empty for non-agent entries. -->

a2a-target:

## Checklist

- [ ] The linked repository is public and uses an [OSI-approved license](https://opensource.org/licenses).
- [ ] The project has no commercial intent (not a paid, hosted-only, freemium, or marketplace product) and this PR is not promotion.
- [ ] I searched the list and this is not a duplicate (or I explained above what is different).
- [ ] This PR adds one entry and changes only `README.md`.
- [ ] I used the entry format.
