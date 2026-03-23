# Processamento Digital de Imagens (PDI) 📷⚙️

Repositório destinado aos laboratórios e projetos práticos desenvolvidos na disciplina de Processamento Digital de Imagens do curso de Engenharia de Computação (UFG). 

## 🎯 Objetivo Geral
Explorar os fundamentos matemáticos e algorítmicos da visão computacional, incluindo a manipulação de matrizes de pixels, transformações espaciais e tonais, e filtragem de imagens digitais. O domínio prático dessas técnicas forma a base essencial para o desenvolvimento de sistemas visuais aplicados a projetos complexos de tecnologia.

## 🛠️ Tecnologias Utilizadas
* **Python 3**
* **NumPy:** Essencial para o cálculo vetorizado e manipulação pesada das matrizes de imagem.
* **OpenCV (`cv2`):** Utilizada para a leitura padronizada e manipulação de espaços de cor.
* **Matplotlib:** Empregada para a plotagem, criação de gráficos de histograma e comparação analítica dos resultados visuais.

---

## 📂 Índice de Laboratórios

### [Lab 01: Manipulação, Resoluções, Quantização e Ruído](./lab01_introducao/)
Primeiro experimento da disciplina focado na compreensão de como a manipulação de dados afeta a qualidade visual.
* **Manipulação Básica:** Leitura em `uint8`, inversão tonal (negativo).
* **Resolução e Quantização:** Impacto da redução de bits (falsos contornos) e redução da resolução espacial (subamostragem).
* **Compressão:** Comparação de perda de dados utilizando compressão JPEG (95% vs 50%).
* **Morfologia:** Estudo de conectividade de pixels (4-adjacente e 8-adjacente) para análise de objetos.
* **Ruído:** Simulação de degradação em sensores de baixa qualidade. Empregada para a plotagem e comparação lado a lado dos resultados visuais.
