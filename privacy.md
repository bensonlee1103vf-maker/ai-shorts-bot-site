---
title: Privacy Policy
---

# Privacy Policy

_Last updated: 2026-10-31_

**ai-shorts-bot** ("the client") is a personal automation operated by its owner to publish videos to the owner's own YouTube channel. This policy explains what data the client accesses and how it is used.

## Who uses the client

Only the owner. The client has no end users, no sign-up, no login page and no public interface. The source code is kept in a private repository.

## YouTube API Services

The client uses YouTube API Services. By using it, the owner agrees to the [YouTube Terms of Service](https://www.youtube.com/t/terms) and the [Google Privacy Policy](https://policies.google.com/privacy).

The client accesses the following data **only for the owner's own channel**, through OAuth 2.0 authorisation granted once by the owner:

- **Upload** (`youtube.upload`): to publish videos the client produced.
- **Manage** (`youtube.force-ssl`): to post one pinned comment per video and to set the scheduled publish time.
- **Analytics** (`yt-analytics.readonly`): to read view counts, average view duration and retention of the owner's own videos.

The client does **not** read, store or process any data about other YouTube users or channels. It does not use the YouTube search API.

## Data storage and retention

- The OAuth refresh token is stored as an encrypted secret in GitHub Actions and is never written to files or logs.
- Analytics numbers for the owner's own videos (views, watch time, retention) are stored as a CSV file in the repository and kept indefinitely to improve future scripts. They contain no personal data.
- No cookies are set and no visitor data is collected on this website.

## Revoking access

The owner can revoke the client's access at any time at <https://myaccount.google.com/permissions>. Doing so stops all uploads and analytics reads immediately.

## Third-party services

Besides Google / YouTube, the client sends the video script text to Microsoft or Azure text-to-speech to generate narration, and uses the Anthropic API to write scripts. No YouTube user data is sent to these services.

## Contact

Questions about this policy: use the contact link on the YouTube channel's About page.
