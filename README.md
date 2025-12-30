# 🧠 Missionários e Canibais — Inteligência Artificial

Este projeto implementa a solução do clássico problema dos **Missionários e Canibais**, amplamente utilizado no estudo de **Inteligência Artificial clássica**, **algoritmos de busca** e **modelagem de estados**.

O objetivo é encontrar uma sequência válida de movimentos que permita atravessar todos os personagens de uma margem do rio para a outra, respeitando regras de segurança e garantindo que estados inválidos não sejam gerados.

---

## 📌 Descrição do Problema

Três missionários e três canibais precisam atravessar um rio utilizando um barco com capacidade limitada.  
A qualquer momento, em nenhuma das margens o número de canibais pode ser maior que o de missionários, caso contrário os missionários estariam em risco.

O desafio consiste em:
- Modelar corretamente os **estados possíveis**
- Definir **regras de transição**
- Evitar estados inválidos
- Encontrar a **solução ótima**

---

## 🧠 Abordagem Utilizada

A solução foi desenvolvida em **Python**, utilizando conceitos fundamentais de Inteligência Artificial:

- Modelagem formal de estados (margem esquerda, margem direita e posição do barco)
- Definição de regras de transição entre estados
- Validação automática de estados válidos
- Implementação do algoritmo de **Busca em Largura (BFS)** para garantir a solução ótima
- Uso de estruturas de dados como **fila (`deque`)** para controle da busca

Essa abordagem garante que a primeira solução encontrada seja a de menor custo (menor número de movimentos).

---

## 🛠️ Tecnologias Utilizadas

- Python  
- Algoritmos de Busca  
- Estrutura de Dados  
- Inteligência Artificial Clássica  
- Google Colab  

---

## ▶️ Como Executar

1. Clone o repositório:
```bash
git clone https://github.com/seu-usuario/nome-do-repositorio.git
```

2. Acesse o diretório do projeto:
```bash
cd nome-do-repositorio
```

3. Execute o notebook:
- Abra o arquivo `.ipynb` localmente **ou**
- Acesse diretamente pelo Google Colab

---

## 📈 Resultados

O algoritmo encontra uma sequência válida de movimentos que resolve o problema respeitando todas as restrições impostas, demonstrando a eficácia da modelagem do problema e da utilização de busca em largura.

O projeto evidencia a importância da **modelagem correta do problema** antes da implementação da solução, um princípio essencial em projetos de Inteligência Artificial.

---

## 📚 Aprendizados

- Importância da modelagem de estados em problemas de IA
- Aplicação prática de algoritmos de busca
- Uso eficiente de estruturas de dados
- Separação entre regras do problema e lógica de busca
- Pensamento lógico aplicado à tomada de decisão

---

## 🔗 Links

- 🔹 Portfólio: *[JoseTayllan](https://portfolio-hub-silk.vercel.app)*  
 

---

## 👤 Autor

**José Tayllan**  
Formado em Gestão da Tecnologia da Informação  
Foco em Inteligência Artificial, algoritmos e lógica computacional.
