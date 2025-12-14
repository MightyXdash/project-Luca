<img width="1536" height="1024" alt="hello_fox_mascot" src="https://github.com/user-attachments/assets/6e5f4a6f-dbcf-40ad-970d-52808b814551" />



# Project-Luca

Project-Luca is my open research initiative focused on building highly efficient artificial intelligence systems. The objective is not to maximize parameter count, but to maximize intelligence per parameter. Every design decision, including architecture, data composition, and training strategy, is optimized to reach a balance point where the model produces coherent and stable outputs without unnecessary computational overhead.

Rather than chasing novelty, I deliberately revisit and refine techniques that are often considered outdated. Through careful tuning and disciplined iteration, Project-Luca demonstrates that meaningful efficiency gains often come from refinement and constraint, not from constant reinvention.

Development has followed a strictly incremental path. The earliest prototype, Luca Nano-N1, was trained on only 160 KB of data and served as a minimal proof of concept. Luca Nano-N1.5 expanded this scale to approximately 14 MB. While both models were unstable and highly experimental, they provided essential insight into early scaling behavior, failure modes, and architectural sensitivity.

The current generation, Luca Nano-N2, represents a fundamental transition point for the project. N2 is trained on 24.5 GB of curated text, corresponding to approximately 6.5 billion tokens. This increase in scale results in a qualitative shift in behavior. Luca Nano-N2 represents a clear and decisive advancement in stability, coherence, and learning depth. Earlier iterations were intentionally limited experimental stages designed to probe constraints and weaknesses. N2 is the first version in which the system consistently exhibits stable token generation, and behavior sutable for practical evaluation.

Luca Nano-N2 is released in bfloat16 (BF16) rather than FP32, providing a better balance between numerical stability, performance, and memory efficiency. This choice enables faster inference and training while maintaining model quality.

***
**Model Status**

Luca Nano-N1 and Luca Nano-N1.5 should be treated strictly as experimental. They hallucinate heavily and are not suitable for reliable use. Luca Nano-N2 is currently in preview testing and is scheduled for public release within one week. This release marks the first iteration of Project-Luca that I consider meaningfully stable.

Access and Release Policy

I am not releasing the training code, datasets, or internal architectural implementation. Access is intentionally limited to the trained model and a minimal testing interface due to license type of my dataset. A small test codebase is provided exclusively for inference and evaluation, allowing users to run the model, observe its behavior, and verify performance characteristics. This approach preserves transparency at the usage level while keeping the full training pipeline private. though, I would be providing the research I did!

Project-Luca is not simply an experiment in training small models. It is a long-term foundation for efficient intelligence, disciplined research, and pushing the limits of what can be achieved with constrained hardware and carefully optimized design. The project exists to demonstrate that strong models are defined not by scale alone, but by how intelligently that scale is applied.

<img width="2560" height="1428" alt="horizontal_mascot_LN_preview (1)" src="https://github.com/user-attachments/assets/91dfca3a-ca5b-4e1f-8748-30fde2e2dd45" />

Next gen LN2 is expected to have a very high accuracy compared to many models from my own model family and many major companies! since I havn't done all my tests I can't confidently aprove that statement, I will be providing all documents after testing with the model. theoretically the model MUST out perform many high-end models!
