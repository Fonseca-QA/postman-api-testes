# Environments

Esta pasta contém os environments (ambientes) utilizados nos testes de API com Postman.

##  Arquivos Disponíveis

### `contactList.environment.json`
Environment principal utilizado durante os testes do curso Postman Essential Training.

##  Como Usar

### No Postman:
1. Clique no ícone de engrenagem no canto superior direito
2. Selecione "Import"
3. Escolha o arquivo `contactList.environments.json`
4. Ative o environment no dropdown superior direito

### Com Newman:
```bash
newman run ../collections/contactList.environment.json \
  -e testing-environment.postman_environment.json
