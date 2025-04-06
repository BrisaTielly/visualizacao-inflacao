# Visualização da Inflação Mensal Brasileira 2024

Este projeto apresenta uma visualização gráfica interativa da inflação mensal no Brasil durante o ano de 2024, comparando os índices IPCA (Índice Nacional de Preços ao Consumidor Amplo) e IGP-M (Índice Geral de Preços do Mercado).

## 📊 Demonstração

![Prévia do Gráfico de Inflação](https://i.imgur.com/bktjcNk.png)


### Características

- Visualização em gráfico de barras duplas usando SVG puro
- Comparação direta entre IPCA e IGP-M

## 🔍 Dados Utilizados

Os dados apresentados são da inflação mensal do Brasil em 2024 para os índices IPCA e IGP-M (percentual):

| Mês      | IPCA  | IGP-M  |
|----------|-------|--------|
| Janeiro  | 0.42  | 0.07   |
| Fevereiro| 0.83  | -0.52  |
| Março    | 0.16  | -0.47  |
| Abril    | 0.38  | 0.31   |
| Maio     | 0.46  | 0.89   |
| Junho    | 0.21  | 0.81   |
| Julho    | 0.38  | 0.61   |
| Agosto   | -0.02 | 0.29   |
| Setembro | 0.44  | 0.62   |
| Outubro  | 0.56  | 1.52   |
| Novembro | 0.39  | 1.30   |
| Dezembro | 0.52  | 0.94   |

## 📐 Explicação da Escala e Escolhas de Design

### Escala do Gráfico

A escala vertical do gráfico foi definida para acomodar todos os valores dos dois índices, indo de -0.5% até 2.0%, com marcações a cada 0.5 pontos percentuais. Esta escala foi escolhida porque:

1. **Amplitude**: Abrange confortavelmente o menor valor (-0.52% do IGP-M em fevereiro) e o maior valor (1.52% do IGP-M em outubro).
2. **Legibilidade**: As marcações a cada 0.5 pontos permitem uma leitura precisa sem sobrecarregar o gráfico.
3. **Comparabilidade**: Facilita a comparação visual entre os valores dos dois índices.

### Escolhas de Design

1. **Gráfico de Barras Duplas**: 
   - Foi escolhido para permitir uma comparação direta e imediata entre os dois índices para cada mês.
   - Barras lado a lado facilitam a percepção das diferenças mensais.

2. **Esquema de Cores**:
   - **IPCA (Azul #1e88e5)**: Cor fria, associada à estabilidade, representando o índice oficial do governo.
   - **IGP-M (Laranja #ff5722)**: Cor quente, representando maior volatilidade, característica deste índice que é mais sensível a variações cambiais.

3. **Tratamento de Valores Negativos**:
   - As barras negativas são mostradas abaixo da linha de zero, com seus valores exibidos abaixo delas.
   - Isso preserva a integridade visual dos dados e facilita a percepção das deflações.

4. **Linhas de Grade**:
   - Linhas horizontais leves para facilitar a leitura dos valores sem dominar visualmente o gráfico.

5. **Layout Modularizado**:
   - Separação completa entre estrutura (HTML), apresentação (CSS) e dados para facilitar manutenção e atualizações.


## 🛠️ Tecnologias Utilizadas

- HTML5
- CSS3
- SVG (Scalable Vector Graphics)

## 📁 Estrutura do Projeto

```
├── index.html       # Estrutura do documento e gráfico SVG
├── style.css        # Estilos de apresentação
└── README.md        # Documentação do projeto
```

## 🚀 Como Usar

1. Clone este repositório:
```bash
git clone https://github.com/BrisaTielly/visualizacao-inflacao.git
```

2. Abra o arquivo `index.html` em qualquer navegador moderno.

---

Desenvolvido como parte de um projeto acadêmico de computação gráfica.