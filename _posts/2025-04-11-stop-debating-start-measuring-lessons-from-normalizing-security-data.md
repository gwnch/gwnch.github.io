---
title: "Stop Debating, Start Measuring: Lessons from Normalizing Security Data"
categories:
  - Reflections
tags:
  - Speaking
  - Data-Normalization
  - Asset-Inventory
excerpt: "Once we normalized our security data, we stopped debating assumptions and started measuring reality, revealing coverage gaps, quantifying risk, and shifting remediation from reactive firefighting to focused, proactive action."
---

I spoke at a vendor conference about a shift that changed how we operate: once we normalized a lot of our data, we stopped arguing about what we thought was true and started measuring what was actually happening.

The audience spanned security leaders and practitioners across industries and disciplines. My goal was for everyone to leave with a simple takeaway: when you normalize data into a consistent view of your environment, assumptions become testable. That makes it easier to quickly identify missing vulnerability coverage, configuration drift, and control gaps. Just as importantly, it lets you quantify those findings (coverage, patch performance, misconfigurations) and translate them into actions teams can act on.

At a high level, a normalized view allows your team to move from reacting to alerts to validating reality: find the gaps, quantify the risk, and focus remediation where it matters most.

## What single pane of glass actually looked like for us
For us, single pane of glass wasn’t just a buzzword or a prettier dashboard. It meant less exporting spreadsheets and running VLOOKUPs to compare them. It meant fewer duplicate asset records because multiple sources were reconciled into a single record. It also meant fewer circular debates because the data was coming from systems they already used and trusted. And once the data lived in one place, reporting improved dramatically because we weren’t stitching together different views every time someone asked a question.
It also helped us operate more effectively even without a perfect CMDB. A strong inventory is still the goal, but normalization gave us a practical way to establish ownership, coverage, and visibility while we continued improving.

## What changed for my team
### Before
- Chasing alerts and new critical vulnerabilities as they appeared
- Inconsistent scope (repeated back-and-forth on whether we owned an asset)
- Remediation debates with inconsistent reporting

### After (not perfect, but meaningfully better)
- Validating assumptions quickly (coverage, exposure, posture)
- Prioritizing and sharing results with more confidence
- Automating workflows to notify stakeholders sooner

## Assumptions we were able to validate
Normalization made it possible to prove (or disprove) things we previously treated as common knowledge:
- **“All assets are scanned.”** We found missing ranges and gaps in coverage.
- **“We detect new critical vulnerabilities within a day.”** In some cases, detection lagged by more than a week after public disclosure.
- **“Teams are notified within one day of detection.”** Only true a small percentage of the time.

## A misconception I heard often
One recurring misconception in conversations was that single pane of glass means fewer tools. Sometimes it does, but often it doesn’t. In practice, it’s about normalizing and reconciling data across systems so you can make consistent decisions. Depending on your environment, that may require additional integration work, better data hygiene, or yes, sometimes another tool.

## What I’d do differently next time
- Share a clearer maturity path for inventory quality (crawl → walk → run), including minimum viable inventory fields
- Spend more time on why these initiatives stall in the real world, such as ownership, duplicate assets, drift, and unclear decision rights, and what to do about it.

The biggest lesson I left with is that most teams don’t have a tooling problem, they have a lack of visibility problem. A normalized view of your environment doesn’t magically fix everything, but it makes reality measurable. Once you can measure reality, you can stop arguing about it and start improving it.
