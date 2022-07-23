<p align="center">
  <img width="500" alt="giskardlogo" src="readme/correct_logo.png">
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

## About Giskard
Giskard creates interfaces for humans to inspect AI models. It is  open-source & self-hosted.

1. Giskard allows to play with the model by changing examples, feature values, or generating local explanations. Saw anything strange? Leave a feedback directly within Giskard, so that your team can explore the query that generated the faulty result. Designed for both tech and business users, Giskard is super intuitive to use!👌
2. Additionally, Giskard enables you to create test suites on AI models. It provides presets of tests so that you design and execute your tests in no time.
3. And of course, it integrates seemlessly with your favorite tools. ⤵️ <br/>
<p align="center">
  <img width='600' src="readme/tools.png">
</p>
<br/>

## Why use Giskard
⚡ **Explore and Validate** -  Collaborate with business stakeholders with direct feedback & discussion.<br/>
🧑‍🔧 **Test** - Exhaustive test suites, backed by State-of-the-Art ML research. <br/>
🤖 **Automate** - Protect your ML models against the risk of regressions, drift and bias.<br/>

<p align="center">
  <img width='600' src="readme/perturbation.png" radius = 8px>
</p>

## Interactive demo
Click the image below to start the demo:

<a align='center' href="https://app.arcade.software/share/zPfpXFt8lRm5XDkaWM85" target="_blank">
         <img width='600' align='center' alt="Interactive demo" src="readme/demo.png">
      </a>
<br/>

## Getting Started with Giskard
### 🚀 Installation

**Requirements:** `git`, `docker` and `docker-compose`

```sh
git clone https://github.com/Giskard-AI/giskard.git
cd giskard
docker-compose up -d
docker-compose up -d        -> Access at http://localhost:19000 with default login / password: admin / admin
```

After the application is started you can access at:

http://localhost:19000 with default login / password: **admin** / **admin**


<h3>Upload your model</h3>

  <a align='center' href="https://app.arcade.software/share/zPfpXFt8lRm5XDkaWM85">
         <img width='500' alt="Interactive demo" src="readme/upload.png">
      </a>
<br/>
  <br/>
  <br/>
  
  Easy upload for any Python model: PyTorch, TensorFlow, Transformers, Scikit-learn, etc. </br>
[👉 Documentation](https://docs.giskard.ai/start/guides/upload-your-model)

<h3>Collect feedback on your model</h3>
  
  <a align='center' href="https://app.arcade.software/share/zPfpXFt8lRm5XDkaWM85">
         <img width='600' alt="Interactive demo" src="readme/feedback.png">
      </a>
<br/>
  <br/>
  <br/>
  
  Improve ML models with business stakeholders in no time. </br>
[👉 Documentation](https://docs.giskard.ai/start/guides/review-your-model)
  
 <h3>Get automated test suites in seconds</h3>
  
  <a href="https://app.arcade.software/share/zPfpXFt8lRm5XDkaWM85">
         <img width='600' alt="Interactive demo" src="readme/test.png">
      </a>
<br/>
   <br/>
   <br/>
  

  Exhaustive test suites, backed by  State-of-the-Art ML research.</br>
  [👉 Documentation](https://docs.giskard.ai/start/guides/create-tests-from-your-review)
  
   <h3>Deploy tests in your CI/CD Pipeline</h3>
  
  <a href="https://app.arcade.software/share/zPfpXFt8lRm5XDkaWM85">
         <img width='600' alt="Deploy tests in CI/CD Pipeline" src="readme/pipeline.png">
      </a>
<br/>
   <br/>
   <br/>
  

  Protect your ML models against the risk of regressions, drift and bias.</br>
  [👉 Documentation](https://docs.giskard.ai/start/)




<br/>

<h2>How to contribute</h2>

We welcome contributions from the Machine Learning community!

Read this [guide](CONTRIBUTING.md) to get started.
