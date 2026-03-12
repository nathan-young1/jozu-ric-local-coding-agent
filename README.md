# Blog Companion Repository

This repository accompanies the blog post **“Running a Local Coding Agent with OpenCode and Jozu Rapid Inference Container (RICs)”** and contains a Jupyter notebook (`main.ipynb`) with comands and examples demonstrated in the article.

The goal of this repo is **reproducibility**: if you follow both the blog and notebook, you will be able to install the required tooling, pull the quantized model from huggingface, package it as a ModelKit using KitOps, upload to Jozu Hub and run the model with Jozu Rapid Inference Container (RIC).

---

## 📁 Repository Structure

```text
.
├── .gitignore
├── README.md
├── main.ipynb        # Commands & Examples shown on the blog
├── opencode.json     # Json configuration declaring the local model