# Trabalho_Grafos

## Integrantes

- Alexandre Marques Spinola

- Gustavo do Carmo Resende

# 🚚 Projeto de Otimização Logística com Grafos

Este projeto implementa um algoritmo de **Path Scanning** para resolver problemas logísticos baseados em grafos (multigrafos direcionados), como o **Capacitated Arc Routing Problem (CARP)**. Ele foi desenvolvido como parte da disciplina de **Grafos**, e roda totalmente no **Google Colab**.

---

## 📌 Funcionalidades

- Leitura de instâncias logísticas em formato `.dat` ou `.txt`
- Cálculo de estatísticas do grafo (graus, densidade, componentes, etc.)
- Construção de matriz de distâncias com Floyd-Warshall
- Implementação do algoritmo **Path Scanning** com critério baseado na menor distância
- Geração de rotas viáveis respeitando:
  - Capacidade dos veículos
  - Cobertura única de serviços
- Formatação de saída compatível com o esperado pelo professor

---

## ▶️ Como executar o projeto no Google Colab

1. Acesse o Colab: [https://colab.research.google.com/](https://colab.research.google.com/)
2. Clique em **"Upload"** e envie o notebook `.ipynb` do projeto.
3. **Envie os arquivos necessários**:
   - A primeira instância deve ser inserida no terminal 
   - Para a segunda etapa, deve-se colocar uma pasta com o nome MCGRP contendo todas as instâncias `.dat`
4. Execute as células em ordem, começando pelas de leitura do grafo.
