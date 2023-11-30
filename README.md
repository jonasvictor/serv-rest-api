# Teste de API Rest👾

Criação de testes de API Rest utilizando postman, newman e newman-htmlextra

## Tecnologia utilizadas

- Postman
- node v20.9.0
- newman 6.0.0
- newman-reporter-htmlextra

## Documentações

- Análise Técnica Análise/...
- Doc da API [Consulte Swagger](https://serverest.dev/#/)

## Como instalar o ambinete

- Instale o node em seu computador [baixe aqui](https://nodejs.org/en/download)
- Realize a instalação do newman de forma global [baixe aqui a dependência](https://www.npmjs.com/package/newman)
```
npm install -g newman
```
- Realize a instalação da dependência dos relatórios (opicional) [newman-reporter-htmlextra](https://www.npmjs.com/package/newman-reporter-htmlextra)
```
npm install -g newman-reporter-htmlextra
```
## Como rodar os testes

### Pelo Postman web ou desktop

- Import a collection e o environment
- Execute os testes de forma manual ou automatizada

### Pelo newman

- Abra o console de preferência
- Execute a seguinte linha de comando para rodar os testes
```
newman run ServeRest.postman_collection.json -e serveRest_env.postman_environment.json -r cli
```
- Execute os testes com relatório
```
newman run ServeRest.postman_collection.json -e serveRest_env.postman_environment.json -r cli,htmlextra
```

## Report

Se você optou por rodar os testes com o report htmlextra, você gerou um arquivo HTML com o resultado dos testes. Para verificar as validações, você pode abrir a pasta **newman** que foi criada no local onde os arquivos de collection e environment se encontram.

## Entrar em contato

- Email: jonas.victor@dcx.ufpb.br
- Linkedin: [Jonas Victor](https://www.linkedin.com/in/jonas-victor/)
