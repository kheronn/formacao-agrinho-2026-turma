# 🛰️ Dashboard AgroSustentável

> **Projeto desenvolvido para o Concurso Agrinho 2026 - Categoria Programação.**
> *Tema: "Agro forte, futuro sustentável: equilíbrio entre produção e meio ambiente"*.

## 📌 Sobre o Projeto

Este artefato tecnológico foi desenvolvido como parte da formação de estudantes da rede estadual de ensino. O objetivo é oferecer uma ferramenta de visualização de dados que auxilie o produtor rural a encontrar o equilíbrio ideal entre a **capacidade produtiva** e a **preservação ambiental**.

O dashboard permite a entrada de dados reais da propriedade (hectares de produção e hectares de preservação) e fornece um feedback visual imediato sobre a conformidade com as metas de sustentabilidade, unindo conceitos de agronegócio e pensamento computacional.

## 📱 Responsividade e Interface

O projeto foi desenvolvido aplicando conceitos de **Mobile-First** e layouts flexíveis (**Flexbox**), garantindo que a interface se adapte a diferentes tamanhos de tela, um critério essencial de usabilidade previsto no regulamento.


### Visualização em Desktop

Em telas maiores, o dashboard organiza os indicadores horizontalmente para otimizar a leitura dos dados.

<div align="center">
  <img src="https://github.com/kheronn/formacao-agrinho-2026-turma/blob/main/desktop.webp" width="55%" alt="Dashboard Desktop Sustentável">
</div>

Em telas menores (celulares), o layout se ajusta automaticamente. Os elementos são empilhados verticalmente, mantendo a legibilidade e a facilidade de interação com os campos de entrada e o botão de ação.

### Visualização Mobile (Empilhada) 
| :---: |
<div align="center">
  <img src="https://github.com/kheronn/formacao-agrinho-2026-turma/blob/main/mobile.png" width="20%" alt="Dashboard Mobile">
</div>

## 🚀 Tecnologias e Fundamentos

O projeto é composto  por linguagens fundamentais da Web de forma estruturada:

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

Este projeto foi orientado por professor regente e atende aos seguintes critérios da rubrica oficial do Concurso Agrinho em 2024 e 2025.
No momento da formação o edital de 2026 ainda não tinha sido publicado

1.  **Complexidade**: Uso correto de tags de organização e propriedades avançadas de CSS (Flexbox, Estados).
2.  **Usabilidade**: Navegação intuitiva, design responsivo e ausência de erros de código.
3.  **Originalidade**: Código autoral focado na temática de equilíbrio agro-ambiental proposta pelo SENAR-PR.

---

### 👨‍🏫 Orientação Docente

Este repositório serve como base base pedagógica para a formação de professores de programação na Educação Básica, visando o engajamento de estudantes do Ensino Médio nos componentes de Educação Digital das 1ªs séries e trilhas de programação das 2ªs e 3ªs.

---
