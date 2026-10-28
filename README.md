# SRP Linking Guide

A bilingual (Español / English) visual guide for EVE Online pilots whose killmail does not appear on zKillboard, so they can submit it manually and continue an SRP request.

## View the guide

Open [`index.html`](index.html) in a browser. Use the **ES / EN** switch in the top-right corner to change the language. Click any screenshot to enlarge it.

The guide is a static HTML page with no build step, external JavaScript libraries, or backend. It works with the three images in [`assets/`](assets/).

## Workflow

1. Open Notification History in EVE Online and find the Kill Report.
2. Click the three-dot menu in the Kill Report.
3. Select **Copy External Kill Link**.
4. Go to [zKillboard's external killmail submission page](https://zkillboard.com/post/), paste the link, and submit it.
5. Once the killmail appears on zKillboard, copy its zKillboard kill-page URL and continue the SRP request in the [Sigma Grindset AUTH](https://auth2.sigmagrindset.net/ship-replacement/).

**Important:** The external kill link is used to post the killmail on zKillboard. For SRP, use the resulting zKillboard kill-page URL in the Sigma Grindset AUTH.

## Files

- `index.html` — responsive guide with the language switch and image lightbox.
- `assets/01-notifications.png` — Notification History and Kill Report.
- `assets/02-copy-external-link.png` — Kill Report three-dot menu.
- `assets/03-zkillboard-post.png` — zKillboard post form.

The screenshots are from EVE Online and zKillboard and retain their original UI wording. This is an independent community guide, not an official CCP Games or zKillboard publication.
