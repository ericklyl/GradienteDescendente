# Gradient Descent - Aprendizados Principais

## Visão Geral

Este repositório demonstra a implementação do algoritmo Gradient Descent para regressão linear. O objetivo é encontrar os parâmetros (coeficientes) que minimizam a função de custo, ajustando uma linha reta aos dados.

## Conceitos Fundamentais

### 1. O Algoritmo Gradient Descent

O Gradient Descent é um algoritmo de otimização iterativo que:
- Começa com valores iniciais para os parâmetros
- Atualiza esses parâmetros na direção oposta ao gradiente da função de custo
- Converge gradualmente para os valores que minimizam o erro de previsão

### 2. Taxa de Aprendizado (Learning Rate)

- Controla o tamanho dos passos na atualização dos parâmetros
- Taxa muito pequena: convergência lenta
- Taxa muito grande: oscilação ou divergência
- Taxa ideal: convergência rápida e estável

### 3. Função de Custo

- Mede a diferença entre as previsões e os valores reais
- Usamos o Erro Quadrático Médio (MSE)
- Objetivo: minimizar esta função

### 4. Convergência

- O algoritmo converge quando os parâmetros estabilizam
- A função de custo atinge um valor mínimo (ou próximo dele)
- O erro nunca chega a zero devido ao ruído nos dados

## Observações Importantes

1. **Por que o erro não chega a zero?** 
   - Dados reais contêm ruído
   - Modelos lineares têm capacidade limitada
   - Erro zero só é possível em casos específicos (sem ruído ou com overfitting)

2. **Efeitos da taxa de aprendizado:**
   - Valores muito pequenos: algoritmo lento
   - Valores muito grandes: algoritmo instável ou divergente
   - Escolha adequada: crucial para o sucesso do algoritmo

3. **Vetorização para múltiplas características:**
   - Facilmente extensível para regressão multivariada
   - Operações matriciais aumentam a eficiência do código

## Visualizações

O projeto inclui visualizações importantes:
- Superfície 3D da função de custo
- Gráfico de contorno mostrando o caminho da descida do gradiente
- Evolução do erro ao longo das iterações

## Aplicações Práticas

Este algoritmo é a base para:
- Sistemas de recomendação
- Previsão de preços 
- Análise de risco de crédito
- Modelos de aprendizado profundo

