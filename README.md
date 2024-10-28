# 🚚 Análise de Dados Logísticos 📦

## 📒 Descrição
O projeto é uma análise descritiva de dados coletados de uma empresa de logística especializada em entregas rápidas. O objetivo é identificar padrões, tendências e fatores que afetam o desempenho da frota, visando otimizar a eficiência operacional, reduzir custos e melhorar a satisfação dos clientes.

## 🧐 Processo de Criação
O projeto foi desenvolvido utilizando uma base de dados histórica disponível em um arquivo CSV. A análise foca em entender a utilização dos veículos, tempos de entrega e feedback dos clientes.

### Etapas:
1. **Coleta de Dados**: Importação da base de dados em formato CSV utilizando a biblioteca Pandas.
2. **Análise Descritiva**: Cálculo de estatísticas descritivas.
3. **Análise exploratória - Identificação de Padrões**: Análise de tendências de entrega e eficiência dos motoristas.
4. **Visualização de Dados**: Criação de gráficos utilizando Matplotlib, Seaborn e Plotly para comunicar os insights obtidos.
5. **Propostas de Melhoria**: Elaboração de estratégias com base nas análises realizadas para otimizar as operações logísticas.

## 🚀 Resultados
Os resultados do projeto incluem a identificação dos principais fatores que afetam o desempenho da frota, horários de pico, rotas frequentes e feedback dos clientes. As visualizações gráficas ajudaram a comunicar os padrões e tendências encontrados nos dados.

### Identificação de Melhores Desempenhos
Através do feedback dos clientes, foi possível identificar motoristas com os melhores desempenhos. É interessante notar que motoristas com feedbacks mais altos podem até manter o mesmo desempenho de tempo e uso de combustível que outros, indicando que a satisfação do cliente pode depender de fatores além das métricas tradicionais.

### Análise por Carga
A implementação da função melhor_desempenho_por_carga foi útil para destacar quais motoristas têm melhor desempenho em diferentes tipos de carga. Essa abordagem é valiosa para a otimização logística, permitindo alocar motoristas com base em suas especialidades.

### Tendências de Carga e Tempo Médio de Viagem
A análise das tendências mensais de carga e tempo de viagem revelou que algumas cargas mantiveram estabilidade, enquanto outras apresentaram a necessidade de melhorias. Essa informação é essencial para realizar ajustes operacionais e melhorar a eficiência.

## 💭 Reflexão
Este projeto demonstrou a importância da análise descritiva na identificação de oportunidades de melhoria nas operações logísticas. Através da exploração dos dados, foi possível propor medidas para aumentar a eficiência e a satisfação do cliente.

### Análises Futuras

Modelagem Preditiva: Com dados suficientes, considerar a implementação de modelos preditivos para prever consumo de combustível e tempo de entrega, com base em fatores como carga, motorista e horário.

## 📊 Visualização de Dados


## Outros pontos
Além da análise das viagens, também foi realizada uma análise subsidiária do desempenho dos motoristas e oportunidades de melhorias na atribuição de atividades de cargas. O projeto utilizou as bibliotecas Plotly, Pandas, Matplotlib e Seaborn, com uma única base de dados (bd.csv). O arquivo `project.ipynb` contém todo o código necessário para as análises, além de um arquivo oculto com regras de negócio relevantes.
