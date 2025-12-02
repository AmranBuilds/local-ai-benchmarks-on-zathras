# Local LLM Quantization Benchmarks

A comparative analysis of Local LLM performance. This project benchmarks the trade-offs between model quantization levels (Q4 vs Q8), inference speed, and response accuracy using Llama-3 on consumer hardware.

### Project Goals
* **Quantify Performance Loss:** Measure exactly how less capable a model gets when compressed to 4-bit.
* **Benchmark Inference Speed:** Record tokens-per-second on local hardware.
* **Optimize for Deployment:** Determine the sweet spot between speed and accuracy for local AI agents.
