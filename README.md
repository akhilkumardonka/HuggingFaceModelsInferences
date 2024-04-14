# Open Source Deep Learning Applications on Hugging Face

Inferences on some of the best open source models on Hugging Face, covering multiple domains : audio, text, vision, etc. and across various tasks.
This is my documentation while I was attending the following course by DeepLearning.AI : [Open Source Models with Hugging Face](https://www.deeplearning.ai/short-courses/open-source-models-hugging-face/)

## Sphinx Documentation & Deployment on Github Pages

To build documentation, install sphinx in our python environment and follow below steps:
```
cd <to workspace containing doc folder>
sphinx-build doc _build
```

Check html page in browser, generated at **/_build.index.html**

In case of any additional package installations, navigate to below directory :
```
.github/workflows/documentation.yaml
```
and change pip install or sudo apt install commands according to package requirements

then commit and push repository, github actions will take care of deployments further
