# Bottleneck Solutions

Bottleneck Solutions is a read-only operational dashboard for emergency department throughput. It helps charge nurses, charge physicians, and ED operations leaders identify delays in patient flow such as long door-to-provider times, boarding delays, and lab/imaging turnaround bottlenecks.

## Intended users
- Charge nurses
- Charge physicians
- ED operations managers

## Epic integration summary
- Read-only integration
- Designed for Epic-compatible FHIR and normalized event data
- Initial non-production testing uses backend-service OAuth 2.0 and patient read access
- No order entry, documentation, or write-back actions in the MVP

## Data use
The application is intended to use the minimum necessary data to support operational throughput monitoring, including timing-oriented encounter and workflow signals used to calculate:
- door-to-doc
- ED length of stay
- boarding time
- lab turnaround time
- imaging turnaround time

## Privacy and safety posture
- Read-only in the MVP
- No treatment recommendations or clinical decision-making
- Designed to support de-identified or pseudonymous operational views where feasible

## Support
For product or integration questions, contact: alex.theiler@gmail.com
