# Awesome Open Source — Best of All Time

This repository is a curated "best of all time" index of public GitHub projects — a lightweight, legal aggregator that lists the most influential, widely used, and highly starred open source projects across categories.

This repo stores metadata (name, description, stars, URL, license) and provides a script + GitHub Action to refresh the list of top-starred public repositories periodically.

Quick links

- Repository: https://github.com/mianb7/awesome-open-source

How this works

- The repository stores a curated starter list and a generated list (repos.json / repos.md).
- A script (scripts/fetch_top_repos.py) uses the GitHub Search API to fetch the top-starred public repositories and writes repos.json and repos.md.
- A GitHub Action runs weekly (and on demand) to refresh the list.

Starter curated "Best of All Time" (cross-category examples)

- torvalds/linux — Linux kernel
- microsoft/vscode — Visual Studio Code
- facebook/react — React
- tensorflow/tensorflow — TensorFlow
- pytorch/pytorch — PyTorch
- kubernetes/kubernetes — Kubernetes
- nodejs/node — Node.js
- python/cpython — CPython
- golang/go — Go language
- rust-lang/rust — Rust language
- django/django — Django web framework
- pallets/flask — Flask web framework
- apache/spark — Apache Spark
- hashicorp/terraform — Terraform
- electron/electron — Electron
- ansible/ansible — Ansible
- nginx/nginx — Nginx (note: upstream sources may vary)

Contributing

This project is a living list. To contribute:
- Use the issue tracker to suggest additions or corrections.
- Open a PR to update the curated list or categories.
- See CONTRIBUTING.md for details.

Legal / Scope

- This repository does not mirror or copy upstream source code. It stores metadata and links only, keeping it lightweight and compliant with licenses.
- For full project source, follow the link to the original repository.

License

This index content is MIT-licensed. See LICENSE in this repo.
