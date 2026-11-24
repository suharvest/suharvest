### Real-World Edge Solutions · Low-Cost Hardware, High-Performance Runtime

Leading Solutions at **Seeed Studio**. My focus is getting edge hardware running reliably in real scenarios — picking practical use cases and cost-effective devices (**RK3576/RK3588, RV1126B, SG2002, Hailo-8, Jetson Orin, ESP32**), then pushing them to production latency and throughput.

---

#### Selected Work

**On-Device Speech (Low-Latency, Offline-First)**
- [**rkvoice-stream**](https://github.com/suharvest/rkvoice-stream) — Streaming ASR (52 languages) + ~120 ms TTS on RK3576/RK3588 in one Docker command.
- [**openvoicestream**](https://github.com/Seeed-Solution/openvoicestream) — Real-time edge voice streaming runtime.
- [**jetson-voice-engine**](https://github.com/suharvest/jetson-voice-engine) / [**jetson-qwen3-speech**](https://github.com/suharvest/jetson-qwen3-speech) — Qwen3 ASR/TTS TensorRT deployment and validation toolkit for Jetson.
- [**rknn-matmul-parallel**](https://github.com/suharvest/rknn-matmul-parallel) — Open-source RKLLM alternative exploring dual-core NPU parallelism (~16 ms/token).

**Edge Vision for Production Scenarios**
- [**edgefallkit**](https://github.com/suharvest/edgefallkit) — 15 FPS multi-person fall detection across Jetson, Hailo, RKNN, and reCamera (C++).
- [**retail-vision**](https://github.com/Seeed-Solution/retail-vision) — Shared footfall tracking pipeline running across Hailo-8, Jetson, Rockchip NPU, and reCamera.
- [**screw-guard**](https://github.com/suharvest/screw-guard) — Cross-platform fastener inspection and assembly QA engine for edge cameras.
- [**eldercare-monitor**](https://github.com/suharvest/eldercare-monitor) — On-device eldercare safety app on reCamera Pro (RV1126B) combining YOLO11n-Pose fall detection and offline ASR.

**Robot Control & Embodied Interaction**
- [**rebot-armd**](https://github.com/Seeed-Solution/rebot-armd) & [**rebot-companion**](https://github.com/Seeed-Solution/rebot-companion) — Minimal Rust robot arm control runtime (single static binary, safety supervisor, web cockpit) with Python SDK and MCP server.
- [**reachy-claw**](https://github.com/suharvest/reachy-claw) — Sub-200 ms voice assistant for Reachy Mini powered by `sherpa-onnx` and OpenClaw.

**Solution Platform, Benchmarks & Agent Tooling**
- [**sensecraft-solutions**](https://github.com/suharvest/sensecraft-solutions) — Open IoT solution content and authoring/validation tooling for SenseCraft.
- [**laya-on-rk3588-jetson**](https://github.com/suharvest/laya-on-rk3588-jetson) — Model conversion recipes and measured latency benchmarks on RK3588 (509 ms) and Jetson Orin NX (18.9 ms).
- [**claude-rescue**](https://github.com/suharvest/claude-rescue) / [**agy-codex-rescue**](https://github.com/suharvest/agy-codex-rescue) — Multi-model dispatch and sandboxed CLI bridges for coding agent workflows.

---

#### Hardware & Runtime Stack
- **Devices**: Rockchip (RK3588 / RK3576 / RV1126B), NVIDIA Jetson Orin, Hailo-8, reCamera (SG2002), ESP32 / Wio Terminal
- **Stack**: C++, Rust, Python · TensorRT, RKNN, HailoRT, ONNX Runtime / `sherpa-onnx`
