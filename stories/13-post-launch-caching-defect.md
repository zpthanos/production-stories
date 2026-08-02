<div align="center">

# Post-launch caching defect

**Restoring current styling without sacrificing wider performance controls**

`Cloudflare` · `Caching` · `CSS` · `Production support`

</div>

> **Outcome:** Resolved stale stylesheet delivery while preserving the site's broader caching and performance benefits.

## At a glance

| | |
| --- | --- |
| **Site** | [RadioFamily.gr](https://www.radiofamily.gr/) |
| **Issue** | Design updates hidden by cached stylesheets |
| **Role signal** | Production support · Root-cause isolation · Cloudflare operations |

## 1. Situation

After launch, some design updates were not appearing correctly because specific stylesheets were being served from cache.

## 2. Objective

Restore current styling without disabling the site's wider performance configuration.

## 3. What I did

- Reproduced the behaviour.
- Isolated the affected cached resources.
- Excluded the necessary stylesheets from the relevant caching rules.
- Configured Cloudflare cache-clearing behaviour for future updates.

## 4. Result

Visitors received the current styling while the site retained its broader caching and performance benefits.

## Recruiter takeaway

> Resolved a post-launch caching conflict on RadioFamily.gr by isolating stale stylesheets, applying targeted cache exclusions and configuring Cloudflare purging without removing broader performance controls.

---

[← Previous](12-technical-seo.md) · [All stories](../README.md) · [Next →](14-ambiguous-requirements.md)
