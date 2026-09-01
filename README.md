# WorkerConnect prototype

A dependency-free, responsive browser prototype for the first delivery stage of WorkerConnect. It presents three coherent role experiences in one live workspace:

- **Customer app:** service discovery, job creation, configurable labour count/duration, price calculation, and a search dispatch confirmation.
- **Worker app:** verified worker profile, online/offline availability, privacy-aware request card, acceptance/rejection, and an assignment confirmation state.
- **Admin console:** operational metrics, live job activity, risk/verification/dispute queue, and recent job monitoring.

## Run locally

This prototype is static. Use any local HTTP server, for example:

```bash
python3 -m http.server 4173
```

Then visit `http://localhost:4173`.

## Product boundaries

The current version intentionally uses sandbox/sample data. Real matching, atomic assignment, authentication, payment verification, location telemetry, arrival-code validation, KYC, notifications, audit events, and authorization must be server-side capabilities in the next implementation stage. No payment or production secrets are present in this repository.
