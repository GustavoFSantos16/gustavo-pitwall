# 🏎️ Desafio Pit Wall — GP de São Paulo

Projeto desenvolvido para a disciplina de **Linguagem de Marcação (LIMA)**, ministrada pelos professores **André Denani** e **Raul Lopes**. 

O objetivo do desafio é recriar a página institucional e comercial do **GP de São Paulo de Fórmula 1 (Autódromo de Interlagos)** aplicando conceitos avançados de estruturação com HTML5 e estilização com CSS3, garantindo suporte completo para desktop e dispositivos móveis.

---

## 📸 Sobre o Projeto

A aplicação consiste em uma landing page responsiva que apresenta:
1. **Topo de Navegação (Topbar):** Logo customizado com tipografia itálica, menu central de links rápidos e botão de chamada para ação (*CTA*).
2. **Hero Banner & Zebra:** Apresentação principal do evento com degradê com corte seco em diagonal, estatísticas rápidas do circuito (`voltas`, `km por volta`, `curvas`) e a tradicional faixa zebra de pista feita puramente em CSS (`repeating-linear-gradient`).
3. **Grid de Pilotos:** Cards estilizados utilizando CSS Grid (`auto-fit`) e temas individuais com variáveis CSS (`:root`) para as cores de cada equipe (*Ferrari, McLaren, Mercedes, Audi*).
4. **Tabela de Classificação:** Tabela responsiva (`thead` e `tbody`) indicando o líder do campeonato, vitórias e pontuação, além de formulário funcional para filtragem de pilotos.
5. **Formulário de Ingressos:** Layout estruturado via `form-grid` com suporte a múltiplos tipos de campos (`text`, `email`, `select`, `date`, `number`, `file` e `textarea`).
6. **Rodapé Identificado:** Identificação do desenvolvedor conforme os requisitos da atividade.

---

## 🧰 Tecnologias e Conceitos Utilizados

- **HTML5:** Marcação semântica (`header`, `nav`, `main`, `section`, `table`, `form`, `footer`).
- **CSS3 Moderno:**
  - **Variáveis (`:root`):** Padronização de cores gerais e personalizadas por equipe.
  - **Flexbox:** Alinhamento do topo, conteúdo do hero, estatísticas e filtros.
  - **CSS Grid (`auto-fit` e `form-grid`):** Responsividade dos cards de pilotos e layout do formulário.
  - **Degradês & Texturas:** `linear-gradient` com corte seco e `repeating-linear-gradient` para a zebra da pista.
  - **Efeitos Dinâmicos:** Microinterações com `:hover` e desfoque com `backdrop-filter`.
- **Google Fonts:** Tipografia externa [*Titillium Web*](https://fonts.google.com/specimen/Titillium+Web).
- **Responsividade (`@media`):** Adaptação completa do layout para telas de celulares e tablets.

---

## 📂 Estrutura de Pastas

```text
pit-wall/
├── index.html
├── styles.css
├── README.md
└── img/
    └── piloto.jpg
```

---

## 🚀 Como Executar o Projeto

1. **Clonar o Repositório:**
   ```bash
   git clone https://github.com/SEU_USUARIO/pit-wall.git
   ```
2. **Abrir a Aplicação:**
   - Navegue até a pasta do projeto e abra o arquivo `index.html` em qualquer navegador web.
   - Ou abra a pasta inteira no **VS Code** e execute com a extensão **Live Server**.

---

## 👤 Autor

Projeto de estudo desenvolvido por **Gustavo Ferreira Santos**.

---
*PITWALL · Projeto de estudo de HTML e CSS · Pontos e números da tabela são ilustrativos*