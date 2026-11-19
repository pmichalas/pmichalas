### Paris Michalas

Partner at [NetProjects](https://netprojects.com) (Internet Projects Ltd)

I build and test open models on Apple Silicon. Each port is checked against the original model before release. The builds are published on [huggingface.co/netprojects](https://huggingface.co/netprojects) and the code under [internet-projects](https://github.com/internet-projects).

**MLX ports**
- [h2o-lightning-mlx](https://github.com/internet-projects/h2o-lightning-mlx): H2O.ai's H2O-Lightning-4B decision model with H2O's official shim (two-way reading, Box questions)
- [glide-mlx](https://github.com/internet-projects/glide-mlx): Fastino's GLiDE 27B decision model
- [granite-switch-mlx](https://github.com/internet-projects/granite-switch-mlx): IBM Granite Switch 4.1.1 (chat, decision and guardian adapters)
- [autotrust-jev27b-mlx](https://github.com/internet-projects/autotrust-jev27b-mlx) and [autotrust-jev35b-mlx](https://github.com/internet-projects/autotrust-jev35b-mlx): AutoTrust JEV decision models
- [dory-mlx](https://github.com/internet-projects/dory-mlx): NVIDIA Nemotron-Labs Dory 1.0 4B, a looped reasoning model, plus [mlx-lm PR 1988](https://github.com/ml-explore/mlx-lm/pull/1988)
- [sensenova-loop-mlx](https://github.com/internet-projects/sensenova-loop-mlx): SenseNova-Loop-9B, a looped model with two-stream mHC, image input and ~1.7× faster MTP decoding (6 / 8 / 4-bit and bf16 MLX builds; Preview builds too)
- [cosmos3-edge-mlx](https://github.com/internet-projects/cosmos3-edge-mlx): NVIDIA Cosmos3-Edge, a vision-language reasoner for text, images and video (8 / 6-bit builds) and a video generator (8-bit / bf16 builds)
- [dspine-hybrid-mlx](https://github.com/internet-projects/dspine-hybrid-mlx): Tencent DSpine speculative decoding for Qwen3.8-27B, a hybrid model (2.0x faster on 4-bit, 2.9x on 8-bit, 4.3x on bf16)
- [nemotron-retrieval-mlx](https://github.com/internet-projects/nemotron-retrieval-mlx): NVIDIA Nemotron 3.5 Embed / Rerank retrieval models, text and page images
- [Qwen-Concept-27B-MLX](https://huggingface.co/netprojects/Qwen-Concept-27B-MLX-6bit): Concept Country's Qwen Concept 27B, Qwen3.8-27B edited to reach answers with less thinking; text and images (bf16 / 8 / 6 / 4-bit builds on Hugging Face, runs with stock mlx-lm and mlx-vlm)
- [Laplace-1-Atlas-MLX](https://huggingface.co/netprojects/Laplace-1-Atlas-MLX-6bit): Juneo Lab's Laplace-1-Atlas, a 27B decision model that scores candidates in one forward pass (JevBench 91.8% at 6-bit) (bf16 / 8 / 6 / 4-bit builds on Hugging Face, runs with stock mlx-lm and mlx-vlm)
- [Laplace-1-Vector-MLX](https://huggingface.co/netprojects/Laplace-1-Vector-MLX-6bit): Juneo Lab's Laplace-1-Vector, a 4B decision model that scores candidates in one forward pass (JevBench 79.2% at 6-bit) (bf16 / 8 / 6 / 4-bit builds on Hugging Face, runs with stock mlx-lm)
- [SenseNova-6.8-Code2Video-MLX](https://huggingface.co/netprojects/SenseNova-6.8-Code2Video-MLX-6bit): SenseNova's SenseNova-6.8-Code2Video, a 27B agentic model that writes, renders and reviews short videos as code (bf16 / 8 / 6 / 4-bit builds on Hugging Face, runs with stock mlx-vlm)
- [Mage-VL-Cowork-MLX](https://huggingface.co/netprojects/Mage-VL-Cowork-MLX-6bit): Microsoft's Mage-VL-Cowork, a 4B computer-use agent that works a desktop through GUI actions and a shell (bf16 / 8 / 6 / 4-bit builds on Hugging Face, runs with stock mlx-vlm)
- [Qwen3.8-27B-pi-adapted-MLX](https://huggingface.co/netprojects/Qwen3.8-27B-pi-adapted-MLX-6bit): harness-hub's pi coding-agent LoRA merged into Qwen3.8-27B (Terminal-Bench 2.1 39.5% → 55.8% under pi, publisher's figures); thinking off, vision and MTP kept (6 / 8 / 4 / 3 / 2.5-bit, bf16 and an mlx-lm adapter on Hugging Face; [GGUF](https://huggingface.co/netprojects/Qwen3.8-27B-pi-adapted-GGUF) down to IQ2_M for llama.cpp)
- [Qwen3.8-27B-opencode-adapted-MLX](https://huggingface.co/netprojects/Qwen3.8-27B-opencode-adapted-MLX-6bit): harness-hub's OpenCode coding-agent LoRA merged into Qwen3.8-27B (SWE-bench Pro hard-51 35.3% → 51.0% under OpenCode, publisher's figures); thinking off, vision and MTP kept (6 / 8 / 4 / 3-bit, bf16 and an mlx-lm adapter on Hugging Face; [GGUF](https://huggingface.co/netprojects/Qwen3.8-27B-opencode-adapted-GGUF) down to IQ2_M for llama.cpp)
- [DaisyRose-27B-MLX](https://huggingface.co/netprojects/DaisyRose-27B-MLX-6bit): RadixArk's reinforcement-learned Qwen3.8-27B (Terminal Bench 4.1 5.6 → 12.0, publisher's figures); thinking model, vision and MTP kept (6-bit / 8-bit / 4-bit / 3-bit / 2.5-bit / bf16 on Hugging Face)
