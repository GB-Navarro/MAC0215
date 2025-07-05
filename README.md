# 📈 Previsão de Volatilidade Realizada em Criptomoedas com Modelos Fuzzy Baseados em Level Sets

## 📚 Descrição do Projeto
Este projeto tem como objetivo desenvolver um modelo fuzzy adaptativo para previsão da volatilidade realizada de criptomoedas a partir de dados intradiários. A proposta se fundamenta na utilização de regras nebulosas (fuzzy rules) baseadas em level sets, possibilitando uma modelagem interpretável e não linear.

A construção do modelo envolve duas etapas principais:

- Estruturação do espaço de entrada-saída fuzzy via clusterização — utilizando o algoritmo Gustafson-Kessel, que permite detectar estruturas elípticas nos dados e fornece uma base para a geração automática das regras fuzzy;

- Aprendizado online dos parâmetros consequentes — por meio do algoritmo Recursive Correntropy-Based Least Squares (RCLS), que permite atualizações eficientes dos parâmetros em tempo real, garantindo adaptabilidade ao mercado.

Ao longo do desenvolvimento, foram realizados estudos teóricos e implementações progressivas do modelo proposto, com foco em sua modularidade, capacidade de adaptação e fidelidade às formulações do artigo de referência do Prof. Dr. Leandro Maciel. 

---

## 🎯 Objetivos

- Estudar os fundamentos dos modelos fuzzy baseados em level sets aplicados à previsão de volatilidade.

- Estudar o algoritmo Recursive Correntropy-Based Least Squares (RCLS) e sua aplicação ao ajuste online de parâmetros.

- Implementar de forma incremental o modelo fuzzy adaptativo proposto por Prof. Dr. Leandro Maciel, estruturando o pipeline completo de inferência.

- Investigar e aplicar o algoritmo de clusterização fuzzy Gustafson-Kessel para definir o número e a forma das regras fuzzy.

- Desenvolver mecanismos para seleção automática de parâmetros e regularização do modelo.


---

## 📅 Cronograma

### 📅 Março  (25 horas) 
- Estudo introdutório sobre inferência fuzzy. - 10h
- Estudo sobre a construção de regras fuzzy e definição de funções de pertinência em modelos fuzzy baseados em level sets. - 15h

    ###### *Algumas das referencias usadas foram [1](https://link.springer.com/article/10.1007/s10614-015-9535-2) e [2](https://www.sciencedirect.com/science/article/pii/S0957417422014981)*
---

### 📅 Abril  (30 horas)
- Estudo do algoritmo **Recursive Correntropy-Based Least Squares (RCLS)** para ajuste online de parâmetros do modelo. - 10h 
    ###### *Algumas das referencias usadas foram [1](https://www.youtube.com/watch?v=Q1H2kckjdQ0) e [2](https://www.youtube.com/watch?v=y0O0WaPoJSw)*
- Início da implementação do [modelo fuzzy adaptativo proposto pelo Prof. Dr. Leandro Maciel](https://github.com/GB-Navarro/MAC0215/tree/main/refer%C3%AAncias) — *estruturação inicial das ideias do artigo em código*. - 20h

---

### 📅 Maio  (40 horas)

- Estudo sobre o [algoritmo de clusterização fuzzy Gustafson‐Kessel](https://ieeexplore.ieee.org/document/4046215) - 15h 
- Continuação da implementação do [modelo fuzzy adaptativo proposto pelo Prof. Dr. Leandro Maciel](https://github.com/GB-Navarro/MAC0215/tree/main/refer%C3%AAncias) — *Refinamento do código criado até então e implementação da clusterização fuzzy vista para a seleção do número de regras do modelo*. - 25h

---

### 📅 Junho  (25 horas)

- Continuação da implementação do [modelo fuzzy adaptativo proposto pelo Prof. Dr. Leandro Maciel](https://github.com/GB-Navarro/MAC0215/tree/main/refer%C3%AAncias) — *Aperfeiçoamento do código criado até então e início da implementação de um mecanismo para seleção automática de parâmetros*. - 25h

---

### 📅 Julho – Dezembro  
- Definição de etapas futuras conforme progresso do desenvolvimento.  
- Expansão e otimização do modelo fuzzy.  
- Validação dos resultados e ajustes finais.  


---

## ✅ Status Atual do Projeto (Progresso até Junho)

| Etapa                                                                                         | Status         |
|-----------------------------------------------------------------------------------------------|----------------|
| Estudo introdutório sobre inferência fuzzy                                                    | ✅ Concluído    |
| Estudo da construção de regras fuzzy e definição de funções de pertinência com level sets     | ✅ Concluído    |
| Estudo do algoritmo Recursive Correntropy-Based Least Squares (RCLS)                     | ✅ Concluído    |
| Estudo do modelo fuzzy adaptativo proposto pelo Prof. Dr. Leandro Maciel                      | ✅ Concluído    |
| Estruturação inicial do código do modelo fuzzy adaptativo                                     | ✅ Concluído    |
| Estudo do algoritmo de clusterização fuzzy Gustafson‐Kessel                                   | ✅ Concluído    |
| Integração da clusterização Gustafson-Kessel para definição do número de regras fuzzy no modelo        | ✅ Concluído    |
| Início do desenvolvimento do mecanismo de seleção automática de parâmetros                    | ✅ Concluído |
| Definição preliminar das etapas futuras (validação, avaliação e expansão do modelo)           | ✅ Concluído    |

---

## 🔗 Links Importantes
- 📁 [Repositório de códigos](https://github.com/GB-Navarro/ALSM_EUSFLAT_2025)
---
