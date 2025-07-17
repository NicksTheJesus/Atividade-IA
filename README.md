-----

# Atividade P3: Otimização de Hiperparâmetros de MLP com Algoritmos Evolutivos

Este repositório contém a implementação da Atividade P3 da disciplina de Inteligência Artificial, focada na otimização de hiperparâmetros de uma rede neural Multi-Layer Perceptron (MLP) utilizando um Algoritmo Genético.

-----

## 📌 Descrição do Projeto

O objetivo deste trabalho é aplicar técnicas de Computação Evolutiva para encontrar uma combinação ótima de hiperparâmetros para o `MLPClassifier` do scikit-learn. A abordagem compara o desempenho de um modelo com configuração padrão (baseline) com três variações otimizadas por um Algoritmo Genético.

A eficácia dos modelos é avaliada por métricas como **F1-Score**, **Precisão** e **Recall**, além do **tempo de execução**, permitindo uma análise crítica do trade-off entre performance e custo computacional.

O projeto completo está documentado em um único Jupyter Notebook (`atividade_p3.ipynb`), que inclui:

  - Fundamentação teórica da otimização.
  - Implementação do modelo baseline.
  - Configuração e execução dos experimentos com o Algoritmo Genético.
  - Análise de resultados com tabelas e gráficos comparativos.

-----

## 🛠️ Tecnologias Utilizadas

  - **Python 3**
  - **Jupyter Notebook**
  - **Scikit-learn**
  - **DEAP**
  - **NumPy**
  - **Pandas**
  - **Matplotlib**

-----

## ▶️ Como Executar

Para executar este projeto, siga os passos abaixo.

### Pré-requisitos

  - [Python 3.8+](https://www.python.org/downloads/)
  - [Git](https://git-scm.com/downloads)

### Passos

1.  **Clone o repositório:**

    ```bash
    git clone https://github.com/NicksTheJesus/Atividade-IA.git
    cd Atividade-IA
    ```

2.  **Instale as dependências:**
    (É uma boa prática criar um ambiente virtual antes de instalar)

    ```bash
    pip install -r requirements.txt
    ```

    > **Nota:** Se não tiver um `requirements.txt`, você pode criá-lo com o conteúdo: `scikit-learn deap numpy pandas matplotlib jupyter`

3.  **Inicie o Jupyter Notebook:**

    ```bash
    jupyter notebook atividade_p3.ipynb
    ```

    Ou abra o notebook no seu ambiente preferido (Google Colab, VS Code, etc).

4.  **Execute as células:**
    Rode todas as células sequencialmente para reproduzir os experimentos e gerar os resultados.

-----

## 👥 Autores e Agradecimentos

Este projeto foi desenvolvido por:

  - **Maria Luiza Monteiro** - [maria.lm@discente.ufma.br](mailto:maria.lm@discente.ufma.br)
  - **Nickolas Ferreira Maiolino** - [nickolas.fm@discente.ufma.br](mailto:nickolas.fm@discente.ufma.br)

**Agradecimentos:**
Agradecemos à Universidade Federal do Maranhão (UFMA), ao Professor Doutor Thales Levi Azevedo Valente pela orientação, e aos nossos colegas de curso pelo apoio.

-----

## 📝 Licença

Este material é resultado de um trabalho acadêmico para a disciplina **INTELIGÊNCIA ARTIFICIAL**, sob a orientação do professor **Dr. THALES LEVI AZEVEDO VALENTE**, semestre letivo **2025.1**, curso **Engenharia da Computação**, na **Universidade Federal do Maranhão (UFMA)**.

O projeto é licenciado sob a Licença MIT. O único requisito para seu uso é a devida creditação aos autores.

\<details\>
\<summary\>Clique para ver a Licença MIT completa\</summary\>

**The MIT License (MIT)**

Copyright (c) 2025 Maria Luiza Monteiro e Nickolas Ferreira Maiolino

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

\</details\>