# Atividade P3: Otimização de Hiperparâmetros de MLP com Algoritmos Evolutivos  

Este repositório contém a implementação da Atividade P3 da disciplina de Inteligência Artificial, focada na otimização de hiperparâmetros de uma rede neural Multi-Layer Perceptron (MLP) utilizando um Algoritmo Genético.  



## 📌 Descrição do Projeto  

O objetivo deste trabalho é aplicar técnicas de Computação Evolutiva para encontrar uma combinação eficiente de hiperparâmetros para o `MLPClassifier` do scikit-learn. A abordagem compara o desempenho de uma configuração padrão (baseline) com três variações otimizadas por meio de um Algoritmo Genético.

A eficácia das soluções é avaliada por métricas como **F1-Score**, **Precisão**, **Recall** e também pelo **tempo de execução**, permitindo uma análise crítica entre desempenho e custo computacional.

Todo o desenvolvimento está contido em um único Jupyter Notebook (`.ipynb`), organizado da seguinte forma:  

- Fundamentação teórica sobre GAs e tuning de hiperparâmetros  
- Implementação do baseline e da classe de algoritmo genético  
- Execução de quatro experimentos  
- Análise de resultados com gráficos e tabelas comparativas  



## 🛠 Tecnologias Utilizadas  

- **Python 3**  
- **Jupyter Notebook**  
- **Scikit-learn** — para o MLP e cálculo das métricas  
- **DEAP** — biblioteca de Algoritmos Evolutivos (se aplicável)  
- **NumPy** — operações vetoriais e manipulação de indivíduos  
- **Pandas** — tabulação dos resultados  
- **Matplotlib** — visualização dos gráficos  



## ▶️ Como Executar  

1. Clone o repositório:  
   ```bash
   git clone https://github.com/NicksTheJesus/Atividade-IA.git
````

2. Acesse o notebook:
   `atividade_p3.ipynb`

3. Execute-o em um ambiente compatível com Jupyter Notebook (ex: [Google Colab](https://colab.research.google.com), Jupyter Lab ou VS Code).

4. Rode todas as células sequencialmente para reproduzir os experimentos e gerar os gráficos comparativos.



## 👥 Reconhecimentos e Direitos Autorais

@autor: Maria Luiza Monteiro e Nickolas Ferreira Maiolino
@contato: [maria.lm@discente.ufma.br](mailto:maria.lm@discente.ufma.br) e [nickolas.fm@discente.ufma.br](mailto:nickolas.fm@discente.ufma.br)
@data última versão: 16/07/2025
@versão: 1.0
@outros repositórios: [https://github.com/NicksTheJesus/Atividade-IA](https://github.com/NicksTheJesus/Atividade-IA)

**@Agradecimentos:** Universidade Federal do Maranhão (UFMA), Professor Doutor Thales Levi Azevedo Valente, e colegas de curso.



## 📝 Licença (MIT)

Este material é resultado de um trabalho acadêmico para a disciplina **INTELIGÊNCIA ARTIFICIAL**, sob a orientação do professor **Dr. THALES LEVI AZEVEDO VALENTE**, semestre letivo **2025.1**, curso **Engenharia da Computação**, na **Universidade Federal do Maranhão (UFMA)**.

Todo o material é software livre: pode ser usado para fins acadêmicos e comerciais sem custo. Ele é licenciado sob os termos da Licença MIT, compatível com a GPL e de código aberto.

O único requisito é que, ao utilizar o material, os autores sejam devidamente creditados.

<details>
<summary>Clique para ver a Licença MIT completa</summary>

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

</details>
