# **Análise de Dados da Mega-Sena com Regressão Linear**

Este projeto utiliza JavaScript para analisar os números sorteados na Mega-Sena, explorando padrões e tendências por meio de regressão linear. Ele apresenta três modelos distintos de análise: todos os sorteios históricos, os últimos 10 anos e uma faixa específica de ocorrências (278–290). Os gráficos interativos são gerados com **Chart.js**, enquanto os cálculos de regressão linear são realizados com **Regression.js**.

## Autores

- Brendon Gomes da Silva
- Elias Barbosa Souza
- Adriano das Chagas Barros
- Rafael Rodrigues Gonçalves

---

## **Descrição do Projeto**

O objetivo do projeto é visualizar e analisar os dados históricos da Mega-Sena para identificar possíveis padrões nos números sorteados. Apesar da natureza aleatória dos sorteios, as análises ajudam a compreender a distribuição dos números e a reforçar a imprevisibilidade do jogo.

### **Modelos de Análise**

1. **Modelo 1: Todos os Sorteios**
   - Analisa todos os números sorteados desde o início dos registros.
   - Mostra a distribuição geral dos números ao longo do tempo.

2. **Modelo 2: Últimos 10 Anos**
   - Foca nos sorteios realizados entre 2014 e 2024.
   - Destaca possíveis tendências recentes nos números sorteados.

3. **Modelo 3: Faixa Média (278–290)**
   - Filtra números cuja frequência está próxima à mediana histórica.
   - Explora subconjuntos específicos para verificar consistência.

---

## **Funcionalidades**

- **Visualização Interativa**: Gráficos que mostram os dados reais e as linhas ajustadas pela regressão linear.
- **Estatísticas do Modelo**:
  - Equação da regressão linear.
  - Coeficiente de determinação ($$ R^2 $$).
  - Coeficientes angular e linear.
- **Três Análises Separadas**:
  - Dados completos.
  - Últimos 10 anos.
  - Faixa específica (278–290).

---

## **Tecnologias Utilizadas**

- **HTML/CSS**: Estrutura e estilização da página.
- **JavaScript**: Manipulação de dados e cálculos estatísticos.
- **Chart.js**: Biblioteca para gráficos interativos.
- **Regression.js**: Biblioteca para cálculos de regressão linear.
- **Pico CSS**: Framework CSS minimalista para estilização.

---

## **Como Executar o Projeto**

1. Clone ou baixe este repositório.
2. Abra o arquivo `index.html` no navegador para visualizar a página interativa.
3. Os dados estão embutidos no código como CSV, mas podem ser substituídos por arquivos externos ou APIs.

---

## **Conclusão**

Este projeto demonstra que, apesar do uso de ferramentas estatísticas avançadas como regressão linear, a natureza aleatória dos sorteios da Mega-Sena torna qualquer tentativa de previsão ineficaz. Os gráficos e análises ajudam a visualizar a distribuição dos dados e reforçam a imprevisibilidade do jogo.

---

## **Licença**

Este projeto é livre para uso e modificação.

Além disso foi utilizado de IAs para a adaptação para a página em HTML, CSS e JavaScript como PerplexityAI e ChatGPT
