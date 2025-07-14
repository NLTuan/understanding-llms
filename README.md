# understanding-llms

My attempt at using / understanding llms on practical examples.

This project consists of building an LLM from scratch based on the GPT2 architecture and then training it on a jokes dataset. Learning picked up from https://www.youtube.com/playlist?list=PLAqhIrjkxbuWI23v9cThsA9GvCAUhRvKZ

In addition, I tried to finetune GPT2 using 2 techniques: replacing the final layer (although without freezing the rest of the model) and lora finetuning. The former technique failed masterfully and its notebook was labeled "bad". The other one leveraged the pretrained model without bringing in catastrophic forgetting and picked up the jokes pretty quickly.
