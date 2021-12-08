# Persia: An Open, Hybrid System Scaling Deep Learning-based Recommenders up to 100 Trillion Parameters


[download](https://arxiv.org/pdf/2111.05897.pdf)



## Referência 
``` Bibtex 
@article{lian2021persia,
  title={Persia: A Hybrid System Scaling Deep Learning Based Recommenders up to 100 Trillion Parameters},
  author={Lian, Xiangru and Yuan, Binhang and Zhu, Xuefeng and Wang, Yulong and He, Yongjun and Wu, Honghuan and Sun, Lei and Lyu, Haodong and Liu, Chengjun and Dong, Xing and others},
  journal={arXiv preprint arXiv:2111.05897},
  year={2021}
}
```
## Resumo
Modelos baseados em aprendizagem profunda têm dominado o cenário atual de sistemas de recomendação de produção. Além disso, nos últimos anos testemunharam um crescimento exponencial da escala do modelo - de. O modelo 2016 do Google com 1 bilhão de parâmetros até o modelo mais recente do Facebook com 12 trilhões de parâmetros. Aumento significativo da  qualidade vem com cada salto da capacidade do modelo, o que torna acreditamos que a era de 100 trilhões de parâmetros está chegando. No entanto, o treinamento de tais modelos é desafiador, mesmo dentro centros de dados em escala industrial. Esta dificuldade é herdada do surpreendente heterogeneidade da computação de treinamento - o modelo camada de incorporação pode incluir mais de 99,99% do modelo total tamanho, que consome muita memória; enquanto o resto neural rede é cada vez mais intensiva em computação. Para apoiar o treinamento de modelos tão grandes, um sistema de treinamento distribuído eficiente é em necessidade urgente. Neste artigo, resolvemos esse desafio com cuidado co-design do algoritmo de otimização e do arquitetura do sistema. Especificamente, a fim de garantir tanto o treinamento eficiência e precisão do treinamento, projetamos um novo algoritmo de treinamento híbrido, onde a camada de incorporação e a rede neural densa são manipuladas por diferentes mecanismos de sincronização; então nós construímos um sistema chamado Pérsia (abreviação de recomendação paralela sistema de treinamento com aceleração híbrida) para apoiar este híbrido algoritmo de treinamento. Demonstrações teóricas e empíricas estudos de até 100 trilhões de parâmetros foram conduzidos para justificar o projeto e implementação do sistema da Pérsia. Nós fazemos Pérsia disponível ao público (em https://github.com/PersiaML/Persia) para que qualquer pessoa possa treinar facilmente um modelo de recomendação na escala de 100 trilhões de parâmetros.

## comentário
PERSIA  ( p arallel r e elogios t r aining  s istema com hybr i d  a cceleration), um sistema de formação distribuída eficiente baseado em um algoritmo de treinamento híbrido revolucionário, foi revelado por uma equipe de pesquisadores da Kwai Inc., Tecnologia Kuaishou e ETH Zurique. Essa abordagem fornece eficiência e precisão de treinamento para sistemas extensivos de recomendação de aprendizado profundo com até 100 trilhões de parâmetros.

#### PERSIA é baseada em dois aspectos fundamentais:

A distribuição do fluxo de trabalho de treinamento em um cluster diversificado
O procedimento de treinamento de infraestrutura híbrida associada


## pontos fortes

A Pérsia está disponível ao público (https://github.com/PersiaML/Persia) para que qualquer pessoa possa treinar facilmente um modelo de recomendação na escala de 100 trilhões de parâmetros.