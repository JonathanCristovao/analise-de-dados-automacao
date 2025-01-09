
# Projeto: Análise de Dados de Sensores Industriais

![Análise de Dados Industriais](assets/cover.png)

## Descrição
Este projeto utiliza dados de sensores industriais para realizar análises exploratórias e identificar anomalias de temperatura em motores elétricos. A análise inclui etapas de visualização, tratamento de dados e geração de insights para melhorar a eficiência e segurança no ambiente industrial.

## Funcionalidades
- Identificação de anomalias com base em limites pré-definidos (50°C a 120°C).
- Visualização de dados em gráficos de linha e dispersão.
- Análise separada para cada motor com base em um identificador único (ID).
- Demonstração prática de técnicas de análise e visualização de dados.

## Ferramentas Utilizadas
- **Python**: Linguagem de programação principal.
- **Bibliotecas**:
  - `pandas`: Manipulação e análise de dados.
  - `matplotlib`: Criação de gráficos.

## Estrutura do Projeto
1. **Coleta de Dados**: Simulação ou importação de um conjunto de dados de sensores industriais.
2. **Tratamento de Dados**:
   - Remoção de ruídos.
   - Identificação e tratamento de valores ausentes.
   - Normalização de dados.
3. **Análise Exploratória**:
   - Cálculo de estatísticas básicas (média, mediana, etc.).
   - Visualização de tendências e identificação de padrões.
4. **Identificação de Anomalias**:
   - Valores fora dos limites aceitáveis (abaixo de 50°C ou acima de 120°C).
   - Destaque das anomalias em gráficos.

## Como Executar
1. Clone o repositório ou faça o download do notebook.
2. Instale os pacotes necessários utilizando:
   ```bash
   pip install pandas matplotlib numpy
   ```
3. Execute o notebook em um ambiente como Jupyter Notebook (exemplo: Google Colab)
4. Carregue os dados no formato CSV e siga as instruções do notebook.

## Exemplo de Uso
O notebook inclui um exemplo completo de análise de temperatura de motores elétricos em uma linha de produção. Cada motor é analisado separadamente, e as anomalias são destacadas para facilitar a interpretação.

## Contribuição
Contribuições são bem-vindas! Para contribuir, faça um fork do repositório, crie um branch com suas alterações e envie um pull request.

## Licença
Este projeto está licenciado sob a licença MIT. Veja o arquivo LICENSE para mais detalhes.
