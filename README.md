# APi Escola - node.js  +  Express
API RESET REST simples para gerenciar alunos e professores 

## Pré-Requisitos
-Node.js instalados

## Como Rodar

### Instalar dependências
```bash
npm :
```

### Iniciar o Servidor 
```bash
node index.js
```

### Acessar 
Abra o navegador em: `https://localhost:3000`

### Endpoints

### Alunos

| Método | Endpoints | Descrição |
|--------|-----------|-----------|
| GET | `/alunos` | Lista de todos os Alunos |
| GET | `/alunos/id:` | buscar um alunos em específico |
| POST | `/alunos` | Cria um novo Aluno |
| PUT | `/alunos/:id` | atualiza um aluno |
| DELETE | `/alunos/:id` | remove um aluno |

### Professores

| Métodos | Endpoints | Descrição |
|---------|-----------|-----------|
| GET | `/professores` | Lista de todos os professores |
| POST | `/professores` | Cria um novo professor |
| PUT | `/professores/:id` | atualiza um professor |
| DELETE | `/professores/:id` | deleta um professor |

## Tecnologias 
-Node.js
-Express

## Notas 
- Os dados são armazenados na memória (Reiniciar o servidor apaga tudo)
