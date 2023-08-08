# Mango_predict_tranfer_learning
Xception
## 目的在於有效的分辨出不同品級的芒果，以減少人力的使用
- 使用Xception作為預訓練模型，並做遷移學習，疊了三層的Dence，中間做一次的dropout，避免overfitting，輸出層以softmax為activate_function，在分類上效果準確度會提升很多。
- 可以看到結果A,B,C級的芒果的預測準度，都在80%以上
