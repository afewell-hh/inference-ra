# OPG‑64 — Distributed Inference: Rail‑Optimized Clos (CX7 1×400G; BF3 2×200G; Air)

Adds a back‑end fabric for cross‑host parallelism. With placement aligned to first‑hop rail domains, most collectives stay leaf‑local, dramatically reducing spine traffic; front‑end remains multi‑tenant with converged storage.

Attributes
- Back‑end: single plane (rail‑optimized); CX7 1×400G per GPU
- Front‑end: BF3 2×200G per server (L3MH)
- Storage: converged into FE
- Gateway: distributed x86 for ingress/egress
- QoS: RDMA enabled for back‑end; FE/App and Control prioritized accordingly

Assets (placeholders; to be populated)
- connectivity-map.csv, bom.yaml, wiring.yaml, vpc.yaml, diagrams/
