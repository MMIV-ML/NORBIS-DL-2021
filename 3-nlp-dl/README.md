## NLP and deep learning

In addition to computer vision, natural language processing is one of the fields most impacted by deep learning. Here's a quick [intro to some relatively recent developments in deep learning for NLP](https://www.linkedin.com/pulse/natural-language-processing-2020-year-review-ivan-bilan) that can give you a flavor of the field. 

In later years, the model class known as _Transformers_ have been shown to be very powerful across all the major tasks in natural language processing. Here's a quick [code-based intro](https://colab.research.google.com/github/huggingface/transformers/blob/master/notebooks/02-transformers.ipynb) and a more [technical intro](https://lilianweng.github.io/lil-log/2020/04/07/the-transformer-family.html) if you're interested. (However, I recommend that you start out by playing with various Transformer models before reading up on the mathematical details.) 

Famous examples of Transformers include [BERT](https://arxiv.org/abs/1810.04805), [GPT-2](https://blog.openai.com/better-language-models/), GPT-3, [RoBERTa](https://arxiv.org/abs/1907.11692), [XLM](https://arxiv.org/abs/1901.07291), [DistilBERT](https://arxiv.org/abs/1910.01108) and many more. 

[HuggingFace](https://huggingface.co/)  :hugs: is an open-source provider of large libraries of pre-trained transformers and datasets, and arguably the best starting point for all kinds of deep learning-based NLP. 

If you want to get started, have a look at their [tutorial notebooks](https://github.com/huggingface/transformers/tree/master/notebooks) and their [documentation](https://huggingface.co/transformers/). 

The notebook ***TBA*** shows an example of how you can download and fine-tune a biomedically oriented pre-trained transformer model, the PubMedBERT model for biomedical natural language processing. It can also be used as a template for how to run HuggingFace models on Gradient.