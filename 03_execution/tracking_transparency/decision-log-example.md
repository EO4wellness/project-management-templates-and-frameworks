# Decision Log — Example  
*Project: Paw Snacks Puppy Treats — Website Launch*

## Decision Log Table

| ID | Date | Decision | Description / Context | Options Considered | Final Rationale | Approved By | Impact | Status |
|----|------|----------|-----------------------|---------------------|------------------|-------------|--------|--------|
| DEC-001 | 2026-08-03 | Homepage Hero Graphic Selection | Final homepage hero image needed for UAT readiness | Option A: Puppy in kitchen; Option B: Puppy with treats; Option C: Product-only hero | Option B aligns best with brand identity and tested highest in quick stakeholder review | Marketing Lead, Product Owner | Enables UAT to begin on time | Approved |
| DEC-002 | 2026-08-04 | Payment Gateway Testing Approach | Sandbox instability required alternative testing plan | Option A: Continue sandbox testing; Option B: Switch to backup provider; Option C: Parallel testing | Option A chosen with escalation to provider; avoids delay and avoids integration rework | Engineering Manager | Keeps testing on schedule if provider resolves issue quickly | Approved |
| DEC-003 | 2026-08-05 | Fallback Images for Licensing Delay | Licensing delay risked homepage launch | Option A: Wait for vendor; Option B: Use temporary fallback images | Option B chosen to avoid schedule slip; vendor approval still pending | Marketing Lead | Protects schedule; minor temporary scope change | Approved |

---

## Notes

- DEC-001 directly supports UAT readiness and is linked to Issue ISS-002 (image licensing).  
- DEC-002 is tied to Issue ISS-001 (payment gateway instability).  
- DEC-003 mitigates a medium-severity risk and prevents schedule slippage.  
