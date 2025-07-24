# L-SCOPE 🧭

**LLM-assisted design Space Convergence for Optimized Parameter Exploration**

L-SCOPE is an interactive Grasshopper plugin designed to improve the efficiency and interpretability of simulation-based building design optimization.  

It guides users through a four-step workflow powered by LLMs and information gain-based analysis to automatically refine design parameter domains.

## 🔧 Key Components

### Step 1: Setup Environment  
Prepare a virtual environment and install required dependencies.

### Step 2: Launch LLM Server  
Start the local server to process prompts and generate analysis code.

### Step 3: IG-Guided Control Panel  
Interactively send prompts, visualize results, and run Python code.

### Step 4: Automatic Convergence  
Classify parameters via information gain and refine design domains accordingly.

## 📦 Installation

- Download the `.yak` plugin file from [Releases](https://github.com/Joannazhou-qianyun/L-SCOPE/releases)
- Install via `yak install` or drag into Rhino/Grasshopper
- Open `example_AIGGC.gh` to see the full workflow in action

## 📝 Related Publication

If you use L-SCOPE in your research, please cite:

Zhou, Q., & Xue, F. (2025). *Automatic information gain-guided convergence for refining building design parameters: Enhancing effectiveness and interpretability in simulation-based optimization*. **Building and Environment**, 275, 112788. https://doi.org/10.1016/j.buildenv.2025.112788

<details>
<summary><strong>BibTeX Citation</strong></summary>

```bibtex
@article{zhou2025igconvergence,
  title={Automatic information gain-guided convergence for refining building design parameters: Enhancing effectiveness and interpretability in simulation-based optimization},
  author={Zhou, Qianyun and Xue, Fan},
  journal={Building and Environment},
  volume={275},
  pages={112788},
  year={2025},
  doi={10.1016/j.buildenv.2025.112788}
}
```

</details>

## 📫 Contact / Issues

Please open an [issue](https://github.com/Joannazhou-qianyun/L-SCOPE/issues) if you have questions or feedback.