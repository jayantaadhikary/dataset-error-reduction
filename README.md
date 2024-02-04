# Dataset Error Reduction

To reduce error in NLP Datasets using LLMs.

The datasets used currently are [SQuAD](https://rajpurkar.github.io/SQuAD-explorer) and [RACE](https://www.cs.cmu.edu/~glai1/data/race) which are Extractive Question Answering Datasets.


### Use in your system

Fork and Clone this Repository.
1. If you are using a OpenAI API key, create a `.env` file in the same directory and add your OpenAI API key.   

`OPENAI_API_KEY = YOUR_API_KEY`

2. If you are using a LLM model locally using a local server, then use the files inside of the LocalLLM folder instead of the default files. The folder /ollama consists of my notebooks which were using Ollama to run LLMs locally. 

PS - I use [LM Studio](https://lmstudio.ai/) and [Ollama](https://ollama.ai)to run the LLMs locally. 

#### References:
1. [SQuAD: 100,000+ Questions for Machine Comprehension of Text](https://aclanthology.org/D16-1264) (Rajpurkar et al., EMNLP 2016)
2. [RACE: Large-scale ReAding Comprehension Dataset From Examinations](https://aclanthology.org/D17-1082) (Lai et al., EMNLP 2017)

