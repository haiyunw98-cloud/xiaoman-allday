# 小满全天记 · 第三方组件

中文转写使用 SenseVoiceSmall，由 FunAudioLLM / Alibaba Group 提供。
随包权重为 sherpa-onnx 提供的 int8 ONNX 转换版本，遵循 FunASR 模型开源协议 v1.1。
原模型：https://huggingface.co/FunAudioLLM/SenseVoiceSmall
转换版本：https://github.com/k2-fsa/sherpa-onnx/releases/tag/asr-models
完整模型协议见 licenses/SENSEVOICE_MODEL_LICENSE.txt。

推理及音频组件：sherpa-onnx（Apache-2.0）、llama.cpp（MIT）、whisper.cpp（MIT）、Silero VAD（MIT）。
仅随包提供 SenseVoice 和 VAD 权重，不包含本地大语言模型。
云端整理使用安装者自行配置的阿里云百炼账号。

出处：
- https://github.com/k2-fsa/sherpa-onnx
- https://github.com/ggml-org/llama.cpp
- https://github.com/ggml-org/whisper.cpp
- https://github.com/snakers4/silero-vad
