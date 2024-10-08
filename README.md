# Exploration of Traffic Accident Based Pilot Zones for Autonomous Vehicle Safety Validation

The repository contains the data used in "Exploration-of-Traffic-Accident-Based-Pilot-Zones-for-Autonomous-Vehicle-Safety-Validation".

## Abstract
 Recently, the commercialization of autonomous vehicles has increased the importance of verifying vehicle safety through autonomous trials. Autonomous driving trials are conducted in limited areas within artificially constructed test roads and pilot districts and directly explore road sections and areas with similar environments to ensure the safety of AVs driving on real roads. Many previous studies have evaluated the complex response potential of AV by deriving edge scenarios to ensure their safety. However, difficulties arise in exploring real roads with traffic accident factors and configurations similar to those in edge scenarios, making validation on real roads uncertain. This paper proposes a novel method for exploring pilot zones using traffic accident data to verify the safety of AVs. The method employs a CNN+BiGRU model trained on DMV dataset data to classify traffic accidents as AV or human-caused. The model’s classification accuracy was evaluated using recall, precision, F1-score, and accuracy, achieving 100.0%, 97.8%, 98.9, and 99.5%, respectively. The trained model was applied to the KNPA dataset, identifying 562 out of 798 cases as AV-like, indicating potential areas of high accident density due to AV operation. Outlier detection and DBSCAN clustering were utilized to identify compact pilot zones, effectively reducing the area size compared to raw data clusters. This approach significantly lowers the cost and time associated with selecting test roads and provides a viable alternative for countries lacking real AV accident data. The proposed method’s effectiveness in identifying pilot zones demonstrates its potential for advancing AV safety validation.

## Model
### GloVe
The pre-trained models provided in the implementation of the GloVe model for learning word representations from the paper "GloVe: Global Vectors for Word Representation" can be utilized. ([project page](https://nlp.stanford.edu/projects/glove/))

## Authors
Siyoon Kim, MinJe Cho and Yonggeol Lee*
