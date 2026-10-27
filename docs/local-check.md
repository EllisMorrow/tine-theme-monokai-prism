# Local check summary

- Theme: Monokai · Prism 0.1.1
- Manifest SHA-256: `4985c12844e53d675426f680f6871ad4f0ba7eabfa1f0f8393b5eb1e4c436ceb`
- Official Tine theme checker: **passed**, 0 errors, 0 warnings.
- Chromium fixture: both modes each contain 21 tokens; light → dark → light switching checked.
- Fixture contrast: body, heading, link and tag on the main canvas; inline code, mark and selected body on their designated surfaces.
  - Light: body 8.96:1, title 8.96:1, link 5.29:1, tag 5.29:1, code 8.19:1, mark 8.1:1, chosen 8.03:1.
  - Dark: body 13.94:1, title 13.94:1, link 5.67:1, tag 5.67:1, code 11.96:1, mark 11.6:1, chosen 11.43:1.

The Chromium check is a synthetic fixture using a cached Tine CSS snapshot. It is not a full Tine application test, and does not establish all states, derived colors or other platforms. Screenshots, where provided, are real application captures and are documented separately in the README.

Reproduce the format check with Tine’s `npm run theme:check -- <theme-directory> --json`. The fixture results describe the specific combinations above and are not an official audit or an all-text accessibility claim.
