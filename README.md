# HybridAI

Highly distributed AI systems increasingly execute inference
across heterogeneous cloud and edge infrastructures. The placement of
inference tasks along the computing continuum directly influences la-
tency behavior, scalability, and operational efficiency. Many existing con-
tinuum architectures rely on hierarchical task propagation between tiers,
introducing structural dependencies that may affect latency predictabil-
ity under dynamic load conditions. We evaluate three deployment strate-
gies, Cloud AI, Edge AI, and Hybrid AI using a YOLOv5-based vehicle
classification workload. We formulate a latency-centered analytical model
that expresses end-to-end inference delay as a function of network traver-
sal, execution time, and bounded computational capacity. The evalua-
tion further incorporates operational cost and CO2 emissions to quantify
resource-efficiency trade-offs. Controlled simulations under varying client
loads and inference intervals reveal distinct structural trade-offs: Cloud
AI provides high computational density at elevated cost; Edge AI mini-
mizes base latency but saturates under increasing workload; Hybrid AI
increases the effective saturation threshold while preserving near-edge
responsiveness. In our evaluation, Hybrid deployment reduces monthly
operating cost by 46.5% compared to Cloud AI while maintaining com-
parable emissions. These results demonstrate that hybrid deployment
without strict hierarchical offloading improves latency predictability and
resource efficiency in distributed AI systems.
