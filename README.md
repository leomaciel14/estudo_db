
# 🎬 Projeto CRUD de Filmes

Este é um projeto simples que conecta um **Frontend** em HTML/CSS/JS a um **Servidor Node.js** com um **Banco de Dados MySQL** para realizar operações de **CRUD** (Create, Read, Update, Delete) de filmes.

## 🚀 Funcionalidades

- **Listar filmes** armazenados no banco de dados.
- **Adicionar novos filmes** através de formulário.
- **Deletar filmes** diretamente no card.
- **(Futuro)**: Editar filmes via formulário.

---

## 🛠️ Tecnologias Utilizadas

- **Front-end:**
  - HTML5
  - CSS3
  - JavaScript Vanilla (puro)

- **Back-end:**
  - Node.js
  - Express.js
  - Cors
  - MySQL (banco de dados)

- **Banco de dados:**
  - MySQL Workbench / MariaDB
  - Tabela de filmes com colunas: `id`, `titulo`, `ano_lancamento`, `genero`

---

## 📂 Estrutura do Projeto

```bash
Projeto/
│
├── backend/         # Código Node.js com Express
│   └── server.js    # Configuração de rotas e conexão ao banco
│
├── frontend/        # Página HTML com consumo da API
│   └── index.html   # Exibe cards dos filmes e botões de ação
│
└── README.md        # Este arquivo de documentação
```

---

## 🔧 Como Rodar o Projeto Localmente

1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/seu-repositorio.git
   ```

2. Acesse a pasta do backend:
   ```bash
   cd backend
   ```

3. Instale as dependências:
   ```bash
   npm install
   ```

4. Configure a conexão do MySQL no `server.js` (usuário, senha e banco).

5. Rode o servidor Node:
   ```bash
   node server.js
   ```

6. Acesse a pasta do frontend:
   ```bash
   cd ../frontend
   ```

7. Rode um servidor local para servir o `index.html`:
   ```bash
   npx serve .
   ```

8. Acesse no navegador:
   ```
   http://localhost:porta-que-o-serve-indicar
   ```

---

## 🧠 Conceitos Aplicados

- **Fetch API** para consumo de endpoints REST.
- **Middleware CORS** para permitir comunicação entre servidores diferentes.
- **Manipulação do DOM** para criar e deletar elementos dinamicamente.
- **CRUD completo** integrando Frontend → Backend → Banco de dados.

---

## 📈 Próximos Passos (Melhorias Futuras)

- Implementar a função de **Editar Filme** via formulário modal.
- Adicionar **validação de campos** no front-end.
- Tratar melhor os erros da API.
- Melhorar o estilo dos cards usando um framework como TailwindCSS ou Bootstrap.
- Implementar paginação para muitos filmes.

---

## ✨ Screenshots

| Página Inicial |
| :---: |
| ![Página Inicial](https://i.ibb.co/tTMvFzVz/Apresenta-o.png)|


---

## 📜 Licença

Este projeto está sob a licença [MIT](LICENSE).

---

> Feito com 💻, ☕ e muito aprendizado!