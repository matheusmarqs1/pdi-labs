# 🔬 Lab 01: Fundamentos, Resoluções, Quantização e Ruído

Neste primeiro laboratório, exploramos os conceitos fundamentais de Processamento Digital de Imagens (PDI) utilizando Python, OpenCV e Matplotlib, com base na literatura de Gonzalez & Woods. O objetivo é analisar matematicamente e visualmente como a manipulação da matriz de pixels afeta a qualidade da imagem.

## 🚀 Tópicos Abordados

* **Manipulação Básica:** Leitura de imagens em tons de cinza (`uint8`), cálculo de ocupação em memória RAM e inversão tonal (criação de negativo para realce de contraste).
* **Resolução e Quantização:** * Redução da resolução de intensidade (quantização de 8 bits até 1 bit) e análise do efeito de falsos contornos (posterização).
  * Redução da resolução espacial (subamostragem) e perda de detalhes anatômicos.
* **Compressão:** Comparação do impacto visual e perda de dados utilizando compressão JPEG em diferentes níveis (95% vs 50%).
* **Morfologia Matemática:** Estudo dos algoritmos de vizinhança e conectividade (4-adjacente e 8-adjacente) em imagens binárias para contagem de objetos.
* **Simulação de Sensores:** Injeção de ruído artificial para simular a degradação da imagem capturada por sensores de baixa qualidade.
* **Análise de Dados:** Uso de **Histogramas** para validar e ilustrar graficamente as alterações tonais e estruturais das imagens em cada etapa do experimento.

## 📂 Estrutura dos Arquivos
* `Lab1.ipynb`: O código-fonte executável contendo os algoritmos, plotagens visuais (lado a lado) e reflexões teóricas formatadas em Markdown/LaTeX.
* `Lab1.pptx`: Apresentação executiva focada nos resultados visuais (Antes x Depois) para a defesa em sala de aula.