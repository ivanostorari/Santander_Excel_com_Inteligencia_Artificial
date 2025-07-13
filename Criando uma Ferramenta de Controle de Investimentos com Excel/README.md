# DIO CALCULADORA INVESTIMENTOS
CALCULADORA DE INVESTIMENTOS (PROJETO DIO)

# 📊 Simulador de Investimentos com Aportes Variáveis

Este projeto foi desenvolvido como parte do desafio da DIO com foco em **aplicações práticas de Excel** e **construção de um simulador de investimentos**, especialmente voltado para **fundos imobiliários ou investimentos de renda variável com aportes mensais**.

---

## 🔍 Objetivo

A ferramenta tem como objetivo:

- Controlar e consolidar os investimentos realizados ao longo do tempo
- Simular cenários futuros com base em aportes mensais e taxas de rendimento
- Estimar dividendos recebidos mensalmente
- Apresentar a rentabilidade total (realizada + simulada) de forma clara

---

## 📋 Funcionalidades

### ✔️ Aba `RELATÓRIO`

- Totalmente protegida para evitar alterações acidentais. SENHA:1234
- Apenas a **célula de entrada do período em anos** está desbloqueada para simulação.
- Essa célula possui **validação de dados personalizada**, permitindo somente valores **entre 2 e 50 anos**.
- Toda a simulação futura se baseia nesta entrada.

### ✔️ Aportes Variáveis

- O sistema permite o registro de **aportes mensais com valores diferentes**, refletindo a realidade de muitos investidores.
- As taxas de rendimento também podem variar mês a mês, aumentando a precisão do resultado.

### ✔️ Simulação Real + Projeção

- Cálculo automático do valor investido até o momento
- Cálculo de juros reais recebidos
- Estimativa de dividendos mensais
- Simulação futura com função `VF()` para projetar crescimento com juros compostos

---

## 📈 Cenários de Simulação

Você pode simular cenários de:

- 2 anos
- 5 anos
- 10 anos
- 15 anos
- 20 anos
- 30 anos

A planilha calcula automaticamente:

- **Valor total investido**
- **Dividendos totais estimados**
- **Rentabilidade total esperada (% acumulada)**

---

## 🛠️ Tecnologias Utilizadas

- **Microsoft Excel 2013+**
- Fórmulas financeiras: `VF`, `SOMA`, `SE`, `E`, `MÉDIA`
- Validação de dados personalizada

---

## 🧠 Autoria

Desenvolvido por **Alais Cassimira Salino Barbosa**, como exercício prático e funcional aplicando conhecimentos de Excel, automatização e organização de dados com foco em finanças pessoais.

---

## 📎 Arquivo

A planilha está disponível neste repositório. Basta abrir em qualquer versão do Excel 2013 ou superior para utilizar.
