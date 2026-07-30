# Linear Technology Corporation

Linear Technology Corporation (listed as "Linear Technologies" in the Mayfield portfolio harvest) was an
American analog semiconductor company founded in 1981 and headquartered in Milpitas, California. It
designed and manufactured high-performance analog integrated circuits — power management, data
converters, amplifiers, voltage references, interface and RF products — for industrial, automotive,
communications, computing, and military/aerospace markets.

Backed early by Mayfield and Kleiner Perkins, it went public on NASDAQ in 1986 under the ticker LLTC and
was **acquired by Analog Devices in March 2017**.

## Status: acquired — no API surface

The company no longer operates independently. Verified by live probe (2026-07-19):

- `https://www.linear.com/` `301` → `https://www.analog.com/en/landing-pages/001/adi-linear-combine/index.html?source=ltc`
- Every path, including `/.well-known/*`, redirects to the same Analog Devices landing page
- `linear.com` and `analog.com` share the registrar CSC Corporate Domains and CSCDNS name servers
- No developer portal, documentation, OpenAPI, SDK, or public API surface exists

As an analog component manufacturer it never operated a web/developer API program, so there is nothing to
enrich beyond identity. The successor developer surface is catalogued in the API Evangelist network under
[`analog-devices`](../analog-devices/).

**Duplicate note:** `all/linear-technology/` is the same company harvested from the Kleiner Perkins
portfolio. These two stubs should be merged in a later dedupe pass. Both are distinct from `all/linear/`
and `all/linear-app/` (Linear, the issue-tracking product at linear.app).

Backed by: mayfield, kleiner-perkins
