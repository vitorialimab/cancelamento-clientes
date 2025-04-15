# Cancelamento de Clientes - Análise de Dados com Python

Este projeto realiza uma análise da base de dados de cancelamento de clientes para identificar fatores associados ao cancelamento e propor soluções baseadas nos dados.


## Descrição da Base de Dados

A base de dados contém as seguintes colunas:

- **Idade**: Idade do cliente.
- **Sexo**: Sexo do cliente.
- **Tempo_como_cliente**: Tempo de permanência do cliente na empresa.
- **Frequencia_uso**: Frequência de uso do serviço.
- **Ligacoes_callcenter**: Número de chamadas ao call center.
- **Dias_atraso**: Dias de atraso nos pagamentos.
- **Assinatura**: Tipo de plano do cliente.
- **Duracao_contrato**: Duração do contrato (Mensal, Trimestral, Anual).
- **Total_gasto**: Total gasto pelo cliente.
- **Meses_ultima_interacao**: Meses desde a última interação com a empresa.
- **Cancelou**: Indicador de cancelamento (1 = Cancelou, 0 = Não Cancelou).


## Ferramentas Utilizadas

- Python 3
- Pandas
- Plotly (visualização de dados)
- Jupyter Notebook



## Resultados

- **Contratos mensais** apresentam uma taxa de cancelamento significativamente maior.
- **Clientes com mais ligações ao call center** possuem uma probabilidade mais alta de cancelar.
- **Atrasos frequentes** nos pagamentos estão correlacionados com maior taxa de cancelamento.
- **Baixa frequência de uso** está associada ao cancelamento.

