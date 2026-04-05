<div align="center">

```
████████╗ ██████╗ ██████╗  ██████╗██╗  ██╗
╚══██╔══╝██╔═══██╗██╔══██╗██╔════╝██║  ██║
   ██║   ██║   ██║██████╔╝██║     ███████║
   ██║   ██║   ██║██╔══██╗██║     ██╔══██║
   ██║   ╚██████╔╝██║  ██║╚██████╗██║  ██║
   ╚═╝    ╚═════╝ ╚═╝  ╚═╝ ╚═════╝╚═╝  ╚═╝
```

**Hands-on Deep Learning — train it, break it, understand it.**

[![Python](https://img.shields.io/badge/Python-3.9%2B-3572A5?style=flat-square&logo=python&logoColor=white)](https://python.org)
[![PyTorch](https://img.shields.io/badge/PyTorch-2.x-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)](https://pytorch.org)
[![License](https://img.shields.io/badge/License-MIT-22c55e?style=flat-square)](LICENSE)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-f97316?style=flat-square)](CONTRIBUTING.md)

</div>

---

## What is Torch?

**Torch** is a curated collection of from-scratch deep learning programs built for people who want to *actually understand* what's happening inside the black box — not just import a library and call `.fit()`.

Every program here is intentionally minimal, heavily commented, and designed to isolate one idea at a time. You read it, you run it, you tweak it. That's the loop.

> *"You don't understand it until you can train it from scratch."*

---


## Getting Started

### 1. Clone the repo

```bash
git clone https://github.com/Pmskabir1234/Torch.git
cd torch
```


You should see the loss drop and a plot of the optimization trajectory. That's it — you're training.

---

## Prerequisites

| Topic | Why you need it |
|---|---|
| Python basics | All code is Python 3.9+ |
| Linear algebra | Vectors, matrices, dot products |
| Calculus (partial derivatives) | Backprop is chain rule |
| Probability basics | Loss functions, softmax |

No prior deep learning experience needed — that's what this repo is for.

---

## Program Design Philosophy

Every program in Torch follows these rules:

- **One concept per file** — no mixing ideas
- **Comments explain the *why*, not the what** — the code shows what; the comments teach
- **Runnable in under 2 minutes** — no waiting on giant datasets
- **Breaks are encouraged** — modify hyperparameters and watch things fail

---

## Contributing

Found a bug? Want to add a program on VAEs, diffusion models, or RL? Open a PR.

```bash
# Fork → clone → create branch
git checkout -b feature/variational-autoencoder

# Write clean, commented code
# Add your file to the right folder
# Update this README if needed

git push origin feature/variational-autoencoder
# Open a Pull Request
```

**Guidelines:**
- Keep programs focused and self-contained
- Include a short docstring at the top explaining the concept
- Test that it runs end-to-end before submitting

See [CONTRIBUTING.md](CONTRIBUTING.md) for details.


---

## License

MIT — use it, learn from it, share it.

---

<div align="center">

Built for learners who aren't satisfied with the surface.

**Light the Torch. Train the model. Understand the machine.**

</div>
