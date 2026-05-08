# TextSummarizerwithPegasus
In this project, we use Pegasus transformer as the model base to generate text and summarize resume data.

### Objectives:
LLM / Transformer-based summarization
Using Pegasus (Hugging Face Transformers)
Applying it to resume summarization

### Libraries:
torch
transformers
accelerate>=0.20.1
numpy

### Conclusion:
In conclusion, the best model was summary where it had a more accurate and coherent/cohesive summary of Jessica's work experience and responsibilities. This was done by adding parameters and adjusting their variables to get a better reading. To further elaborate, raising the length limits and search quality (num_beams=6) as well as adding no_repeat_ngram_size=3 to specifically prevent the model from repeating the same three-word phrases, the model's output became more coherent and precise. It is apparent that changing the minimum and maximum length as well as adding the no_repeat impacted the summary in a positive way.