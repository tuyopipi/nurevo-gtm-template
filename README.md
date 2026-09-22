# Nurevo WebMCP — Google Tag Manager Template

Add Nurevo to your website with a single Google Tag Manager tag. Nurevo helps
your forms get completed and makes your site legible to AI answer engines and
agents (AEO / WebMCP), from one lightweight script.

## What this template does

This template loads the Nurevo script on your pages using your Nurevo **Site Key**.
Once active, Nurevo provides:

- **Form optimization** — reads your form structure, assists input, and reports
  where visitors drop off (anonymized) so completion rates improve.
- **AEO (Answer Engine Optimization)** — publishes schema.org structured data
  and metadata so AI search engines and assistants understand and correctly
  represent your site.
- **WebMCP** — exposes your forms to AI agents so agent-driven actions
  (bookings, inquiries) can complete reliably.

No coding is required. All free/paid features are handled by the Nurevo service;
this template only loads the script.

## Prerequisites

- A Nurevo account and a **Site Key** (free): https://nurevo.jp/

## How to use

1. In Google Tag Manager, add a new tag and select **Nurevo WebMCP**.
2. Enter your **Site Key**.
3. Set the trigger to **Initialization - All Pages** (recommended).
4. Publish your container.

## Configuration

| Field | Required | Description |
|-------|----------|-------------|
| Site Key | Yes | The key issued to your site by Nurevo. |



## Privacy

Nurevo collects anonymized form-interaction data (which field, which error,
which step) to compute completion and drop-off analytics. Email and phone
values are masked before leaving the page. See the Nurevo Privacy Policy at
https://nurevo.jp/ for details.

## Support

- Website: https://nurevo.jp/
- Documentation: https://nurevo.jp/#install

## Changelog

### 1.0.0
- Initial release.
