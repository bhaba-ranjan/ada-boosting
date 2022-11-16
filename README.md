# Instruction

### Execution instruction
1. Nothing specific required except the dependency below. 
2. Just run all the cells of the jupyter notebook. 

### Dependency:
1. Tensorflow (version): 2.10.0

### Functions
1. boosting: Takes initial and performs boosting
2. resample: Takes the weight distribution and returns sample with replacement according to the weights.
3. createBaseModel: Returns the base classifier with respective thresold.
4. findMissClassificatonIndex: Returns error rate and miss classification index.
5. updateWeight: Takes missclassification index and returns updated wetights.
6. some_pred (Cross Validation): Returns predicted class using given ensemble size.
7. getf1: return precsion, reacll and F1-score.