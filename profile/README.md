<p align="center">
  <img src="https://raw.githubusercontent.com/netx-aiops/.github/main/profile/netx-aiops-logo.png" alt="NetX AIOps" width="820" />
</p>

<p align="center"><b>Autonomous operations for modern networks.</b></p>

---

**NetX AIOps** is a public workspace for autonomous network Root Cause Analysis (RCA) evaluation 
resources. Core agent code remains private; selected evaluation datasets, benchmarks, and 
documentation are published here.

**NetX AIOps** builds AI agents that diagnose network faults the way a proof is built, deriving 
the **root cause** from streaming syslog and proving every symptom against diagnostic evidence 
gathered from the devices (and/or any additional data sources) in real time.

**No hand-written fault descriptions. No hard-coded workflows. No ground-truth leakage.**

We publish the evaluation dataset to make the benchmark transparent and reproducible: We run 
purely on network-wide device logging, the most widely established monitoring baseline
(additional telemetry sources welcome), but the core evaluation starts from logs only, without 
prior assumptions that reveal the injected fault or leak the expected answer.

The focus is autonomous multi-hop RCA agents that dynamically plan, gather evidence, and test 
hypotheses across devices. Unlike fixed prompt workflows, this approach is designed to be evaluated 
and improved end to end through optimization loops, enabling the system to learn from measured 
outcomes and progressively improve its diagnostic behavior, including with smaller local models (SLMs) 
and fully air-gapped on-prem deployments.

- **Autonomous RCA** across OSPF, IS-IS, BGP, Segment Routing, and SRv6, and many more
- **Ontology-grounded reasoning:** symbolic inference paired with SLM agents, over live IOS-XR networks
- **Reproducible evaluation** against gold benchmarks on live labs

### Open resources

- [**xrd-scenarios-datasets**](https://github.com/netx-aiops/xrd-scenarios-datasets) — a gold-standard benchmark of 60 IOS-XR fault scenarios for evaluating autonomous RCA agents · `CC-BY-4.0`

<sub>© 2026 NetX AIOps</sub>
