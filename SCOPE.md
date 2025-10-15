# WebScanPro — Project Scope

## Project goal
Build a safe, ethical, and educational web-application security testing tool (WebScanPro) that performs passive security analysis, form discovery, and report generation. Active scans are out-of-scope by default and only allowed with explicit authorization.

## In-scope
- Polite web crawler (respects robots.txt, same-domain default, depth/page limits, rate limiting)
- Passive checks: security headers, cookie flags, TLS expiry checks, server info (informational)
- Form discovery (no submissions)
- Streamlit UI to run scans and export JSON/PDF
- Containerization (Docker + docker-compose) for dev with a local test target (Juice Shop)
- Documentation and ethics notice

## Out-of-scope (without explicit authorization)
- Exploit payloads or automated offensive scans
- Unauthorised testing of external domains
- Automated form submissions with payloads

## Acceptance criteria
- The app runs locally and can perform passive scans against a local test target.
- Findings export to JSON and PDF.
- ETHICS.md present and visible before any active scan is allowed.
