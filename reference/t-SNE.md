# t-Stochastic Neighbor Embedding ([t-SNE](https://lovit.github.io/nlp/representation/2018/09/28/tsne))와 perplexity  

### t-Stochastic Nearest Neighbor (t-SNE) 는 vector visualization 을 위하여 자주 이용되는 알고리즘입니다. t-SNE 는 고차원의 벡터로 표현되는 데이터 간의 neighbor structure 를 보존하는 2 차원의 embedding vector 를 학습함으로써, 고차원의 데이터를 2 차원의 지도로 표현합니다. t-SNE 는 벡터 시각화를 위한 다른 알고리즘들보다 안정적인 임베딩 학습 결과를 보여줍니다. 이는 t-SNE 가 데이터 간 거리를 stochastic probability 로 변환하여 임베딩에 이용하기 때문입니다. 그리고 이 stochastic probability 는 perplexiy 에 의하여 조절됩니다. 이번 포스트에서는 t-SNE 가 어떻게 안정적인 임베딩 학습 결과를 보일 수 있는지에 대한 원리를 살펴보고, perplexity 의 역할에 대해서도 알아봅니다.

## https://lovit.github.io/nlp/representation/2018/09/28/tsne/
