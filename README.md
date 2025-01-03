# WeatherApp

Este projeto foi gerado com [Angular CLI](https://github.com/angular/angular-cli) versão 16.2.15.

## Servidor de Desenvolvimento

Execute `ng serve` para iniciar um servidor de desenvolvimento. Navegue até `http://localhost:4200/`. A aplicação será recarregada automaticamente se você alterar qualquer um dos arquivos de origem.

## Estrutura do Projeto

- **src/app/modules/weather/components**: Contém os componentes da aplicação.
- **src/app/services**: Contém os serviços da aplicação.
- **src/app/models**: Contém os modelos e interfaces da aplicação.

## Chamadas de API

A aplicação faz chamadas para uma API de clima para obter dados meteorológicos. Certifique-se de configurar a URL da API e a chave de API no serviço de clima (`weather.service.ts`).

## Scaffold de Código

Execute `ng generate component component-name` para gerar um novo componente. Você também pode usar `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Execute `ng build` para compilar o projeto. Os artefatos de build serão armazenados no diretório `dist/`.

## Testes

### Testes Unitários

Execute `ng test` para executar os testes unitários via [Karma](https://karma-runner.github.io).

### Testes End-to-End

Execute `ng e2e` para executar os testes end-to-end via [Protractor](http://www.protractortest.org/).

## Contribuição

1. Faça um fork do projeto.
2. Crie uma branch para sua feature (`git checkout -b feature/nova-feature`).
3. Commit suas mudanças (`git commit -am 'Adiciona nova feature'`).
4. Faça um push para a branch (`git push origin feature/nova-feature`).
5. Abra um Pull Request.
