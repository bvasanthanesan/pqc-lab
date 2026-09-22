\# Timing Analysis Notes



This section explores side‑channel vulnerabilities in PQC algorithms.



\## Objective

\- Understand how timing differences can leak information.

\- Document experiments with PQC implementations (Kyber, Dilithium).



\## Example Test Plan

\- Measure handshake times for classical RSA vs PQC Kyber.

\- Record variations in response times.

\- Analyze whether timing differences could be exploited.



\## Next Steps

\- Set up test environment with liboqs.

\- Collect timing data during TLS handshakes.

\- Document findings and mitigation strategies.



