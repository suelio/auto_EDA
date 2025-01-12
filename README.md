# Análise Exploratória de Dados com Python

Este script realiza uma análise exploratória de dados (EDA) em um arquivo CSV, oferecendo funcionalidades como:

- Carregamento de dados.
- Tratamento de valores faltantes.
- Detecção e tratamento de outliers.
- Análises estatísticas descritivas.
- Testes estatísticos (correlação de Pearson, qui-quadrado, teste t de Student, ANOVA).
- Visualizações gráficas (histogramas, boxplots, matriz de correlação).

## Funcionalidades

1. **Carregamento de Dados**:
   - Carrega um arquivo CSV e exibe informações básicas (estrutura, tipos de dados, valores faltantes).

2. **Tratamento de Dados Faltantes**:
   - Detecta valores faltantes e permite ao usuário escolher entre preenchê-los com a mediana (colunas numéricas) ou a moda (colunas categóricas).

3. **Detecção e Tratamento de Outliers**:
   - Identifica outliers usando o método IQR (Intervalo Interquartil) e permite ao usuário removê-los.

4. **Análises Estatísticas Descritivas**:
   - Calcula medidas de posição (média, mediana) e dispersão (variância, desvio padrão).
   - Exibe o resumo de cinco números (mínimo, Q1, mediana, Q3, máximo).

5. **Testes Estatísticos**:
   - **Correlação de Pearson**: Avalia a relação linear entre variáveis numéricas.
   - **Teste de Qui-Quadrado**: Verifica a associação entre variáveis categóricas.
   - **Teste t de Student**: Compara as médias de dois grupos.
   - **ANOVA**: Compara as médias de três ou mais grupos.

6. **Visualizações Gráficas**:
   - Histogramas e boxplots para variáveis numéricas.
   - Matriz de correlação para variáveis numéricas.

## Como Usar

1. **Instalação das Dependências**:
   - Execute o seguinte comando para instalar as bibliotecas necessárias:
     ```bash
     pip install pandas numpy seaborn matplotlib scipy scikit-learn
     ```

2. **Executando o Script**:
   - Execute o script em um ambiente Python (Jupyter Notebook, Google Colab, ou terminal).
   - Siga as instruções interativas para carregar o arquivo CSV e escolher as análises desejadas.

3. **Exemplo de Uso**:
   - Digite o caminho do arquivo CSV.
   - Escolha entre tratar dados faltantes e outliers.
   - Selecione as análises estatísticas e visualizações desejadas.

## Autor

- **Suelio Lima**
  - Email: suelio@gmail.com
  - GitHub: [suelio](https://github.com/suelio)

## Licença

Este projeto está licenciado sob a licença **MIT**. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.