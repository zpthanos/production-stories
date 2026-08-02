# Post-launch caching defect

[← All production stories](../README.md)

`Cloudflare` `Caching` `CSS` `Production support`

## Situation

After the launch of [RadioFamily.gr](https://www.radiofamily.gr/), some design updates were not appearing correctly because specific stylesheets were being served from cache.

## Task

I needed to restore current styling without disabling the site's wider performance configuration.

## Action

I reproduced the behaviour, isolated the affected cached resources, excluded the necessary stylesheets from the relevant caching rules, and configured Cloudflare cache-clearing behaviour for future updates.

## Result

Visitors received the current styling while the site retained its broader caching and performance benefits.

## CV-ready summary

> Resolved a post-launch caching conflict on RadioFamily.gr by isolating stale stylesheets, applying targeted cache exclusions, and configuring Cloudflare purging without removing broader performance controls.
