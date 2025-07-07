This script implements *two* coupling mechanisms described in
Vakulenko & Zhokhin (2025) for modelling the emergence of artificial
consciousness:

    1. Broadcast coupling (feed-forward of the “winner” process) – C1
    2. Sin–arcsin phase coupling – C2

For each mechanism the script:

    • Simulates N independent feed‑forward neural processes
    • Applies the selected nonlinear inter‑process coupling
    • Records the network states over T time‑steps
    • Visualises:
        – Component‑wise time‑series (low‑amplitude oscillations)
        – Power spectrum (higher harmonics 12–70 Hz equivalent)
        – Phase portrait / strange attractor
        – Slow decay of the attractor envelope

The default hyper‑parameters are tuned for qualitative
demonstration; feel free to experiment.
