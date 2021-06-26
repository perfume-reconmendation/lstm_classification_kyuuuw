# Fragrantica perfume review clasifier (LSTM)

## Train list

| model name | padding length | num words | embedding | batch size | acc result |
| --- | --- | --- | ---  | --- | --- |
| lstm_with_lemmatizated_01 | 200 | 5000 | 100 | 128 | 0.7450 |
| lstm_with_lemmatizated_02 | 200 | 2500 | 100 | 256 | 0.7384 |
| lstm_with_lemmatizated_03 | 200 | 1000 | 100 | 256 | 0.7029 |
| lstm_with_lemmatizated_04 | 200 | 500 | 100 | 256 | 0.6727 |
| lstm_with_lemmatizated_05 | 200 | 5000 | 200 | 256 | 0.7310 |
| lstm_with_lemmatizated_06 | 200 | 2500 | 200 | 256 | 0.7358 |
| lstm_with_lemmatizated_07 | 200 | 1000 | 200 | 256 | 0.7049 |
| lstm_with_lemmatizated_08 | 200 | 500 | 200 | 256 | 0.6741 |
| lstm_with_lemmatizated_09 | 200 | 5000 | 50 | 256 | 0.7452 |
| lstm_with_lemmatizated_10 | 100 | 2500 | 50 | 256 | 0.7424 |
| lstm_with_lemmatizated_11 | 100 | 1000 | 50 | 256 | 0.7085 |
| lstm_with_lemmatizated_12 | 200 | 1000 | 200 | 512 | 0.7068 |
| lstm_with_stopword_removed_01 | 200 | 5000 | 100 | 128 | 0.7390 |
| lstm_with_stopword_removed_02 | 200 | 2500 | 100 | 256 | 0.7300 |
| lstm_with_stopword_removed_03 | 200 | 1000 | 100 | 256 | 0.6960 |
| lstm_with_stopword_removed_04 | 200 | 500 | 100 | 256 | 0.6693 |
| lstm_with_stopword_removed_05 | 200 | 5000 | 200 | 256 | 0.7364 |
| lstm_with_stopword_removed_06 | 200 | 2500 | 200 | 256 | 0.7365 |
| lstm_with_stopword_removed_07 | 200 | 1000 | 200 | 256 | 0.6975 |
| lstm_with_stopword_removed_08 | 200 | 500 | 200 | 256 | 0.6631 |
| lstm_with_stopword_removed_09 | 200 | 5000 | 50 | 256 | 0.7391 |
| lstm_with_stopword_removed_10 | 100 | 2500 | 50 | 256 | 0.7406 |
| lstm_with_stopword_removed_11 | 100 | 1000 | 50 | 256 | 0.7009 |
| lstm_with_stopword_removed_12 | 200 | 1000 | 200 | 512 | 0.7032 |

* lemmatizate 하면 미세하게 0.01 정도 accuracy 향상 효과가 있음
* num_words 는 대체로 큰것이 좋음. 근데 특이하게 embedding 이 클때는 오히려 