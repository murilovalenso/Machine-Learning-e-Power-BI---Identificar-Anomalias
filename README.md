# Machine-Learning-e-Power-BI---Identificar-Anomalias
## Detecção de Anomalias em Transações Financeiras

Neste projeto, exploramos a aplicação de Machine Learning utilizando a linguagem R e criamos visualizações interativas no Power BI. Tudo isso, dentro de um ambiente do RStudio. Nosso objetivo, é abordar um problema de negócio que envolve a detecção de anomalias em transações financeiras de uma empresa, tendo como base os dados históricos dos clientes. Os dados, mostram que a empresa da área financeira tenha dados históricos de clientes com duas transações financeiras (aqui chamadas de “transacao1” e “transacao2”). Os gestores acreditam que algumas dessas transações possam ser fraudulentas e gostariam de identificar as eventuais anomalias. 

Os gestores não fazem ideia do que seria uma anomalia e precisam encontrar uma solução. De fato, eles não sabem se anomalias realmente ocorreram. Através dos dados coletados usaremos Machine Learning para agrupar os dados de transações financeiras dos clientes e, então, detectar e definir as anomalias (se existirem). Portanto, além dos resultados, o projeto têm como objetivo entregar no formato visual através de gráficos no Power BI.


### Problema de Negócio
Considerando os dados históricos de transações financeiras realizadas pelos clientes, enfrentamos o desafio de identificar anomalias através das transações efetuadas por esses clientes. Esse processo de detecção nos ajudará a entender melhor o comportamento dessas transações e direcionar melhores estratégias contra fraudes financeiras.

### Ferramentas Utilizadas
**R**: Utilizaremos a linguagem R para o processamento dos dados, aplicação de técnicas de Machine Learning e criação dos modelos de segmentação.
    
**RStudio**: O RStudio será o ambiente onde escreveremos e executaremos nosso código em linguagem R, facilitando a análise e visualização dos resultados.
    
**Power BI**: Integraremos visualizações interativas criadas no Power BI ao RStudio para oferecer uma representação visual mais rica dos resultados.


### Passos do Projeto
**Coleta e Análise de Dados**: Carregaremos os dados históricos das transações financeiras e realizaremos uma análise inicial para entender sua estrutura e conteúdo.

**Pré-processamento de Dados**: Prepararemos os dados para o processo de segmentação, o que pode envolver tratamento de valores ausentes, normalização de dados, etc.

**Aplicação de Algoritmos de Machine Learning**: Utilizaremos o pacote solitude para detecção de anomalias através do método Isolation Forest e o pacote ggplot2 para gerar gráficos dessas anomalias.

**Integração com Power BI**: Criaremos visualizações no Power BI que representam graficamente os resultados das anomalias.

**Análise e Insights**: Interpretaremos os resultados, identificando padrões e insights que possam guiar decisões estratégicas.

**Executando o Projeto**
  - Clone este repositório para o seu ambiente local.
    
  - Instale as bibliotecas Python necessárias (tidyverse, dplyr, solitude, ggplot2 e readr.).
    
  - Configure o ambiente do RStudio.
    
  - Execute o RStudio e siga os passos definidos no arquivo .ipynb.
    
  - Utilize o Power BI para criar as visualizações necessárias e exporte-as.

**Observações:**
Certifique-se de possuir todas as credenciais e permissões necessárias para acessar os dados dos clientes.
O Power BI e o RStudio são ferramentas poderosas para análise e visualização de dados, mas também exigem um aprendizado prévio para utilizá-las eficientemente.

## Editando o Relatório das Anomalias no Power BI
![Tabelas](https://github.com/murilovalenso/Machine-Learning-e-Power-BI---Identificar-Anomalias/blob/main/Dashboard%20-%20Detec%C3%A7%C3%A3o%20de%20Anomalias.png)
