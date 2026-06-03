<div align="center">
  <picture>
    <source srcset="figures/MiniMaxLogo-Dark.png" media="(prefers-color-scheme: dark)">
      <img src="figures/MiniMaxLogo-Light.png" width="60%" alt="MiniMax">
    </source>
  </picture>
</div>
<hr>

<div align="center" style="line-height: 1.4; font-size:16px; margin-top: 30px;">
  Join Our
  <a href="https://platform.minimaxi.com/docs/faq/contact-us" target="_blank" style="font-size:17px; margin: 2px;">
    💬 WeChat
  </a> |
  <a href="https://discord.com/invite/DPC4AHFCBw" target="_blank" style="font-size:17px; margin: 2px;">
    🧩 Discord
  </a>
  community.
</div>
<div align="center" style="line-height: 1.2; font-size:16px;">
  <a href="https://agent.minimax.io/" target="_blank" style="display: inline-block; margin: 4px;">
    MiniMax Agent
  </a> |
  <a href="https://platform.minimax.io/docs/guides/text-generation" target="_blank" style="display: inline-block; margin: 4px;">
    ⚡️ API
  </a> |
  <a href="https://github.com/MiniMax-AI/MiniMax-MCP" style="display: inline-block; margin: 4px;">
    MCP
  </a> |
  <a href="https://www.minimax.io" target="_blank" style="display: inline-block; margin: 4px;">
    MiniMax Website
  </a>
</div>
<div align="center" style="line-height: 1.2; font-size:16px; margin-bottom: 30px;">
  <a href="https://huggingface.co/MiniMaxAI" target="_blank" style="margin: 2px;">
    🤗 Hugging Face
  </a> |
  <a href="https://github.com/MiniMax-AI/MiniMax-M3" target="_blank" style="margin: 2px;">
    🐙 GitHub
  </a> |
  <a href="https://www.modelscope.cn/organization/MiniMax" target="_blank" style="margin: 2px;">
    🤖️ ModelScope
  </a>
</div>

# MiniMax-M3 is Coming

**MiniMax-M3** is the next generation of the MiniMax series, building on the agent harness, software engineering, and professional-work foundations established by [MiniMax-M2.7](https://github.com/MiniMax-AI/MiniMax-M2.7). The model is not yet released — this repository exists so the community can share what they need next.

## We Want Your Feedback

Before M3 lands, we are listening. If you are using **MiniMax-M2.7** (via the API, Agent, or locally) and have something to say about it, please tell us — every report directly shapes M3.

We are especially interested in:

- 🐛 **Bugs and regressions** — anything that broke, hallucinated, or behaved unexpectedly in M2.7.
- 💡 **Capability requests** — what M2.7 still can't do well for your workload (agent harnesses, SWE, professional work, entertainment, multilingual, long context, tool use, …).
- 📊 **Benchmark gaps** — public or internal evals where you would like to see M3 improve.
- 🧰 **Deployment pain points** — issues with SGLang, vLLM, Transformers, ModelScope, NIM, or the API.
- 🧠 **Agent / skill feedback** — anything you observed while building Agent Teams, Skills, or dynamic tool search on top of M2.7.

### How to send feedback

| Channel | Use for |
|---|---|
| [📮 Open an Issue](https://github.com/MiniMax-AI/MiniMax-M3/issues/new/choose) | Bugs, capability requests, M2.7 → M3 comparisons. Pick a template. |
| [💬 WeChat](https://platform.minimaxi.com/docs/faq/contact-us) | Chinese-speaking community discussion. |
| [🧩 Discord](https://discord.com/invite/DPC4AHFCBw) | English-speaking community discussion. |
| [✉️ model@minimax.io](mailto:model@minimax.io) | Private feedback, partnership, or evaluation requests. |

If you are reporting a bug from M2.7, please include:
1. Which inference path you used (MiniMax API / Agent / SGLang / vLLM / Transformers / NIM / ModelScope).
2. Inference parameters (`temperature`, `top_p`, `top_k`, system prompt).
3. A minimal reproduction — prompt, expected output, actual output.

## In the Meantime — Use M2.7

While M3 is in development, M2.7 remains our latest released model:

- **MiniMax Agent**: https://agent.minimax.io/
- **MiniMax API**: https://platform.minimax.io/
- **Token Plan**: https://platform.minimax.io/subscribe/token-plan
- **Weights & deployment guides**: [MiniMax-M2.7](https://github.com/MiniMax-AI/MiniMax-M2.7) (SGLang / vLLM / Transformers / ModelScope / NVIDIA NIM)
- **Model card**: https://huggingface.co/MiniMaxAI/MiniMax-M2.7

Recommended inference parameters for M2.7: `temperature=1.0`, `top_p=0.95`, `top_k=40`.

## Stay Updated

Watch this repository for the M3 announcement, release notes, weights, and deployment guides.

## Contact Us

Contact us at [model@minimax.io](mailto:model@minimax.io).
