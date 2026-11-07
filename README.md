# pwnt-toast

```

Public Stub for PWNT TOAST, the CVE to PoC to Patch or Pwnt Security Suite.

You've got CVE, we've got the solution.


    ██████╗ ██╗    ██╗███╗   ██╗████████╗    ████████╗ ██████╗  █████╗ ███████╗████████╗
    ██╔══██╗██║    ██║████╗  ██║╚══██╔══╝    ╚══██╔══╝██╔═══██╗██╔══██╗██╔════╝╚══██╔══╝
    ██████╔╝██║ █╗ ██║██╔██╗ ██║   ██║          ██║   ██║   ██║███████║███████╗   ██║
    ██╔═══╝ ██║███╗██║██║╚██╗██║   ██║          ██║   ██║   ██║██╔══██║╚════██║   ██║
    ██║     ╚███╔███╔╝██║ ╚████║   ██║          ██║   ╚██████╔╝██║  ██║███████║   ██║
    ╚═╝      ╚══╝╚══╝ ╚═╝  ╚═══╝   ╚═╝          ╚═╝    ╚═════╝ ╚═╝  ╚═╝╚══════╝   ╚═╝

    ╔═══════════════════════════════════════════════════════════════════════════════════╗
    ║                                                                                   ║
    ║           CVE  ──────────────►  PoC  ──────────────►  [ PWNT ]                    ║
    ║                                                                                   ║
    ║         ┌──────┐   parse   ┌──────┐  generate  ┌──────────────┐                   ║
    ║         │ CVE  │ ────────► │ vuln │ ─────────► │  exploit.py  │                   ║
    ║         │  DB  │           │ info │            │  crispy      │                   ║ 
    ║         └──────┘           └──────┘            └──────────────┘                   ║
    ║                                                                                   ║
    ╚═══════════════════════════════════════════════════════════════════════════════════╝

         ______
        /      \          P W N T   T O A S T
       /  🔥🔥 \         ─────────────────────────────
      /  ______  \        CVE2PoC Factory  |  v1.0
     |  |      |  |       "We burn it so you don't have to"
     |  |  ██  |  |
      \ |  ██  | /
       \|______|/
        |      |
      ══╧══════╧══

Another Creative Mayhem Product.

Contact Sales@CreativeMayhem.com
```

---

## No weapons

This repo tracks what PWNT-Toast has found and fixed. Every entry is a disclosed, public CVE
with a recommended remediation. There is no exploit code, no proof-of-concept scripts, and no
runnable harness here, and there never will be. If you're looking for a weapon, this isn't it,
and we won't point you to one.

A disclosed CVE with a working exploit attached is a gift to one audience, and it isn't
defenders. We built this to shorten the distance between "a bug exists" and "the bug is fixed."
If a vulnerability needs a working reproduction to be taken seriously, that reproduction stays
with the vendor, the CNA, or whoever's coordinating the disclosure. It does not go here.

What you'll find per CVE:

- the public vulnerability record (CVE ID, affected product, root cause)
- the recommended fix, as a diff or concrete code change
- hardening guidance for the vulnerability class
- disclosure timeline and references

## Index

| CVE | Product | Class | Status |
|---|---|---|---|
| [CVE-2026-116533](CVE-2026-116533/) | Static Snapshot (WordPress plugin) | OS command injection (CWE-94) | Patch published, no vendor fix exists |

## Working with us

PWNT-Toast runs against disclosure queues, internal backlogs, and bounty programs under NDA, on
your infrastructure or ours.

This is what Creative Mayhem does. Offensive and defensive security, hands on the tools, not a
deck: penetration testing and red teaming across web, infrastructure, APIs, and AI/LLM systems,
hardening, detection engineering, and incident response readiness. 36 years on the tools behind it.
Offensive engagements need a signed SOW and written authorization, every time, no exceptions.

A free, no-obligation call first. A scoped SOW before anything runs. What you get at the end is
working tooling, not a PDF that gets skimmed once and filed. If that's what you need:
[CreativeMayhem.com/services](https://CreativeMayhem.com/services)
