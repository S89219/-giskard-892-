<p align="center">
  <img alt="giskardlogo" src="readme/correct_logo.png">
</p>
<h1 align="center" weight='300' >Open-Source CI/CD platform for ML teams</h1>
<h3 align="center" weight='300' >Giskard creates interfaces for humans to inspect AI models</h3>
<p align="center">
   <a href="https://github.com/Giskard-AI/giskard/releases">
      <img alt="GitHub release" src="https://img.shields.io/github/v/release/Giskard-AI/giskard">
  </a>
 <a href="https://github.com/Giskard-AI/giskard/blob/main/LICENSE">
     <img alt="GitHub" src="https://img.shields.io/badge/License-Apache_2.0-blue.svg">
 </a>
  <a href="https://github.com/Giskard-AI/giskard/actions/workflows/build.yml">
    <img alt="build" src="https://github.com/Giskard-AI/giskard/actions/workflows/build.yml/badge.svg?branch=main"/>
 </a>
  <a href="https://gisk.ar/discord">
    <img alt="Giskard on Discord" src="https://img.shields.io/discord/939190303397666868?label=Discord"/>
  </a>
</p>
<h3 align="center">
   <a href="https://docs.giskard.ai/"><b>Documentation</b></a> &bull;
   <a href="https://docs.giskard.ai/start/"><b>Getting Started</b></a> &bull;
   <a href="https://docs.giskard.ai/start/guides/upload-your-model"><b>Upload Model & Data</b></a> &bull; 
   <a href="https://www.giskard.ai/knowledge-categories/blog"><b>Blog</b></a> &bull;  
  <a href="https://gisk.ar/discord"><b>Discord Community</b></a> &bull;
  <a href="https://www.giskard.ai/about#advisors"><b>Advisors</b></a>
 </h3>
<br />

# About Giskard
- Giskard creates interfaces for humans to inspect AI models. It is  open-source & self-hosted.

- Giskard allows to **instantly see model's prediction** to a given set of feature values. You can change the values directly in Giskard and see the changed prediction. 

- Saw anything strange? Leave a **feedback** directly within Giskard, so that your team can explore the query that generated the faulty result. Designed for both tech and business users, Giskard is super intuitive to use!👌

- Giskard enables you to create **test suites** on AI models. It provides presets of tests so that you design and execute your tests in no time.

- And of course, Giskard works with any model, any environment and integrates seemlessly with your favorite tools. ⤵️ <br/>
<p>
  <img width='600' src="readme/tools.png">
</p>
<br/>

# Why use Giskard
### Inspect the model's performance
- instantly see model's prediction** to a given set of feature values
- change the values directly in Giskard and see the changed prediction
- works with any type of models, datasets and environments. 
<br/>

### Collaborate with business stakeholders
- Exhaustive test suites, backed by State-of-the-Art ML research. 
- Collaborate with business stakeholders with direct feedback & discussion.<br/>
🤖 **Automatically test & monitor** - Protect your ML models against the risk of regressions, drift and bias.<br/>

<p>
  <img width='600' src="readme/perturbation.png" radius = 8px>
</p>

# Interactive demo
Click the image below to start the demo:

<a align='center' href="https://app.arcade.software/share/zPfpXFt8lRm5XDkaWM85" target="_blank">
         <img width='600' align='center' alt="Interactive demo" src="readme/demo.png">
      </a>
<br/>

# Getting Started with Giskard
## 🚀 Installation

**Requirements:** `git`, `docker` and `docker-compose`

```sh
pip istall giskard

git clone https://github.com/Giskard-AI/giskard.git
cd giskard
docker-compose up -d
```

Thats' it. Access at http://localhost:19000 with login/password: admin/admin.

 For more details, refer to the guides below:
1. <a href="guides/installation.md"><b>installation.md</b></a>
2. <a href="guides/configuration.md"><b>configuration.md</b></a>
3. <a href="guides/upload-your-model.md"><b>upload-your-model.md</b></a>

<br/>

## 🏄🏽‍♂️ Workflow
1. **Explore your ML model:** Easily upload any Python model: PyTorch, TensorFlow, Transformers, Scikit-learn, etc. Play with the model to test its performance. 

<p align="center">
  <img width='600' src="readme/Give_feedback.jpeg">
</p>

2. **Discuss and analyze feedback:** Enter feedback directly within Giskard and discuss it with your team. 

<p align="center">
  <img width='600' src="readme/feedback1.png">
</p>

3. **Turn feedback into tests:** Automate tests in any of the categories below.

<p align="center">
  <img width='600' src="readme/test1.png">
</p>

<details>
  <summary><b>Metamorphic testing</b></summary>
Test if your model outputs behave as expected before and after input perturbation
</details>
<details>
  <summary><b>Heuristics testing</b></summary>
Test if your model output respects some business rules
</details>
<details>
  <summary><b>Performance testing</b></summary>
Test if your model performance is sufficiently high within some particular data slices</details>
<details>
  <summary><b>Data drift testing</b></summary>
Test if your features don't drift between the reference and actual dataset</details>
<details>
  <summary><b>Prediction drift testing</b></summary>
Test the absence of concept drift inside your model</details>




# Guides: Jump right in
Follow our handy guides to get started on the basics as quickly as possible:

1. <a href="guides/installation.md"><b>installation.md</b></a>
2. <a href="guides/upload-your-model.md"><b>upload-your-model.md</b></a>
3. <a href="guides/review-your-model.md"><b>review-your-model.md</b></a>
4. <a href="guides/create-tests-from-your-review.md"><b>create-tests-from-your-review.md</b></a>


# How to contribute
We welcome contributions from the Machine Learning community!

Read this [guide](CONTRIBUTING.md) to get started.

# Like what we're doing?
🌟 [Leave us a star](https://github.com/ManeSah/giskard), it helps the project to get discovered by others and keeps us motivated to build awesome open-source tools! 🌟
