# ID2223 - LAB 2
Athanasia Farmaki, farmaki@kth.se

Michail Roussos, michailr@kth.se

Deliverables description:
Training colab notebook: Llama_3_2_1B+3B_Conversational_+_2x_faster_finetuning
Inference notebook for testing the models: ID2223_inf.ipynb
Gradio app script: https://huggingface.co/spaces/michailroussos/ID2223_9D_withGPU/tree/main

Gradio app: https://huggingface.co/spaces/michailroussos/ID2223_9D_withGPU

Trained models: 
* michailroussos/model_llama_8d (unsloth/Llama-3.2-1B-bnb-4bit)
* Natassaf/lora_model-llama-new (unsloth/Llama-3.2-1B-bnb-4bit)

Model selected for gradio: michailroussos/model_llama_8d

## Ways to improve model performance
### (a) model-centric approach 
The model-centric approach focuses on changing the model itself to improve the performance. Some model-centric approaches are the following:
* Tuning the hyperparameters such as Learning Rate, Batch Size, Epochs etc.
* Changing the model architecture by adjusting the Layer Depth and Width, updating the Attention Mechanism or the Activation Functions.
* Parameter-Efficient Fine-Tuning using LoRA or QLoRA to reduce the number of trainable parameters, making training more efficient

### (b) data-centric approach
The data-centric approach focuses on cleaning or updating the data used to train the model. Some data-centric approaches are the following:
* Making sure that the used data are clean and in the correct format by doing Data Cleaning, Data Augmentation and Data Labeling.
* Using data only from reliable sources by using Public Datasets, Domain-Specific Data or User-Generated Content.
* Performing Data Preprocessing like Tokenization or Text Normalization.


The provided blog (https://huggingface.co/blog/mlabonne/sft-llama3) focuses on Tuning the hyperparameters, Parameter-Efficient Fine-Tuning, Data Preprocessing and used data from a reliable source.



