# Notes on my AI journey


## 🔧 Environment Setup

This project uses a Conda-based environment to manage dependencies across all AI topics consistently.

### 🧪 Create the Environment

1. Clone this repository:
   ```bash
   git clone https://github.com/sanjaynegi309/ai-journey.git
   cd ai-journey

2. Create the Conda environment from the provided configuration file:
    ```bash
    conda env create -f environment.yml

3. Activate the environment:
    ```bash
    conda activate ai-journey
---
♻️ Environment Lifecycle CommandsBelow are common Conda commands to help manage this environment:

| Operation                 | Command                                           |
|---------------------------|---------------------------------------------------|
| Activate environment      | `conda activate ai-journey`                      |
| Deactivate environment    | `conda deactivate`                               |
| Update environment        | `conda env update -f environment.yml --prune`    |
| List installed packages   | `conda list`                                     |
| Export environment        | `conda env export > environment.yml`             |
| Remove environment        | `conda env remove -n ai-journey`                 |
---

💡 Tip: If you're using VS Code, be sure to select the ai-journey kernel for notebooks or Python execution.

📌 Make sure Conda is installed and up-to-date before running these commands.
