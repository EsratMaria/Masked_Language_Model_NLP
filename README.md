# Masked Language Model (NLP) with Transformer Pipeline 

Adding diversity to data

For example:
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
