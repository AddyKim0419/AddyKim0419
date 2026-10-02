# Adrian Studio

### Practical developer tools & reliability labs

Small, runnable examples for understanding failure modes in backend systems. Start with the code, reproduce the behavior, and inspect the assumptions.

**Current focus:** Java · notification reliability · retries & idempotency

## Start here

### [Notification Timeout Lab](https://github.com/AddyKim0419/notification-timeout-lab)

**A timeout can hide a successful send. What should the client do next?**

A standalone Java lab that compares a broken retry, a stable-key retry, and an `UNKNOWN` outcome resolved through read-only acceptance lookup.

- **Run locally:** JDK 21+, no third-party dependencies or network calls
- **Inspect the evidence:** [7 executable checks and their recorded results](https://github.com/AddyKim0419/notification-timeout-lab/blob/main/TEST-EVIDENCE.md)
- **Use the source:** [MIT-licensed sample](https://github.com/AddyKim0419/notification-timeout-lab)

[Explore the code →](https://github.com/AddyKim0419/notification-timeout-lab) · [Read the walkthrough →](https://adrianstudio3.hashnode.dev/a-notification-timeout-can-hide-a-successful-send)

## How these labs are built

AI-assisted development, with explicit assumptions and executable checks. The current lab uses a synthetic, in-memory provider. Its tests verify that model; they do not establish real-provider behavior, successful delivery, or production readiness.

## Learn & explore

- [Technical notes](https://adrianstudio3.hashnode.dev/)
- [Free sample ZIP](https://adrianstudio3.itch.io/notification-timeout-lab-free-java-sample)
- [Notification Failure Kit](https://adrianstudio3.gumroad.com/l/iqwjwr) · a separate paid teaching kit sold by Adrian Studio

The free lab stands on its own. No purchase is required to run it.
