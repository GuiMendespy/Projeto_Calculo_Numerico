```markdown
# Inpainting & Interpolação Linear em Imagens Pixeladas 🧮🖼️

Este projeto aplica conceitos de **Cálculo Numérico** para resolver problemas de baixa resolução (pixelização) e perda de dados em imagens digitais. Através de métodos de interpolação e técnicas de *inpainting*, o algoritmo reconstrói e suaviza matrizes de pixels de forma precisa.

---

## 💡 O Projeto

Quando uma imagem é ampliada ou corrompida, lacunas de informação surgem em sua matriz de pixels. Este repositório estuda e implementa soluções numéricas para esse problema:

1. **Interpolação Linear / Bilinear:** Estima o valor de novos pixels com base na média ponderada dos pixels vizinhos conhecidos, reduzindo o efeito de "serrilhado" em imagens pixeladas.
2. **Inpainting Numérico:** Restaura regiões danificadas, removendo ruídos ou preenchendo partes ausentes de uma imagem utilizando aproximações lineares de fronteira.

---

## 🛠️ Tecnologias e Bibliotecas

O projeto foi totalmente desenvolvido em **Python**, utilizando o ecossistema científico:

- **NumPy:** Manipulação eficiente das matrizes de pixels (imagens).
- **Matplotlib:** Visualização dos resultados e comparação "Antes vs. Depois".
- **OpenCV / Pillow:** Carregamento, tratamento inicial e exportação das imagens.
- **Jupyter Notebook:** Documentação passo a passo dos experimentos matemáticos.

---

## 🚀 Como Executar

1. Clone o repositório:
   ```bash
   git clone [https://github.com/GuiMendespy/Projeto_Calculo_Numerico.git](https://github.com/GuiMendespy/Projeto_Calculo_Numerico.git)
