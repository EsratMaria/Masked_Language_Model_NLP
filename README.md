# Masked Language Model (NLP) with Transformer Pipeline

In this repository, I used a **Huggingface** 🤗 transformer model to generate some candidate responses for a given dialogue and then using transformer pipeline I mask a part of the sentence to generate candidate assumptions with scores.

Adding diversity to data.               

**For example:**                     
```
I am going to the <mask> tonight!

[{'sequence': "I'm going to the movies tonight!",
  'score': 0.13211850821971893,
 {'sequence': "I'm going to the gym tonight!",
  'score': 0.12617048621177673,
 {'sequence': "I'm going to the beach tonight!",
  'score': 0.05755433440208435,
 {'sequence': "I'm going to the pub tonight!",
  'score': 0.04060250148177147,
 {'sequence': "I'm going to the dentist tonight!",
  'score': 0.026756728067994118,
}]
  
```
