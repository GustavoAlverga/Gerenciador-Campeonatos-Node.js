# 🏆 Gerenciador de Campeonatos

Este projeto é um sistema completo para **gerenciar campeonatos esportivos**, desenvolvido com **Node.js** no backend e **React** no frontend.  
Ele oferece **organização clara da API via Swagger** e **alta cobertura de testes automatizados**, garantindo qualidade e facilidade de manutenção.

---

## 📌 Funcionalidades Principais

- **Cadastro de Campeonatos**  
  - Estrutura flexível para gerenciar múltiplos campeonatos.
  - Possibilidade de criar competições independentes.

- **Gerenciamento de Jogadores**  
  - Adição, edição e exclusão de jogadores de um campeonato.
  - Associação direta de jogadores a competições específicas.

- **Geração de Rodadas**  
  - Criação automática ou manual de rodadas.
  - Controle de partidas e resultados por rodada.

- **Tabela de Pontuação**  
  - Atualização automática dos pontos de cada jogador a cada rodada.
  - Cálculo dinâmico do ranking com base nos resultados.
  - Exibição de classificação geral.

---

## 🛠 Tecnologias Utilizadas

**Backend (Node.js)**  
- Express.js  
- Prisma ORM  
- Swagger (documentação da API)  
- Jest / Supertest (testes unitários e de integração)  

**Frontend (React)**  
- React.js com Hooks  
- Axios (consumo da API)  
- TailwindCSS (estilização)  

---

## 📚 Organização da Documentação

Toda a API é documentada utilizando **Swagger** e pode ser acessada através do endpoint:
GET /api-docs

O Swagger permite:
- Visualizar todos os endpoints disponíveis.
- Testar chamadas diretamente pela interface web.
- Consultar exemplos de requisição e resposta.

A documentação está estruturada por **módulos**:
1. **Campeonatos**
2. **Jogadores**
3. **Rodadas**
4. **Tabela**

