---
layout: default
title: Moxuno Support
---

# Moxuno support and FAQ

> **Pending publication:** This page is a GitHub Pages source draft. It is not a live support page and does not replace signed-device or release testing.

**Publisher:** Saksham Virmani<br>
**Support:** [support@sakshamvirmani.com](mailto:support@sakshamvirmani.com)

## What is Moxuno?

Moxuno helps you add a small pause before opening the apps, categories, or websites you choose. You decide what belongs behind the gate, then choose a short ritual when you want an intentional opening.

## How do I set up my boundary?

1. Allow Screen Time access when Apple asks.
2. Choose the apps, categories, or websites you want to pause.
3. Save the selection and confirm what is included.
4. Choose a ritual when you want an intentional opening.

If permission is denied or later revoked, use “Review Screen Time access” in Moxuno and return to setup. Moxuno should show that protection needs attention instead of claiming that apps are blocked when authorization or selection is missing.

## What does “protected” mean?

On an authorized device, Moxuno asks Apple’s Screen Time services to apply a shield to the selected boundary. The direct shield-to-Moxuno route is conditional on iOS 26.5 or later; iOS 17 through iOS 26.4 uses the documented manual Home Screen reopen. Both routes and automatic re-shielding still need signed-device validation.

## How long is an open window?

The selected v1 behavior is one 15-minute wall-clock window for the whole saved selection, with “Close window now” available. Background expiry and callback tolerance require physical-device proof before they are a final customer promise.

## How do I change protected apps?

Open “Protected apps” in Settings, edit the Apple Screen Time selection, and save. The final release must validate what happens when a selection changes during an open window.

## Does Moxuno collect app usage or browsing history?

The current source has no analytics, cloud, network upload, account, or usage-history service. Screen Time selections are stored locally as Apple-managed opaque tokens. Moxuno does not use billing, subscriptions, or purchases.

## How do I delete my data?

Moxuno currently provides controls to close an open window, stop protection, and clear recorded ritual progress. A complete local reset and protected-selection deletion flow still require final release validation. Until that work is complete, do not treat the app’s separate controls as a promise that every local record has been removed.

## What if I cannot or do not want to walk?

Reset is an equal ritual alternative. Move can read Core Motion step data while you complete it; if motion access is denied or unavailable, Moxuno must explain that state without awarding steps it did not observe.

## Contact support

Email [support@sakshamvirmani.com](mailto:support@sakshamvirmani.com). Include the Moxuno version, iOS version, device model, and a description of the issue. Do not include Screen Time tokens or private browsing details.

This page’s public URL and publication date are pending owner approval.
