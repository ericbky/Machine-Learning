## Fundamentos de Machine Learning

O Machine Learning é a área mais importante do universo de IA e necessita de uma dedicação abrangente pois há uma complexidade alta para o domínio desta área.

- Machine Learning é o aprendizado de máquina, ou seja, o aprendizado requer uma capacidade de aprender sobre determinados assuntos de forma contínua e sempre tem alguma relação com o ambiente para esse aprendizado, seja por meio de brincadeiras, informações, etc.
Como uma máquina interage com o ambiente? Através de fontes de dados ou através de reforço (tentativa e erro).
O aprendizado deve ter evolução e deve ser mensurado através de métricas, para o uso do modelo.

## Como a máquina aprende?

Para o treinamento há uma fonte de dados e básicamente através da relação desses dados ocorrerá um processamento/algoritmo que através dele é possível obter resultados de deciões e essas decisões formam um modelo, como você pode ver abaixo.

CVocê quer prever em quais dias poderá jogar vôlei. Os dados de entrada podem conter informações como **clima**, **temperatura**, **umidade** e **vento**. O algoritmo processa esses dados e gera um modelo (como uma árvore de decisão). Esse modelo é capaz de fazer previsões para novos dias com base nos dados que ele já viu durante o treinamento.

![Dados de Aprendizado](./assets/Fluxo-modelo.png)

O resultado do aprendizado é uma árvore de decisão, que seria o modelo.

Assim, vamos supor que surja um novo dia:

|Ensolarado|quente|alta|FALSO|
|----------|------|----|-----|

Como vou saber se poderei jogar? O modelo, ao receber esses novos dados, percorre a árvore de decisão para verificar as condições e, com base nas regras que ele aprendeu, irá decidir se você poderá jogar ou não.

## Conceitos de Machine Learning

Geralmente as estruturas dos dados em que os modelos irão trabalhar serão dados tabulados como no exemplo abaixo, mas eventualmente pode se referir a matrizes por exemplo e a resolução vem a partir de cálculos matemáticos.

![Estrutura dos dados para empréstimo](./assets/Dados-Empréstimo-Estrutura.png)

### Conceitos importantes:

- **Atributos**: Características utilizadas para rotular os dados e a partir dessas características utilizamos as aplicações dos modelos em favor delas.
- **Instâncias**: Representação de algum fator, ou seja, nesse caso, uma tupla.
- **Classe**: Nos modelos que utilizam a técnica de classificação o objetivo é prever ou descrever um atributo especial (**classe**), ou seja ele é o objetivo do modelo de ML, ele se chama assim por convenção.
- **Tipos de dados**: Há muitas mudanças em relação aos tipos de dados que são **Dados Categóricos** e **Dados Numéricos**, e também há diferenciação entre atributos comuns ou em classes.

### Conceitos fundamentais:

Tarefas mais importantes: 

- **Classificação**: A classificação seria a descrição ou previsão relacionado a um atributo especial chamado **classe**, ou seja, prever os motivos de uma fraude, uma doença a raça de um animal. - Dados categóricos.

- **Regressão**: Utilizado para prever ou descrever um atributo **classe** porém numérico.

- **Agrupamento**: O objetivo é agrupar os dados a partir de características comuns ou com semelhanças matemáticas que são definidas a partir do algoritmo utilizado. Nova espécie, decisão pelo grupo...
(Um segmento seria basicamente um conjunto de atributos com a mesma fundamentação matemática).

- **Regra de Associação**: Seria basicamente a partir de um dado prever qual outro dado seria o mais provável de estar agrupado junto ao primeira a partir de determinada ação, seja compra, estragar, etc...

- **Diferenças de técnicas**: 
    - Supervisionada: Possui uma referência que obviamente irá avaliar a performance do modelo em questão. Seria o supervisionado.

    - Não supervisionado: Por exemplo, não tem valores de embasamento para o treinamento de modelos.

