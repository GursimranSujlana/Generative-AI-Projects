<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
<body>

<h1>Fine-Tune FLAN-T5 with Reinforcement Learning (PPO) and PEFT</h1>

<h2>Overview</h2>
<p>This project demonstrates how to fine-tune a FLAN-T5 model using Reinforcement Learning with Proximal Policy Optimization (PPO) and Parameter-Efficient Fine-Tuning (PEFT) to generate less toxic summaries. The primary objective is to reduce the toxicity of the generated summaries using a hate speech reward model.</p>

<h2>Table of Contents</h2>
<ul>
    <li><a href="#overview">Overview</a></li>
    <li><a href="#installation">Installation</a></li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#project-structure">Project Structure</a></li>
    <li><a href="#results">Results</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
</ul>

<h2 id="installation">Installation</h2>
<p>To get started with this project, you'll need to install the necessary dependencies. You can install them using <code>pip</code>.</p>
<pre>
<code>pip install pandas scikit-learn transformers torch evaluate trl</code>
</pre>

<h2 id="usage">Usage</h2>
<ol>
    <li><strong>Clone the repository</strong>:
        <pre><code>git clone https://github.com/yourusername/ML-DL-AI-Hands-On-Projects.git
cd ML-DL-AI-Hands-On-Projects/Education/Fine-Tune-FLAN-T5</code></pre>
    </li>
    <li><strong>Run the main script</strong>: Ensure you have the required data and model files in place before running the script.
        <pre><code>python fine_tune_flan_t5.py</code></pre>
    </li>
    <li><strong>Notebook</strong>: Alternatively, you can explore the Jupyter notebook for step-by-step instructions and visualizations:
        <ul>
            <li><code>Notebooks/Fine-Tune-FLAN-T5-with-Reinforcement-Learning-PPO-and-PEFT.ipynb</code></li>
        </ul>
    </li>
</ol>

<h2 id="project-structure">Project Structure</h2>
<pre><code>ML-DL-AI-Hands-On-Projects/
├── Education/
│   └── Fine-Tune-FLAN-T5/
│       ├── Notebooks/
│       │   └── Fine-Tune-FLAN-T5-with-Reinforcement-Learning-PPO-and-PEFT.ipynb
│       ├── Results/
│       │   ├── active_days_by_income.png
│       │   ├── age_and_crown_count.png
│       │   ├── clusters.png
│       │   ├── elbow.png
│       │   ├── multi_variant.png
│       │   ├── result.png
│       │   └── visualization1.png
│       ├── fine_tune_flan_t5.py
│       └── README.md
└── .DS_Store
</code></pre>

<h2 id="results">Results</h2>
<p>The project includes visualizations and results of the fine-tuning process. Here are some key results:</p>
<ul>
    <li><strong>Active Days by Income</strong>: <code>Results/active_days_by_income.png</code></li>
    <li><strong>Age and Crown Count</strong>: <code>Results/age_and_crown_count.png</code></li>
    <li><strong>Clusters</strong>: <code>Results/clusters.png</code></li>
    <li><strong>Elbow Method</strong>: <code>Results/elbow.png</code></li>
    <li><strong>Multi-Variant Analysis</strong>: <code>Results/multi_variant.png</code></li>
    <li><strong>Overall Results</strong>: <code>Results/result.png</code></li>
    <li><strong>Visualization 1</strong>: <code>Results/visualization1.png</code></li>
</ul>

<h2 id="contributing">Contributing</h2>
<p>We welcome contributions to this project. If you have any ideas, suggestions, or bug fixes, please open an issue or create a pull request.</p>

<h2 id="license">License</h2>
<p>This project is licensed under the MIT License. See the <code>LICENSE</code> file for details.</p>

</body>
</html>
