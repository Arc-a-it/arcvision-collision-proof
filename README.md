# ArcVision Collision Proof

This repository contains **raw evidence** of a CLI-based architectural gate
blocking a reasonable code change due to architectural impact.

---

## What Happened

• A small change to a dependency-heavy file  
• ArcVision evaluated architectural impact  
• The change was BLOCKED  
• An override was possible — but permanently recorded  

The decision was **arguable**.
It could not be ignored.

---

## Artifacts

- `proof/trigger-blocked.txt`  
  Raw CLI output from trigger.dev repository

- `proof/trigger-ledger.json`  
  Permanent authority ledger entry after override

- `proof/nextauth-blocked.txt`  
  Raw CLI output from next-auth repository

- `proof/nextauth-ledger.json`  
  Permanent authority ledger entry after override

- `proof/synthetic-blocked.txt`  
  Raw CLI output from a synthetic test repository

- `proof/synthetic-ledger.json`  
  Permanent authority ledger entry after override

---

## The Question

Should a CLI tool be allowed to **force architectural arguments before code is merged**?

That's the only question this repo asks.