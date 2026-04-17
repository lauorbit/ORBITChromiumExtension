# Privacy Policy for ORBIT Scholar Grade Overlay

Last updated: April 17, 2026

ORBIT Scholar Grade Overlay is a browser extension that displays ORBIT journal information on Google Scholar pages.

## Summary

- The extension does not require users to create an account.
- The extension does not sell personal data.
- The extension does not use advertising trackers.
- The extension does not store personal data in extension storage.
- The extension does not collect analytics or telemetry for product analytics.

## Information the extension handles

To provide its functionality, the extension may access:

- page content on supported Google Scholar pages, including article titles, visible venue or source text, author snippets, and publication year information
- Google Scholar article-detail pages or citation-export responses when needed to identify the journal correctly
- a bundled local journal dataset shipped with the extension

When a journal cannot be resolved from the bundled dataset and Google Scholar page content alone, the extension may send a limited bibliographic query to the Crossref API. That query may include:

- article title
- visible citation metadata from Google Scholar
- author surname used for matching
- publication year used for matching

## How the information is used

The extension uses the above information only to:

- identify the journal associated with a Google Scholar result or author-profile publication
- match that journal against the bundled ORBIT dataset
- display the corresponding ORBIT grade, detailed source grades, and any relevant list indicators such as Elite List or Warning List

## Data storage

- The extension ships with a bundled local dataset for journal matching.
- The extension does not store browsing history in extension storage.
- The extension does not maintain user profiles.
- The extension may keep temporary in-memory caches during the current browser session to reduce repeated lookups.
- Those in-memory caches are not intended as long-term persistent storage and are cleared when the extension context is reloaded or the browser session ends.

## Data sharing

The extension does not sell or rent user data.

The extension does not share data with third parties except as needed to provide the fallback matching feature described above:

- Crossref API (`https://api.crossref.org`) may receive limited bibliographic query text so the extension can obtain journal ISSN or container-title information for unresolved results.

## Permissions

The extension requests access only to:

- supported Google Scholar domains, so it can read page content and render ORBIT badges on those pages
- `https://api.crossref.org/*`, so it can perform fallback journal matching when local resolution is insufficient

The extension does not request broad permissions such as:

- `tabs`
- `history`
- `cookies`
- `storage`
- `webRequest`
- `activeTab`

## Cookies and tracking

The extension does not set its own cookies.

The extension does not include advertising SDKs, analytics SDKs, or third-party tracking scripts.

Third-party services such as Google Scholar or Crossref may apply their own server-side logging or cookie practices when you use their websites or APIs. Those services are governed by their own privacy policies, not this extension's policy.

## Children's privacy

The extension is not directed to children and is intended for research and academic-use contexts.

## Changes to this policy

This policy may be updated if the extension's functionality or data practices change. Any updated version should be published with a revised "Last updated" date.

## Contact

If you have questions about this privacy policy, contact the extension publisher through the contact details provided in the Chrome Web Store listing or other official distribution channel for this extension.
