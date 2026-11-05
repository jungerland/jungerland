# Jay Ungerland

Senior PM for B2B SaaS. Nearly 7 years at Xero, on a cloud accounting platform with 5M subscribers. Former engineer who now builds working AI agents to test product ideas hands-on.

## Problems I work on
- Deciding when an AI agent can act on its own, and when a person has to decide
- How to measure that before a customer relies on it
- Fintech, compliance, and legal work: where a wrong answer is expensive

## Projects

**[Grit Remover](https://github.com/jungerland/grit-remover)**: matches incoming payments to invoices, applies the matches it can prove, and queues the rest for a person. I tested it on a new set of fictional payments, created after the agent was finished. It resolved 70 of every 100 correctly with no human review and made zero wrong automatic matches. Simple matching rules resolved 59.
[Demo](https://claude.ai/artifact/W5w7goumjU1Hdasa35nqAR) · [Memo](https://github.com/jungerland/grit-remover/blob/main/MEMO.md)

**[Incident Clock](https://github.com/jungerland/incident-clock)**: after a vendor breach, it works out which customers are owed notice and by when, then drafts each notice for counsel. In each of 3 runs on fictional contracts, it found 71 of 71 required commitments and handled 19 of 19 traps. No separate test set yet, so this shows it passes its own test, not how it does on new contracts.
[Demo](https://claude.ai/artifact/3q22aFqYC36LqojnzfnSYK) · [Memo](https://github.com/jungerland/incident-clock/blob/main/MEMO.md)

**[LabDoctor](https://github.com/jungerland/labdoctor)**: prototype agent that tests Google Cloud labs, diagnoses failures, and proposes fixes. Sandbox runs in simulated mode.

**[Tab Rehab](https://github.com/jungerland/tab-rehab)**: a small local tool for finding, closing, and moving Chrome tabs.

## How I work
I write the expected answers before the agent, compare it to a simpler way of doing the job, and publish the limits along with the results.

[LinkedIn](https://www.linkedin.com/in/ungerland/)
