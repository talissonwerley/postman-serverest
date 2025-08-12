# Postman-Serverest

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)

Coleção Postman completa para testar a API Serverest (Serve REST), uma API RESTful para prática de testes automatizados.

## 📌 Sobre o Projeto

Este repositório contém uma coleção Postman bem documentada para testar todos os endpoints da API Serverest, incluindo:

- Autenticação
- Usuários
- Produtos
- Carrinhos

Os testes foram projetados para validar tanto o comportamento esperado quanto casos de erro, garantindo uma cobertura abrangente da API.

## 🚀 Começando

### Pré-requisitos

- [Postman](https://www.postman.com/downloads/) instalado
- Ou [Newman](https://github.com/postmanlabs/newman) para execução via CLI
- Node.js (opcional, para scripts adicionais)

### Instalação

1.  #### Clone este repositório:

    git clone https://github.com/talissonwerley/postman-serverest.git

    Importe a coleção e o ambiente no Postman:

         Abra o Postman

         Clique em "Import" e selecione os arquivos Serverest.postman_collection.json e Serverest.postman_environment.json

    Configure as variáveis de ambiente conforme necessário

## 🧪Executando os Testes

### No Postman

- Selecione o ambiente "Serverest"

- Abra a coleção "Serverest"

- Clique em "Run Collection" para executar todos os testes

### Via Newman (CLI)

```
npm install -g newman

newman run Serverest.postman_collection.json

Serverest.postman_environment.json
```

## 📊 Relatórios

Para gerar relatórios HTML com Newman:

`newman run Serverest.postman_collection.json -e Serverest.postman_environment.json -r htmlextra`

O relatório será gerado no diretório newman/.

## 📝 Licença

Distribuído sob a licença MIT. Veja LICENSE para mais informações.
✉️ Contato

Talisson Werley - http://www.linkedin.com/in/talissonwerley

Link do Projeto: https://github.com/talissonwerley/postman-serverest
