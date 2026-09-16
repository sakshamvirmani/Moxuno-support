---
layout: default
title: Moxuno Privacy Policy
---

# Moxuno privacy policy

> **Published draft:** This page is publicly reachable for owner review, but it is not the final policy for a released app. The owner must approve the exact release behavior and effective date before treating it as final policy.

**Publisher:** Saksham Virmani<br>
**Support:** [support@sakshamvirmani.com](mailto:support@sakshamvirmani.com)<br>
**Effective date:** Pending owner approval after release behavior is confirmed

## What Moxuno does

Moxuno adds a short pause before the apps, categories, or websites you choose through Apple’s Screen Time controls. You choose the boundary on your iPhone and complete a ritual before an access window can open.

The selected v1 window is one 15-minute wall-clock window for the saved selection, with a “Close window now” action. Automatic expiry, re-shielding, and the route from an Apple shield back to Moxuno still require signed-device proof before this wording becomes release policy.

## Information Moxuno uses

Moxuno uses:

- Your setup state and ritual history, stored locally on the device.
- Your selected Screen Time apps, categories, and websites. Apple represents these selections with opaque tokens; Moxuno does not need to know their names or send them to a server.
- Apple Family Controls, Managed Settings, and Device Activity services to request authorization and apply the boundary you choose.
- Core Motion `CMPedometer` step data during the Move ritual when you grant motion access. Steps are used for that ritual and are not uploaded.

The production app stores shared selection and window state in the App Group container `group.com.moxuno.app` so the app and its Screen Time extensions can coordinate locally. Test and unavailable-container paths may use local app storage instead.

Moxuno does not request an account and the current source has no developer cloud, network service, analytics, advertising, crash-reporting, or third-party tracking. It has no billing, purchase, subscription, or payment flow. It does not request contacts, location, photos, camera, microphone, or Health data.

## Where information goes

The current source has no developer server or network destination. Moxuno keeps its setup, selection records, access-window state, and ritual history on the device. Apple’s Screen Time system handles its own authorization and shielding services under Apple’s terms.

## Retention, deletion, and reset

There is no Moxuno account or server copy to delete. The app currently provides separate controls for closing an open window, stopping protection, and clearing recorded ritual progress. The complete local reset and protected-selection deletion behavior still require final release validation; this page must be updated to describe the exact records removed and the Apple authorization state that remains.

Do not send Screen Time tokens or private browsing details when contacting support.

## Adults and children

Moxuno is designed for individual self-management by adults. The final age rating and distribution decisions remain subject to owner review. This draft does not make a legal age classification.

## Changes to this policy

Material changes to local storage, Screen Time use, motion access, account or cloud behavior, analytics, or billing require an updated policy and App Privacy review. The owner will confirm the reachable policy URL and effective date after approving the release.

## Contact

For support, email [support@sakshamvirmani.com](mailto:support@sakshamvirmani.com). Include the Moxuno version, iOS version, device model, and a description of the issue. Do not include Screen Time tokens or private browsing details.

The legal address is not supplied in this draft. The currently reachable public URL is recorded in the T08 publication evidence.
