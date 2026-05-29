## 🌍 React-Node-Massoterapia-Mvp

Exemplo de criação de aplicativo de agendamento de sessões de massoterapia em NodeJS e React com banco de dados Postgree. 

#### O que voçê vai ver nesse Projeto

| Node.js | Descrição |
|-----------|-----------|
| **Express JSON** | É um middleware embutido responsável por analisar (parsear) corpos de requisições HTTP recebidas que contenham dados no formato JSON.  |
|  **Express Router** | Reponsável por criar manipuladores de rotas modulares e montáveis.  |
|  **Sequelize** |  Mapeador objeto-relacional (ORM) permite que manipular dados usando objetos e métodos JavaScript, eliminando a necessidade de escrever queries SQL. |

| React | Descrição |
|-----------|-----------|
| **react-router-dom** | Biblioteca padrão React para gerenciar navegação e roteamento em aplicações web Single Page Applications, permitindo que o usuário navegue entre diferentes "telas" sem recarregar a página inteira   |
|  **moment**  | Manipulação e formatação de exibição de datas e horas, facilitando o desenvolvimento de interfaces interativas.  |
| **react-hook-form** | Simplifica a validação, coleta de dados e manipulação de estado. Sua principal competência é reduzir a necessidade de componentes controlados (useState) |
| **pdfmake**  | Biblioteca JavaScript para geração de documentos PDF |
| **react-router**  | Biblioteca padrão e mais utilizada para gerenciar navegação e roteamento em aplicações.  |
| **react-table** | Biblioteca headless poderosa para construção de tabelas altamente customizáveis. |

#### Requisitos do Projeto
- Necessários abrir duas instâncias do VSCode: 

```bash
VSCode 
|----| Backend
     |---- API Start / (http://localhost:3333/)
VSCode
|----| Frontend
     |---- App Init / (http://localhost:3000/)
```

#### Backend (Node.js)
- Recuperar as dependencias do projeto node_modules . 
```bash
npm install express
```

- Automatizar o processo de reinicialização
```bash
npm install -g nodemon
```

#### 🔄 Executar a aplicação
- Executar o Build do Projeto
```bash
nodemon index.js
ou 
node index.js
```

#### Frontend (React)
- Recuperar as dependencias do projeto node_modules .
```bash
npm install --legacy-peer-deps
```

#### 🔄 Executar a aplicação
- Executar o Build do Projeto
```bash
yarn start  
```

#### ⚠️ String de conexão do banco
- Modifique a string de conexão no arquivo **db.js**, no trecho indicado:

```bash
        const sequelize = new Sequelize('SEUBANCO', 'postgres', 'SUASENHA', {
        host: 'localhost',
        dialect: 'postgres',
        define: {
            timestamps: false,
            },
```

O script para criação da tabela do exemplo encontra-se na pasta **Database**.

#### Aqui está uma demonstração do Projeto

<img width="1316" height="607" alt="App-Massoterapeuta-Node-React" src="https://github.com/user-attachments/assets/051fda55-b9c6-46da-8d01-33012383f17e" />
