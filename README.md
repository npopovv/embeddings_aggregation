# embeddings_aggregation
ВКР Автоматическое построение ансамбля представлений через метрики сравнения пространств

В папке notebooks лежит код с проведенными экспериментами.
1_get_embeds_age_group.ipynb - получение 102 различных наборов эмбеддингов с помощью PTLS
2_CoLES_metric_analysis.ipynb - эксперименты по коррелияции метрик сходства эмбеддингов с приростом качества от их объединения
3_PTLS_main_exp.ipynb, 4_PTLS_main_exp_2.ipynb  - основные эксперименты с алгоритмами объединения эмбеддингов на транзакционных данных
BERT_layer_aggregation.ipynb, ROBERTA_layer_aggregation.ipynb, SimSCE_layer_aggregation_mean_pooling.ipynb - эксперименты с объединением слоев модели на различных датасетах, ноутбуки аналогичны, только разные модели
