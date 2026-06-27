<h1 align="center">Luiz Guilherme Faria</h1>

<p align="center">
Estudante de Engenharia de Software na Universidade de Brasília (UnB/FCTE). Tenho particular interesse em compreender os fundamentos por trás das tecnologias que utilizo — de redes neurais implementadas do zero a compiladores e estruturas de dados construídos sem o auxílio de bibliotecas prontas. Desenvolvo majoritariamente em <b>C++</b> e <b>Python</b>, com ênfase em Inteligência Artificial, algoritmos e sistemas.
</p>

---

## Tecnologias e Ferramentas

**Linguagens**

![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)

**Frameworks e Bibliotecas**

![Eigen](https://img.shields.io/badge/Eigen-AB2B28?style=for-the-badge)
![Vue.js](https://img.shields.io/badge/Vue.js-4FC08D?style=for-the-badge&logo=vuedotjs&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white)
![Flex & Bison](https://img.shields.io/badge/Flex_%26_Bison-005599?style=for-the-badge)

**Ferramentas e Infraestrutura**

![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![CMake](https://img.shields.io/badge/CMake-064F8C?style=for-the-badge&logo=cmake&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![LaTeX](https://img.shields.io/badge/LaTeX-008080?style=for-the-badge&logo=latex&logoColor=white)

---

## Projetos em Destaque

### Inteligência Artificial e Machine Learning

**[Turing — Deep Learning Framework](https://github.com/luizfaria1989/Turing)**
Framework educacional de Deep Learning desenvolvido inteiramente em **C++20**, utilizando a biblioteca **Eigen** para álgebra linear. Implementa, do zero, camadas densas, funções de ativação (ReLU, Sigmoid, Tanh, Softmax), otimizadores (SGD, Momentum, NAG), o algoritmo de backpropagation e um carregador nativo para o dataset MNIST. A API foi projetada com inspiração em frameworks consolidados como Keras e PyTorch.
`C++20` · `Eigen` · `CMake` · `Doxygen/Sphinx`

**[vigIA — Previsão de Risco de Incêndio em Goiás](https://github.com/luizfaria1989/vigIA)** · [Demonstração](https://vig-ia.vercel.app/)
Sistema de previsão do risco de queimadas para os 244 municípios de Goiás ao longo dos cinco dias subsequentes. Modelos de aprendizado de máquina analisam dados climáticos e o histórico de focos de incêndio (INPE e Open-Meteo, período de 2015 a 2025), gerando diariamente um boletim com mapa interativo categorizado por nível de risco.
`Python` · `Machine Learning` · `JavaScript` · `CSS` · `Vercel`

**[Inteligência Artificial — Livro (TeX)](https://github.com/luizfaria1989/inteligencia-artificial-fundamentos-aprendizado-de-maquina-classico-aprendizado-profundo)**
Obra em português dedicada aos fundamentos de Redes Neurais, Machine Learning Clássico e Deep Learning. Constitui a base teórica que acompanha o framework Turing, abordando a formulação matemática subjacente aos algoritmos.
`LaTeX`

---

### Estruturas de Dados e Algoritmos (EDA2)

Conjunto de projetos desenvolvidos em **C++17**, com todas as estruturas de dados implementadas do zero, acompanhadas de benchmarks de desempenho e recursos de visualização.

**[Grafos — BFS e DFS](https://github.com/luizfaria1989/G5_Grafos_EDA2-2026.1)**
Resolução de labirintos por meio da modelagem de cada célula como nó de um grafo. Implementa os algoritmos BFS e DFS, além de Componentes Conectados e Grafo Reverso, contemplando onze métodos distintos de geração de labirintos e visualização animada via SFML.
`C++17` · `CMake` · `SFML`

**[Busca — Tabela Hash e Árvore Binária](https://github.com/luizfaria1989/G5_Busca_EDA2-2026.1)**
Sistema de busca de veículos por placa que combina Tabela Hash (com redimensionamento automático) e Árvore Binária de Busca, alcançando operações em O(log n) mesmo diante de um milhão de registros.
`C++17` · `CMake`

**[Ordenação — Radix Sort e Parallel Merge Sort](https://github.com/luizfaria1989/G5_Ordenacao_EDA2-2026.1)**
Implementação e análise comparativa entre o Radix Sort e o Merge Sort paralelo (com uso de threads), aplicados à ordenação de extensas listas de nomes, acompanhadas de benchmarks de tempo e gráficos de desempenho.
`C++17` · `CMake` · `Multithreading`

**[Árvore Red-Black](https://github.com/luizfaria1989/G5_Arvore_EDA2-2026.1)**
Implementação de Árvore Red-Black auto-balanceada para armazenamento e busca de registros de alunos, assegurando operações de inserção, busca e remoção em O(log n), com mensuração do tempo de busca em milissegundos.
`C++17` · `CMake`

---

### Compiladores e Sistemas

**[Mini C Compiler to Calango](https://github.com/luizfaria1989/mini-C-compiler-to-Calango)** · [Documentação](https://compiladores-1-sergio-fcte-26-1-gr10.github.io/mini-C-compiler-to-Calango/)
Compilador completo da linguagem Mini C para Calango, contemplando as quatro etapas clássicas: análise léxica, sintática, semântica e geração de código. Inclui otimizações como *constant folding* e remoção de variáveis mortas.
`C` · `Flex` · `Bison` · `Makefile`

---

### Engenharia de Software e Banco de Dados

**[Call of Cthulhu — Jogo com Banco de Dados](https://github.com/luizfaria1989/2025.1-CallOfCthulhu)** · [Documentação](https://sbd1.github.io/2025.1-CallOfCthulhu/)
Jogo de RPG inspirado no universo de H.P. Lovecraft, modelado sobre um banco de dados PostgreSQL. Abrange modelagem entidade-relacionamento, DDL/DML/DQL, triggers e stored procedures, com a lógica de jogo implementada em Python.
`PL/pgSQL` · `Python` · `PostgreSQL` · `Docker`

**[AcheiUnB — Avaliação de Qualidade de Software](https://github.com/luizfaria1989/2026-1_T01_KAY_MCNULTY)** · [Documentação](https://fcte-qualidade-de-software-1.github.io/2026-1_T01_KAY_MCNULTY/)
Auditoria de qualidade, em conformidade com a norma ISO/IEC 25010, de um sistema de achados e perdidos, contemplando testes estáticos (SonarCloud) e dinâmicos (OWASP ZAP, via GitHub Actions), com foco em segurança e manutenibilidade.
`Python` · `SonarCloud` · `OWASP ZAP` · `GitHub Actions` · `MkDocs`

**[PodePedir FCTE — Arquitetura e Desenho de Software](https://github.com/luizfaria1989/2025.2-T01-G7_PodePedirFCTE_Entrega_04)**
Projeto de uma plataforma de delivery voltada a estabelecimentos próximos à FCTE, desenvolvido ao longo de quatro entregas, com ênfase em padrões de projeto e documentação de arquitetura.
`TypeScript` · `Docsify` · `GitHub Pages`
↳ Entregas: [01](https://github.com/luizfaria1989/2025.2-T01-G7_PodePedirFCTE_Entrega_01) · [02](https://github.com/luizfaria1989/2025.2-T01-G7_PodePedirFCTE_Entrega_02) · [03](https://github.com/luizfaria1989/2025.2-T01-G7_PodePedirFCTE_Entrega_03) · [04](https://github.com/luizfaria1989/2025.2-T01-G7_PodePedirFCTE_Entrega_04)

**[Deepseek — Requisitos de Software](https://github.com/luizfaria1989/2025.1-Deepseek)** · [Documentação](https://requisitos-de-software.github.io/2025.1-Deepseek/)
Documentação completa de engenharia de requisitos aplicada ao aplicativo Deepseek, abrangendo técnicas de elicitação, modelagem e análise de requisitos.
`MkDocs` · `Engenharia de Requisitos`

---

## Estatísticas do GitHub

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=luizfaria1989&show_icons=true&theme=radical" alt="Estatísticas do GitHub" />
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com/?user=luizfaria1989&theme=radical" alt="Sequência de contribuições" />
</p>

---

## Contato

Estou à disposição para colaborações, oportunidades e troca de conhecimento. Os canais abaixo encontram-se disponíveis para contato:

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](INSIRA_AQUI_O_LINK_DO_SEU_LINKEDIN)
[![E-mail](https://img.shields.io/badge/E--mail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:INSIRA_AQUI_O_SEU_EMAIL)
[![Lattes](https://img.shields.io/badge/Currículo_Lattes-005CA9?style=for-the-badge&logo=academia&logoColor=white)](INSIRA_AQUI_O_LINK_DO_SEU_LATTES)

<!--
  Lembrete: substitua os placeholders acima pelos seus links reais:
  - LinkedIn: troque INSIRA_AQUI_O_LINK_DO_SEU_LINKEDIN pela URL do seu perfil
  - E-mail:   troque INSIRA_AQUI_O_SEU_EMAIL pelo seu endereço de e-mail
  - Lattes:   troque INSIRA_AQUI_O_LINK_DO_SEU_LATTES pela URL do seu currículo
-->

