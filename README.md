# 🛰️ Dashboard AgroSustentável

> **Projeto desenvolvido para o Concurso Agrinho 2026 - Categoria Programação.**
> *Tema: "Agro forte, futuro sustentável: equilíbrio entre produção e meio ambiente"*.

## 📌 Sobre o Projeto

Este artefato tecnológico foi desenvolvido como parte da formação de estudantes da rede estadual de ensino. O objetivo é oferecer uma ferramenta de visualização de dados que auxilie o produtor rural a encontrar o equilíbrio ideal entre a **capacidade produtiva** e a **preservação ambiental**.

O dashboard permite a entrada de dados reais da propriedade (hectares de produção e hectares de preservação) e fornece um feedback visual imediato sobre a conformidade com as metas de sustentabilidade, unindo conceitos de agronegócio e pensamento computacional.

## 📱 Responsividade e Interface

O projeto foi desenvolvido aplicando conceitos de **Mobile-First** e layouts flexíveis (**Flexbox**), garantindo que a interface se adapte a diferentes tamanhos de tela, um critério essencial de usabilidade previsto no regulamento.

### Visualização em Desktop

Em telas maiores, o dashboard organiza os cards de indicadores lado a lado, otimizando o espaço horizontal para uma leitura rápida dos dados.

| Estado: Aguardando Dados | Estado: Sustentável (Sucesso) |
| :---: | :---: |
| ![Demonstração do Dashboard em visualização desktop, mostrando os cards de produção e preservação lado a lado com cores neutras.](https://via.placeholder.com/800x450.png?text=Dashboard+Desktop+-+Aguardando) | ![Demonstração do Dashboard em visualização desktop, com o card de preservação e a barra de status na cor verde, indicando conformidade ambiental.]([https://via.placeholder.com/800x450.png?text=Dashboard+Desktop+-+Sustentavel](https://github.com/kheronn/formacao-agrinho-2026-turma/blob/main/desktop.webp)) |

### Visualização em Dispositivos Móveis

Em telas menores (celulares), o layout se ajusta automaticamente. Os elementos são empilhados verticalmente, mantendo a legibilidade e a facilidade de interação com os campos de entrada e o botão de ação.

| Visualização Mobile (Empilhada) |
| :---: |
| ![Demonstração do Dashboard em visualização mobile, mostrando a interface adaptada para telas estreitas, com os elementos empilhados verticalmente. ](https://github.com/kheronn/formacao-agrinho-2026-turma/blob/main/note.png) |

## 🚀 Tecnologias e Fundamentos

O projeto utilizao as linguagens fundamentais da Web de forma estruturada:

* **HTML5**: Estruturação semântica (`header`, `section`, `div`) e organização de dados de entrada (`input type="number"`) e saída.
* **CSS3**: Estilização focada em usabilidade, utilizando **Flexbox** para o layout responsivo e **Variáveis CSS** (`:root`) para a identidade visual (Verde).
* **JavaScript**: Implementação da lógica de cálculo (proporção de 20% de reserva legal) e manipulação dinâmica do DOM para feedback visual (troca de classes CSS) em tempo real.

## 🛠️ Funcionalidades

- [x] Entrada de dados para Hectares de Produção e Preservação.
- [x] Cálculo automático da porcentagem de área verde em relação à área total.
- [x] **Interface Reativa**: O painel altera suas cores (Verde Sucesso / Laranja Alerta) e mensagens conforme os critérios de sustentabilidade são atingidos.
- [x] Layout 100% responsivo para dispositivos móveis e desktop.

## 📁 Estrutura de Arquivos

Seguindo as boas práticas de desenvolvimento e organização sugeridas na formação docente, o projeto está modularizado:

* `index.html`: Marcação semântica e estrutura do documento.
* `style.css`: Regras de estilo, layout (Flexbox), responsividade (Media Queries) e estados visuais.
* `script.js`: Lógica de processamento, cálculos e interatividade do DOM.

## ⚖️ Regulamento e Critérios

Este projeto foi orientado por professor regente e atende aos seguintes critérios da rubrica oficial do Concurso Agrinho:

1.  **Complexidade**: Uso correto de tags de organização e propriedades avançadas de CSS (Flexbox, Estados).
2.  **Usabilidade**: Navegação intuitiva, design responsivo e ausência de erros de código.
3.  **Originalidade**: Código autoral focado na temática de equilíbrio agro-ambiental proposta pelo SENAR-PR.

---

### 👨‍🏫 Orientação Docente

Este repositório serve como base base pedagógica para a formação de professores de programação na Educação Básica, visando o engajamento de estudantes dos Anos Finais do Ensino Fundamental e Ensino Médio nas trilhas de tecnologia.

---
