<h1 align="center">
Too Long; Didn't Read ¯\_(ツ)_/¯
</h1>

This interactive notebook uses 🤗 Hugging Face Transformers & BART (Bayesian Additive Regression Trees) to generate summaries from inputted text. To live up to this notebook's theme (tl;dr) I will end the description there.

![Demo](https://i.imgur.com/v7NvPqo.gif)

## Dependencies

You will need these libraries:
- [ipywidgets](https://pypi.org/project/ipywidgets/)
- [Transformers](https://pypi.org/project/transformers/)
- [PyTorch](https://pypi.org/project/torch/)

Since this is a Jupyter Notebook, it will obviously need to be run in some kind of Jupyter environment but the `requirements.txt` does not specify one because there are many different options to choose from. This was developed and tested in JupyterLab but it can also be tried in Jupyter Notebook, Visual Studio Code, Google Colab, etc. However, since widgets are used so heavily, results may vary significantly in each environment. 

If you would like to try it in Google Colab, you can do so using this [link](https://colab.research.google.com/github/styounessi/tldr-jp-notebook/blob/main/tldr-jp-notebook.ipynb#scrollTo=8a5dd47a-a47e-4246-8ee7-96b387e2fc5c). Keep in mind that, based on your Colab runtime environment, you will have to download the main libraries needed to run this notebook. For example, you could add a cell and run this command before doing anything else in the notebook:

`!pip install ipywidgets==8.0.7 transformers==4.31.0 torch==2.0.1`

In Jupyter notebooks and Google Colab, using an exclamation mark (!) before a command in a code cell allows you to run shell commands directly from the notebook.
