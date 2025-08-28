#  Testes de API com Postman

Projeto de testes automatizados desenvolvido durante o curso **Postman Essential Training** da LinkedIn Learning.

##  Sobre o Projeto

Aprendi e pratiquei testes de API criando testes diferentes para uma API de contatos. O projeto inclui testes básicos (quando tudo funciona) e testes negativos (quando algo dá errado).

##  Tecnologias Aprendidas

- **Postman** - Para criar e executar testes de API
- **Newman** - Para rodar os testes no terminal
- **JavaScript** - Para escrever validações nos testes
- **JSON** - Para trabalhar com dados das APIs

##  O que tem no projeto

```
📁 collections/        → Arquivos dos testes do Postman
📁 environments/       → Configurações de ambiente
📁 Imagens/        → Prints dos testes funcionando
```

##  Testes que Implementei

### ✅ Testes Básicos 
- Login de usuário
- Listar todos os contatos
- Criar novo contato
- Buscar um contato específico
- Atualizar dados do contato
- Deletar contato

### ❌ Testes Negativos 
- Tentar acessar sem login → deve dar erro 401
- Buscar contato que não existe → deve dar erro 404
- Criar contato com data inválida → deve dar erro 400
- Criar contato sem campos obrigatórios → deve dar erro 400
- Tentar atualizar com email inválido → deve dar erro 400



##  Como Executar

1. **Baixar o Newman:**
```bash
npm install -g newman
```

2. **Rodar os testes:**
```bash
 newman run contactList.collection.json -e contactList.environment.json

```

3. **Ver no Postman:**
- Importar os arquivos da pasta `collections/`
- Configurar o environment
- Executar os testes

## 📸 Imagens

As imagens na pasta `Imagens/` mostram:
- Como organizei os testes no Postman
- Exemplos de testes funcionando
- Resultados da automação com Newman



---
