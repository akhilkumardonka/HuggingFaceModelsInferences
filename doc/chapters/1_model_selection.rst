Model selection on HF
================================================================

**HuggingFace Hub** today host a lot of models, datasets and ML demos i.e. HuggingFace Spaces deployed using gradio library.

You can start by clicking on models tab and select task which you are interested in. We can further narrow it down based on end use say language specific
model and sort based on popularity, etc. 

**Model card** gives you an idea about model architecture, reference paper and model sizes available. **File and versions** tab helps you find 
trained weights as **pytorch_model.bin** with its size. Roughly while loading them on local GPU, you will need 1.2 times on model size (in MB or GB) i.e. 
20% extra.

**Tasks** page helps you learning different ML tasks. Based on the tasks, HF suggests you best models, datasets and demos to test. 

To load model in local code, you can select **Use in Transformers** which provides code snippets for using the model. We are offered to load model checkpoints
in two ways.

* Pipeline object : Sort of end to end, takes care of input pre-processings as well.
* Processor & model object : More control over inputs to the model