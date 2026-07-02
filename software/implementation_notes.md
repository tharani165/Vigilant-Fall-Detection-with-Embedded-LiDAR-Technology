# Implementation Notes

## Academic Research Project

This project was developed as an academic research project and invention disclosure, not as a commercial software product. It explores the feasibility of a privacy-preserving, LiDAR-based approach to fall detection, and formed the basis of a patent application.

## What This Repository Focuses On

This repository is documentation-first. It focuses on:

- The research problem and motivation
- The proposed system architecture and hardware design
- The workflow connecting sensing, detection, and alerting
- Patent and publication documentation
- Experimental results and demonstration materials

## What This Repository Is Not

- It is not a production software release.
- It does not include a maintained, installable codebase.
- Any code shown elsewhere in this repository (see [code/README.md](../code/README.md)) is conceptual, intended only to illustrate the system architecture — it has not been packaged, tested, or hardened for real-world deployment.
- Full production software developed during the project is not publicly available.

## Design Approach

At a high level, the proposed system:

1. Uses a LiDAR sensor for continuous, privacy-preserving monitoring (point-cloud data rather than always-on video).
2. Processes sensor data locally on an edge device (NVIDIA Jetson Nano) rather than in the cloud.
3. Selectively activates a camera only after a potential fall is flagged, for visual confirmation.
4. Sends alert notifications (e.g. via email/SMTP) to caregivers when a fall is confirmed.

Details of the detection approach, algorithms, and evaluation are documented in the patent application and reference paper in [docs/](../docs/), rather than restated here as unverified specifics.

## Status

| Aspect | Status |
|--------|--------|
| Research & system design | Complete |
| Patent application | Filed (see [docs/](../docs/)) |
| Prototype | Built for proof-of-concept purposes |
| Production software | Not publicly available |
| Clinical validation | Not conducted |

## Disclaimer

This repository documents academic research. Nothing in it is intended for clinical use, medical device deployment, or production use without independent validation, regulatory approval, and professional software engineering.
