# Goal

The goal of this repository is to illustrate how easy it can be to use Azure Cognitive Services to perform tasks like speech recognition, form recognition, text recognition from images, and more. 

With the exception of this README, the files included in this repository are Jupyter notebooks, which you can download and run locally. Each notebook is stand alone, and can be used for learning purposes or to experiment with a specific service. 

## Things to keep in mind

* You'll need an Azure subscription to run any of the notebooks in this repo. In most cases, the *free* subscription will do the trick. If a paid (or standard) subscription is required, it'll be called out in the prerequiusites of the notebook.
* For each service, you'll need to create a resource in the Azure portal. I'll include links direcly to the create blade in each notebook.
  * In most cases you'll need some combination of `key`, `region`, and/or `endpoint`. These are all available in the Azure portal, under your resource, in the *Keys and endpoints* menu.

## Issue? Don't like something?

Find a bug? Come across something that doesn't work? Hate the code and want to make it better? Open an issue -- or even better, submit a pull request.

## List of notebooks 

Each of these Jupyter notebooks is designed to have you up and running in 10 minutes or less. We get it, sometimes signing up for an account takes time, but all of the code is ready to run with minimal adjustments (adding your keys, endpoints, and regions). 

* [Azure Form Recognizer - Pre-built models](https://github.com/erikhopf/CognitiveServicesPyNotebooks/blob/main/Form_Recognizer.ipynb) - Use Form Recognizer to analyze and extract data from business cards, IDs, forms and more using pre-built models from Azure. 
* [Azure Form Recognizer - Custom models](https://github.com/erikhopf/CognitiveServicesPyNotebooks/blob/main/Form_Recognizer_Customization.ipynb) - Build a custom model with existing documents and analyze forms in under 10 minutes. 
* [Azure Speech - Batch transcription of audio files](https://github.com/erikhopf/CognitiveServicesPyNotebooks/blob/main/Batch_Transcription.ipynb) - Use Azure Speech service to transcribe audio files stored in Azure Blob storage containers asyncrhonously.
