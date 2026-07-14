<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0f172a,45:4338ca,100:06b6d4&height=210&section=header&text=ssG12333&fontSize=58&fontColor=ffffff&fontAlignY=35&desc=AI%20Infra%20%C2%B7%20Model%20Quantization%20%C2%B7%20Local%20RAG%20%C2%B7%20RL&descSize=16&descAlignY=56&animation=fadeIn" alt="ssG12333 profile header" />

<p>
  <a href="https://github.com/ssG12333?tab=followers"><img src="https://img.shields.io/github/followers/ssG12333?label=Followers&style=flat&color=6366f1" alt="GitHub followers" /></a>
  <img src="https://komarev.com/ghpvc/?username=ssG12333&label=Profile%20Views&color=06b6d4&style=flat" alt="Profile views" />
  <a href="mailto:1336488531@qq.com"><img src="https://img.shields.io/badge/Email-Contact%20Me-0f172a?style=flat&logo=gmail&logoColor=white" alt="Email" /></a>
</p>

<h3>Hi, I'm ssG12333 👋</h3>

<p><strong>在读研究生 · AI Infra / 模型量化 / 强化学习</strong></p>

<p><sub>Master's student building systems from first principles — from bits and kernels to retrieval and agents.</sub></p>

</div>

---

## About me · 关于我

我关注高效 AI 系统如何从底层表示一路走到真实部署：浮点位布局、量化算法、推理内核、检索系统，以及 Agent 工作流。

- 🔬 **模型量化**：IEEE 754 → PTQ / QAT → GPTQ / AWQ → LLaMA 4-bit
- ⚙️ **AI Infra**：PyTorch → ONNX → TensorRT / llama.cpp → vLLM
- 🤖 **智能系统**：Local RAG · ReAct Agent · PPO / DDPG
- 📝 **源码即文档**：不止调用 API，更关注算法为什么成立、框架内部如何实现

> Build it. Measure it. Read the source. Then explain it clearly.

## Featured projects · 精选项目

<table>
  <tr>
    <td width="50%" valign="top">
      <h3 align="center"><a href="https://github.com/ssG12333/agentRAG">🔎 agentRAG</a></h3>
      <p>从零搭建的本地轻量 RAG Agent。手写文档分块、向量检索与生成管道，继续推进 C++ IVF-PQ、BM25、ReAct 和 KV Cache 优化。</p>
      <p><code>Python</code> <code>C++17</code> <code>llama.cpp</code> <code>ONNX</code></p>
      <p><b>Now:</b> Phase 1 MVP ✅ · Phase 2 C++ retrieval 🚧</p>
    </td>
    <td width="50%" valign="top">
      <h3 align="center"><a href="https://github.com/ssG12333/AI-Infra-Inference-Notes">🧠 AI-Infra-Inference-Notes</a></h3>
      <p>从 ncnn 到 vLLM 的 AI Infra 系统学习仓库，覆盖算子、图优化、量化、推理引擎、KV Cache 与高性能 Serving。</p>
      <p><code>PyTorch</code> <code>ONNX</code> <code>TensorRT</code> <code>vLLM</code></p>
      <p><b>Scope:</b> 9 modules · 24,000+ lines · ongoing</p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3 align="center"><a href="https://github.com/ssG12333/QuantLab">📐 QuantLab</a></h3>
      <p>模型量化深度学习笔记：从 FP32 位布局、PyTorch QAT 源码到 LLM PTQ / QAT 与端侧部署。</p>
      <p><code>QAT</code> <code>PTQ</code> <code>GPTQ</code> <code>QLoRA</code></p>
      <p><b>Roadmap:</b> 9 stages · Stage 0–1 documented · ongoing</p>
    </td>
    <td width="50%" valign="top">
      <h3 align="center">🧪 Current focus</h3>
      <p>把学习路线变成可运行、可验证、可复现的工程：</p>
      <ul>
        <li>C++ IVF-PQ / K-Means 检索内核</li>
        <li>LSQ 可学习步长量化</li>
        <li>本地 RAG 与 Agent 推理优化</li>
      </ul>
      <p><b>Principle:</b> baseline first · one variable at a time</p>
    </td>
  </tr>
</table>

## Toolbox · 技术栈

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=cplusplus&logoColor=white" alt="C++" />
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white" alt="PyTorch" />
  <img src="https://img.shields.io/badge/ONNX-005CED?style=for-the-badge&logo=onnx&logoColor=white" alt="ONNX" />
  <img src="https://img.shields.io/badge/CUDA-76B900?style=for-the-badge&logo=nvidia&logoColor=white" alt="CUDA" />
  <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=111827" alt="Linux" />
</p>

| Direction · 方向 | Stack · 技术 |
|:--|:--|
| Inference & Deployment | PyTorch · ONNX Runtime · TensorRT · llama.cpp · vLLM |
| Model Quantization | PTQ / QAT · LSQ · GPTQ / AWQ · QLoRA / NF4 |
| Retrieval & Agents | Dense / Sparse Retrieval · RRF · Reranker · ReAct · KV Cache |
| Reinforcement Learning | Gymnasium · PPO / DDPG · Stable Baselines 3 |

## Learning path · 学习路线

```text
DONE   PyTorch QAT: Eager / FX / PT2E + prepare_qat_fx source dive
NOW    LSQ from scratch + C++ IVF-PQ retrieval core
NEXT   AdaRound / FlexRound / GPTQ mathematical kernels
LATER  YOLOv8 QAT ablations · PPQ / AIMET · LLM quantization deployment
```

<div align="center">

<h3>A tiny pixel farm between builds 🐾</h3>

<a href="https://github.com/devxb/gitanimals">
  <img src="https://render.gitanimals.org/farms/ssG12333" width="600" alt="Gitanimals farm" />
</a>

<br />

<a href="https://github.com/ssG12333">GitHub</a>
·
<a href="mailto:1336488531@qq.com">Email</a>

<br /><br />

<b>如果这些项目对你有帮助，欢迎留下一个 Star ⭐</b><br />
<sub>If you find something useful here, a star is always appreciated.</sub>

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0f172a,45:4338ca,100:06b6d4&height=100&section=footer" alt="footer" />

</div>
