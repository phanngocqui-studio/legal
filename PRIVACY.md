# Privacy Policy — ngocqui-mmo

_Last updated: 2026-06-09_

## 1. Overview
"ngocqui-mmo" ("the App") is a personal content-automation tool. This Privacy Policy explains
what data the App handles and how. The App is operated by its owner for personal and internal
business use.

## 2. Information we handle
- **TikTok authorization tokens** — When you authorize the App through TikTok's OAuth consent,
  the App receives access and refresh tokens that allow it to publish videos to the authorized
  TikTok account. These tokens are stored only in the App owner's own self-hosted environment
  (a private n8n instance) and are never shared or sold.
- **Product data** — Public product information (title, price, image, affiliate link) retrieved
  from the TikTok Shop Affiliate Creator API, used solely to generate promotional videos.
- **Generated content** — Video scripts and captions generated via the Anthropic Claude API,
  and rendered videos produced via Creatomate.

The App does **not** collect personal data from TikTok viewers, does not run analytics on third
parties, and does not build user profiles.

## 3. How information is used
Information is used only to: fetch affiliate products, generate video content, render the video,
and publish it to the App owner's authorized TikTok account. Optionally, a Telegram notification
is sent to the App owner reporting success or failure.

## 4. Storage and security
All credentials and tokens are kept in the App owner's private, self-hosted environment and in
environment variables that are not committed to source control. They are not transmitted to any
party other than the official APIs required to perform the above functions (TikTok, Anthropic,
Creatomate, Telegram).

## 5. Data sharing
The App does not sell, rent, or share handled data with third parties, except sending the
necessary requests to the official APIs listed above to perform its function.

## 6. Data retention and deletion
Tokens are retained only as long as needed to operate the App and can be revoked at any time.
You may revoke the App's access from your TikTok account settings. To request deletion of any
stored data, contact the App owner.

## 7. Third-party services
This App relies on TikTok, Anthropic (Claude), Creatomate, and Telegram. Please review their
respective privacy policies for how they handle data.

## 8. Changes
This Privacy Policy may be updated from time to time. The "Last updated" date reflects the
latest revision.

## 9. Contact
For privacy questions or data requests, contact: **phanngocqui69@gmail.com**
