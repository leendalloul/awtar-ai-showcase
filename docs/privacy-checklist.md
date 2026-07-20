# Publication Privacy Checklist

Complete this checklist before committing, pushing, sharing, or publishing any file, screenshot, recording, document, issue, or release.

If any item is uncertain, do not publish the material until it has been reviewed and safely redacted or removed.

## Secrets and Credentials

- [ ] No API keys are visible or embedded.
- [ ] No access tokens, refresh tokens, session tokens, or authorization headers are present.
- [ ] No Salla credentials or integration secrets are present.
- [ ] No database connection strings are present.
- [ ] No passwords, private keys, certificates, signing secrets, or webhook secrets are present.
- [ ] No environment files or copied environment-variable values are included.

## Customer and Personal Data

- [ ] No customer phone numbers are visible.
- [ ] No customer names are visible.
- [ ] No customer messages or conversation history are visible.
- [ ] No private email addresses are visible.
- [ ] No profile photos, account details, addresses, appointment details, or order details are visible.

## Business and Platform Identifiers

- [ ] No internal URLs, private hostnames, callback URLs, or non-public domains are visible.
- [ ] No business IDs, tenant IDs, account IDs, or internal identifiers are visible.
- [ ] No Meta IDs, phone-number IDs, app IDs, or business-account identifiers are visible.
- [ ] No private repository names, branch names, commit details, or internal file paths are visible.

## Application and Build Output

- [ ] No source code or proprietary business logic is included.
- [ ] No system prompts, prompt fragments, internal AI instructions, or evaluation data are included.
- [ ] No database schemas, table names, SQL models, queries, or data exports are included.
- [ ] No source maps or debug bundles are included.
- [ ] No logs, stack traces, monitoring events, request payloads, or response payloads are included.
- [ ] No production configuration or security implementation details are included.

## Screenshot and Recording Review

- [ ] Every screenshot has been reviewed at full resolution.
- [ ] Browser tabs, bookmarks, address bars, history suggestions, downloads, and extensions reveal nothing sensitive.
- [ ] Internal dashboards, admin tools, monitoring tools, and developer consoles are closed or fully redacted.
- [ ] Notifications, menu-bar content, clock/calendar details, and other unrelated personal information are removed.
- [ ] Hidden, cropped, blurred, or reflected content cannot be recovered or read.
- [ ] Screenshot metadata has been reviewed and removed where appropriate.
- [ ] Only fictional or explicitly approved demonstration data is shown.

## Final Repository Review

- [ ] The repository contains only intended documentation and reviewed visuals.
- [ ] File history has been checked for previously committed sensitive content.
- [ ] Ignored and untracked files have been reviewed before publication.
- [ ] Links do not expose private resources or grant unintended access.
- [ ] A second person or a separate final review has checked all public materials where possible.
- [ ] The public repository visibility and included files have been confirmed immediately before publishing.
