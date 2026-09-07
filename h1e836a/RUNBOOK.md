# h1e836a Incident 2026-09-03 Postmortem

## Summary

For 41 minutes the checkout API returned 502s for customers routed through the EU load balancer.

## Timeline

- 03:02 alerts fire
- 03:15 rollback started
- 03:43 recovered

## Action items

- Add a canary to the EU pool.
