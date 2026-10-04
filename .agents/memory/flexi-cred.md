---
name: Flexi Cred product requirements
description: Branding and browser-only document handling rules for the loan-management demo.
---

Use Flexi Cred as the lender's user-facing brand across the app and artifact metadata. Collect PAN documents during account creation, and request address proof only for home-loan applications.

The product is frontend-only. PAN and address-proof uploads stay in browser storage and are not sent to a server.

**Why:** the user specified the Flexi Cred name, conditional proof uploads, and a browser-only demo scope.

**How to apply:** Keep user-facing branding consistent, preserve existing browser-stored demo data when updating storage behavior, and do not add server-side document storage or imply that files are uploaded securely unless the user changes the scope.