# Item2Vec
Research and create a hybrid recommender model 

Dataset Amazon

Image:

| Model |Precision_at_4  | Recall_at_4 |
| -------- | ------- | ------- |
| Inception_v3 | 0.02195157884398173 | 0.006379425892699254 |
| EfficientNet | 0.023167018612188773 | 0.0071763082464064805 |
| Resnet101 | 0.006402543829494672| 0.0019453259840823977 |
| CLIP(base) | 0.030528284244974287 | 0.009405105846455908 |
| CLIP(large) | 0.03612669471715755 | 0.010359959239683312 |
| BLIP(base) | 0.030913978494623656 | 0.00931076545375152 |

Text:

| Model |Precision_at_4  | Recall_at_4 |
| -------- | ------- | ------- |
| Word2Vec(Google) | 0.06959624497698134 | 0.025079756137138816 |
| Roberta(base) | 0.06315050805591423 | 0.02154282835420157 |
| Bpe(Clip)| 0.01502273620389603 | 0.005698868287788102 |
| Roberta(large)| 0.09281142985460057 |  0.0316262832135125 |

Combination:

| Model |Precision_at_4  | Recall_at_4 |
| -------- | ------- | ------- |
| Concat | | |
| Mean | | |
| Sum | | |
