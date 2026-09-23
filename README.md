# GPT_from_Scratch
Building gpt from scratch with a Shakespeare dataset

1. Introduction
Generative pretrained transformers (GPT) are machine-learning models that are
trained on large amounts of data and reproduce data in similar yet novel patterns in a
process called generation. In recent years, GPTs have greatly expanded the horizons in
the field of language modeling in the form of large language models (LLM). Companies
such as Anthropic, OpenAI and DeepSeek have demonstrated that LLMs are capable of
convincing and complex conversational simulations and reasoning capabilities which
make the models competent digital aides for many modern tasks, ranging from creative
writing, planning, summarizing or simple recreational conversation.
The aim of the block course was to give us participants a general idea on how
these models functioned under the hood in a more practical fashion through coding a
simplified model on a modest dataset (the collected works of Shakespeare) from scratch,
i.e. without the use of complex machine-learning code libraries such as Tensorflow or
PyTorch that are widely used in modern machine-learning applications and research.
During the course, we have been given four distinct tasks which all build up to
form a greater whole, ending up with a GPT model that is capable of generating texts that
plausibly resemble something one would find in Shakespeare's writings. In this report, we
will list out and highlight the essential steps we have taken to produce the final GPT
model.
2. Dataset
The dataset which we used to train our model is a cleaned up version of
Shakespeare's works in a .txt file provided by Project Gutenberg, split neatly into
training, validation and test sets. In total, the text spans more than one million characters
and the train-validation-test split is a ratio of 80:10:10.
