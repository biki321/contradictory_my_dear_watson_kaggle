## Contradictory, My Dear Watson

### Detecting contradiction and entailment and neutral in multilingual text.
 If we have two sentences, there are three ways they could be related: one could entail the other, one could contradict the other, or they could be unrelated. Natural Language Inferencing (NLI) is a popular NLP problem that involves determining how pairs of sentences (consisting of a premise and a hypothesis) are related.

  

 Here given a premise and hyothesis derived from that premise , a nlp model has to predict whether the relation between the two is entailment, neutral, or contradiction. An example would be as follow:

  
  
  

>**Premise**:

A woman selling bamboo sticks talking to two men on a loading dock.<br>

> **Hypotheses**:

Entailment **:** There are at least three people on a loading dock.<br>

Neutral **:** A woman is selling bamboo sticks to help provide for her family.

Contradiction **:** A woman is not taking money for any of her sticks  

 _the data set contains premise and hypothesis from multiple languages_

**tools used**:
1. pytorch
2.  [XLA-Roberta model ](https://huggingface.co/transformers/model_doc/xlmroberta.html) this model was fine tunned
3. [dataset ]([https://www.kaggle.com/c/contradictory-my-dear-watson/overview](https://www.kaggle.com/c/contradictory-my-dear-watson/overview))
##### screenshot of the predicted results on test data
![test](https://github.com/biki321/contradictory_my_dear_watson_kaggle/blob/master/watson_result.png)
