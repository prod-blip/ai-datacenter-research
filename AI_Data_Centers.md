# AI Data Centers — Living Research Notes

Started: 17 October 2026. Scope: India first, with global comparisons.

## Research approach
Separate established concepts, claims to verify, open questions, and company/market tracking. This is a learning notebook, not investment advice.

## 1. What makes an AI data center different?
AI workloads, particularly model training, may require dense clusters of accelerators, high-throughput networking, fast data access, substantial power, and advanced cooling.

**Claim to refine:** More GPUs necessarily mean more floor space. High-density racks can instead increase computing power per square meter while requiring far more electricity and cooling per rack.

## 2. High-performance computing (HPC)
- **GPU:** A highly parallel processor suited to many AI computations.
- **NPU:** Specialized neural-network accelerator, often designed for efficient inference. It does not literally recreate the brain's pathways.
- **TPU:** Google's custom AI accelerator family for tensor-intensive machine learning.


## 3. Memory, storage, and virtualization
- **SSD:** Persistent NAND-flash storage. **NVMe** is a high-performance interface/protocol commonly used for SSD access.
- **HBM:** High-bandwidth stacked DRAM, positioned close to accelerators; **HBM is itself a form of DRAM**.
- **Virtualization:** Dividing or abstracting physical compute, storage, and networking resources into logical environments.

Important distinction: HBM is working memory for computation, whereas SSDs provide persistent storage.

Sources: [IBM SSDs](https://www.ibm.com/think/topics/solid-state-drives), [IBM virtualization](https://www.ibm.com/topics/virtualization).

## 4. Networking
- Copper and optical connections link servers, racks, storage, and external networks. The exact mix varies with distance and architecture.
- Software-defined networks and overlays manage logical networks on top of physical infrastructure.
- Distributed AI training requires substantial accelerator-to-accelerator communication; bandwidth and latency matter.

Source: [IBM software-defined data center](https://www.ibm.com/think/topics/software-defined-data-center).

## 5. Power and cooling
- **Liquid cooling:** Liquid coolant (not necessarily water) transports heat away from high-density hardware.
- **Hot/cold aisle containment:** Separates hot exhaust air and cold intake air to reduce inefficient mixing.
- **PUE:** Total facility energy divided by IT equipment energy. Lower generally means more efficient supporting infrastructure; the theoretical minimum is 1.0.

## 6. India vs. global market — to research
Compare installed capacity, electricity supply and prices, connectivity, land, cooling/water, regulation, AI demand, capex, utilization, and investment returns.

## 7. Company and stock tracker — to build
Categories: data center owners/operators, hyperscalers, GPU and memory suppliers, networking suppliers, electrical and cooling suppliers, construction companies. Track exchange/ticker, revenue exposure, capex, utilization, valuation, stock performance, and risks.

## 8. Open questions
1. How do traditional cloud data centers, AI training clusters, and AI inference centers differ?
2. What does a complete AI rack contain, and how do GPU, HBM, SSD and networking connect?
3. What do MW, rack density, PUE, capex per MW, and utilization mean?
4. Who owns which layer of infrastructure, and how do participants make money?
5. Which Indian listed companies have direct versus indirect exposure?
6. How does India compare with the US and other global hubs?

## Research log
- **2026-10-17:** Organized initial user notes on HPC, storage, networking, power, and cooling. Added technical corrections and questions. Company-specific market research remains pending.
