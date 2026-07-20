# PPO-GRPO-OR

Research codebase for policy optimization methods in LLM RLHF post-training. Paper under review — details to follow.

---

## Status

🚧 **Pre-release.** Code is functional but documentation is intentionally minimal pending publication. If you're here early, feel free to explore, but expect this README to expand significantly once the paper is public.

---

## Overview

This repo implements and evaluates several policy-optimization approaches for reinforcement learning from human feedback (RLHF), including comparisons across different advantage-estimation strategies and loss formulations. Experiments are run on the Anthropic `hh-rlhf` dataset with a Llama-3.2-1B policy.

Further details — including method descriptions, formulas, and usage instructions — will be published alongside the paper.

---

## Installation

```bash
git clone https://github.com/<your-username>/PPO-GRPO-OR.git
cd PPO-GRPO-OR
pip install -r requirements.txt
```

---

## Repository structure

```
.
├── configs/          # experiment configs
├── losses/           # policy loss implementations
├── advantages/        # advantage estimation
├── reward_model/      # reward model training
├── train_rl.py
├── train_reward_model.py
└── requirements.txt
```

<sub>Adjust to match your actual layout.</sub>

---

## Citation

A citation entry will be added once the paper is publicly available.

---

## License

MIT — see [LICENSE](LICENSE).
