# Privacy Policy (FrontierLifeMC)

**Last updated: February 27, 2026**

## Overview

This privacy policy describes how this application ("the App") handles information
when you authorize it via Google OAuth to access your YouTube account data.

The App is operated for the purpose of displaying YouTube Live stream status
on a Minecraft server.

## Data We Access

When you grant authorization, the App requests read-only access to:

- Your YouTube channel's live streaming status (whether a stream is currently active)

This is accomplished using the `youtube.readonly` OAuth scope provided by the
[YouTube Data API v3](https://developers.google.com/youtube/v3).

## Data We Do Not Collect

- We do not collect, store, or transmit your personal information
- We do not access your Google account credentials or password
- We do not access any YouTube data beyond live status
- We do not sell, share, or disclose any data to third parties

## How Authorization Works

Authorization is handled entirely through Google's OAuth 2.0 flow. You will be
redirected to Google's consent screen, where you can review and approve the
requested permissions before granting access. You may revoke access at any time
via your [Google Account Permissions](https://myaccount.google.com/permissions) page.

## Data Retention

No personal data is retained by this application. Access tokens are used only
for the duration of the authorized session and are not logged or stored
persistently.

## Third-Party Services

This App interacts with the following external service:

- **Google / YouTube Data API v3** — governed by [Google's Privacy Policy](https://policies.google.com/privacy)

## Contact

If you have questions about this privacy policy, please open an issue on this
repository or contact the server administrator directly.
