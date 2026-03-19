# 🛡️ Guild Tracker - RPG Dashboard

O **Guild Tracker** é uma interface interativa e imersiva para monitoramento de guildas em cenários de RPG. O projeto foca no gerenciamento de estatísticas vitais e na gamificação do progresso dos jogadores através de um ranking dinâmico de baús.

---

## ✨ Funcionalidades

* **Dual-View System**: Alterne entre o **Mural de Heróis** (cards visuais) e a **Dungeon View** (painel de análise).
* **Ranking em Tempo Real**: Letreiro animado estilo "Ticker" que exibe a classificação dos jogadores por quantidade de baús.
* **Gestão CRUD**: Adição, edição e remoção de membros diretamente pelo dashboard.
* **Análise de Dados**:
    * Cálculo automático de Dificuldade Média.
    * Média de Vida (PV) do grupo.
    * Gráficos comparativos de tesouros usando **Chart.js**.
* **Persistência de Dados**: Utiliza `localStorage` para manter as informações salvas mesmo após fechar o navegador.

---

## 🚀 Tecnologias

Este projeto utiliza uma stack focada em performance e estética *dark mode*:

* **HTML5/CSS3**: Estrutura e animações customizadas.
* **Tailwind CSS**: Estilização utilitária e responsividade.
* **JavaScript (Vanilla)**: Lógica de estado e manipulação do DOM.
* **Chart.js**: Renderização de gráficos de barras para estatísticas.
* **Google Fonts**: Tipografia *JetBrains Mono* para uma estética técnica/RPG.

---

## 🛠️ Como Utilizar

Por ser uma aplicação baseada em CDN, não é necessário configurar um ambiente de desenvolvimento complexo:

1.  Faça o download ou clone este repositório.
2.  Abra o arquivo `index.html` em qualquer navegador moderno.
3.  **No Mural**: Clique em "Editar" para carregar os dados de um herói no formulário.
4.  **No Dashboard**: Use o botão flutuante (ícone de grade) no canto inferior direito para alternar entre as visões.
5.  **Sincronizar**: Preencha o formulário no rodapé para adicionar novos membros ou salvar alterações.

---

## 📊 Estrutura de Dados

Cada personagem possui quatro atributos principais acompanhados no sistema:

| Atributo | Descrição |
| :--- | :--- |
| **NOME** | Identificador do herói. |
| **DIF** | Nível de dificuldade ou desafio do personagem. |
| **PV** | Pontos de Vida atuais. |
| **BAÚS** | Quantidade de tesouros coletados (define o ranking). |

---

## 📜 Licença

Este projeto é para fins educacionais e de entretenimento. Sinta-se à vontade para adaptar para sua própria mesa de RPG!

---
Desenvolvido com foco em imersão e dados. 🎲
---
Powered by AI
