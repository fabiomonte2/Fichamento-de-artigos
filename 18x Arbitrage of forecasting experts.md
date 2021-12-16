# Arbitrage of forecasting experts

[download](https://link.springer.com/content/pdf/10.1007/s10994-018-05774-y.pdf) 



## Referência 
``` Bibtex 
@article{cerqueira2019arbitrage,
  title={Arbitrage of forecasting experts},
  author={Cerqueira, Vitor and Torgo, Lu{\'\i}s and Pinto, F{\'a}bio and Soares, Carlos},
  journal={Machine Learning},
  volume={108},
  number={6},
  pages={913--944},
  year={2019},
  publisher={Springer}
}
```
## Resumo
A previsão é uma tarefa importante em vários domínios. Seu interesse generalizado está relacionado à incerteza e à estrutura complexa em evolução das séries temporais. Os métodos de previsão são normalmente projetados para lidar com dependências temporais entre as observações, mas é amplamente aceito que nenhum é universalmente aplicável. Portanto, uma solução comum para essas tarefas é combinar a opinião de um conjunto diversificado de previsões. Neste artigo, apresentamos uma abordagem baseada em arbitragem, na qual vários modelos de previsão são combinados dinamicamente para obter previsões. Arbitrar é uma abordagem de metalaprendizado que combina a produção de especialistas de acordo com as previsões das perdas em que incorrerão. Apresentamos uma abordagem para recuperar previsões out-of-bag que melhora significativamente a eficiência dos dados. Finalmente, uma vez que a diversidade é um componente fundamental em métodos de ensemble, propomos um método para lidar explicitamente com a interdependência entre especialistas ao agregar suas previsões. Os resultados de extensos experimentos empíricos fornecem evidências da competitividade do método em relação às abordagens do estado da arte. O método proposto está disponível publicamente em um pacote de software.

## Comentário/citação
A estratégia de metalearning proposta, aqui denominada Arbitrated Dynamic Ensemble (ADE), é baseada na arbitragem


## Pontos fracos
- Modelos baseados em pessoas e não em produtos

## Pontos fortes
* ADE , um método para arbitragem de especialistas em previsão;

* A introdução de um procedimento pré-sequencial bloqueado na abordagem de arbitragem para obter previsões out-of-bag no conjunto de treinamento, a fim de aumentar os dados usados ​​para treinar os modelos de metalearning;

* Uma estratégia de reponderação sequencial para controlar a redundância entre a saída dos especialistas usando sua correlação em uma janela recente de observações;

* Um extenso estudo empírico abrangendo: comparações estatísticas com abordagens do estado da arte; análise sobre as diferentes estratégias de implantação do método proposto; análise de sensibilidade sobre os principais parâmetros do método proposto; análise de escalabilidade relativa em termos de tempo de execução; e um estudo sobre a importância de aumentar o número de especialistas no conjunto.