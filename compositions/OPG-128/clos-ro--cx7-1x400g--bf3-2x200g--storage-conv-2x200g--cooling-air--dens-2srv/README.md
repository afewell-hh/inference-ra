# OPG‑128 — Distributed Inference: Rail‑Optimized Clos (CX7 1×400G; BF3 2×200G; Air)

Adds a back‑end fabric for cross‑host coordination while maintaining a multi‑tenant FE with converged storage. Aligning tenant placement to first‑hop rail domains keeps most collectives leaf‑local, dramatically reducing spine traffic.

Attributes
- Back‑end: rail‑optimized; CX7 1×400G per GPU
- Front‑end: BF3 2×200G per server (L3MH)
- Storage: converged into FE
- Gateway: distributed x86 for ingress/egress
- QoS: RDMA enabled for back‑end only; FE/App/Control prioritized to protect latency and telemetry

Assets (placeholders; to be populated)
- connectivity-map.csv, bom.yaml, wiring.yaml, vpc.yaml, diagrams/
