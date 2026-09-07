<picture>
  <source media="(max-width: 1011px)" srcset="https://raw.githubusercontent.com/AliAlJonaid/AliAlJonaid/main/assets/header-mobile.svg?v=2" />
  <img src="https://raw.githubusercontent.com/AliAlJonaid/AliAlJonaid/main/assets/header.svg?v=2" width="100%" alt="Ali Al-Jonaid — Making the pieces work together. Computer Science at the University of Calgary." />
</picture>

I'm **Ali Al-Jonaid**, a second-year Computer Science student at the **University of Calgary**. I focus on **Python automation and systems integration**. I'm interested in how we tell whether an automated task succeeded, and what happens when a write stops halfway through.

**Seeking Summer 2027 internships across Canada** in automation, cloud infrastructure, or IT operations. Based in Calgary; open to relocation. [LinkedIn](https://www.linkedin.com/in/ali-al-jonaid/)

## Selected work

### [AX Relay](https://github.com/AliAlJonaid/ax-relay)

**The model chooses a control. The operating system supplies its position.**

A Python runtime for macOS automation with numbered interface controls, provider failover, and checks that compare current observations with the task's starting state.

**My contribution:** I defined the interaction model around numbered controls and OS-reported positions, set provider boundaries and acceptance criteria, and directed implementation and revisions.

[Walk through the design](https://github.com/AliAlJonaid/ax-relay/blob/main/docs/walkthrough.md) · [Read the verification checks](https://github.com/AliAlJonaid/ax-relay/blob/main/agents/test_appname_verify.py)

### [Market Decision Ledger](https://github.com/AliAlJonaid/market-decision-ledger)

**An interrupted write should have a defined recovery path.**

A local Python ledger for simulated transactions, with purchase rules and a recovery journal. Tests interrupt event and state writes, then check that recovery restores the deposit and records it once.

**My contribution:** I defined the paper-only scope, review rules, and evidence requirements, then reviewed and validated the implementation. All examples use synthetic data.

[Run the five-minute example](https://github.com/AliAlJonaid/market-decision-ledger/blob/main/docs/walkthrough.md) · [Recovery results and tests](https://github.com/AliAlJonaid/market-decision-ledger/blob/main/docs/walkthrough.md#6-inspect-the-failure-tests)

## How I work

I direct AI-assisted implementation around explicit constraints and acceptance criteria, review the resulting behaviour, and direct revisions when it falls short. The projects make those checks inspectable through provider-failure tests, action guards, and interrupted-write recovery. Each project documents my contribution and the assistance used: [AX Relay](https://github.com/AliAlJonaid/ax-relay/blob/main/docs/ai-collaboration.md) · [Market Decision Ledger](https://github.com/AliAlJonaid/market-decision-ledger/blob/main/docs/ai-collaboration.md).
