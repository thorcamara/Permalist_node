# Permalist_node
<br>
<br>
[ENG] Permalist application using Node, EJS and SQL.
<br>
<br>
• Instructions
<br>
<br>
<b>1.</b> Go to pgAdmin, create a new Database called 'permalist' and create a table by typing in the Query:
<br>
<br>

```
CREATE TABLE items (
  id SERIAL PRIMARY KEY,
  title VARCHAR(100) NOT NULL
);

INSERT INTO items (title) VALUES ('Buy milk'), ('Finish homework');
```
<br>
<b>2.</b> Go to the terminal and type the following command to enter the folder directory:
<br>
<br>

```
cd (Project Folder Path)
```
<br>
<br>
<b>2.</b> To install the required packages, type:
<br>
<br>

```
npm i
```
<br>
<br>
<b>3.</b> Run the project by using:
<br>
<br>

```
node index.js
```
<br>
<br>
<b>4.</b> Finally, type in your browser:
<br>
<br>

```
http://localhost:3000
```
<br>
<hr>
<br>
[PT-BR] Aplicativo de Tarefas usando Node, EJS e SQL.
<br>
<br>
<br>
• Instruções
<br>
<br>
<br>
<b>1.</b> Vá para o pgAdmin, crie um novo banco de dados chamado 'permalist' e crie uma tabela digitando na Query:
<br>
<br>

```
CREATE TABLE items (
  id SERIAL PRIMARY KEY,
  title VARCHAR(100) NOT NULL
);

INSERT INTO items (title) VALUES ('Buy milk'), ('Finish homework');
```
<br>
<b>2.</b> Vá para o terminal e digite o seguinte comando para entrar no diretório da pasta:
<br>
<br>

```
cd (Caminho da pasta do projeto)
```
<br>
<br>
<b>2.</b> Para instalar os pacotes necessários, digite:
<br>
<br>

```
npm i
```
<br>
<br>
<b>3.</b> Execute o projeto usando:
<br>
<br>

```
node index.js
```
<br>
<br>
<b>4.</b> Finalmente, digite no seu navegador:
<br>
<br>

```
http://localhost:3000
```
