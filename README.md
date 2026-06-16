# Phantasm-DNS-OSINT
A browser-based  passive reconnaissance DNS OSINT visualization tool 

What it does when you scan a domain:

- Resolves A, AAAA, MX, NS, TXT, CAA, and SOA records via Google's DNS-over-HTTPS API
- Detects the CDN/DNS provider (Cloudflare, AWS, Vercel, etc.) and mail provider (Google Workspace, Microsoft 365, etc.)
- Probes 40 common subdomains (vpn, admin, jenkins, grafana, staging…) and shows which are live
- Analyzes SPF, DMARC, and DKIM with the actual record values shown
- Calculates a risk score out of 100 based on DNS hygiene with color-coded flags
- Auto-generates intelligence tags (e.g. "DMARC p=reject", "Load balanced (6 IPs)", "CI/CD infrastructure exposed")
- Logs every step in a live recon log

EDUCATIONAL PURPOSES ONLY !!!
