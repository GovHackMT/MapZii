# HotZii - Você de olho no foco

## Sobre o projeto

Sistema de Georreferenciamento para apresentação de ocorrências de casos de dengue, afim de apoiar o processo de tonada de decisão.

## Fluxo do Processo de ETL

1. Receber os dados brutos numa planilha tabulada;
2. Exportar a planilha para o formato CSV;
3. Utilizar um conversor online de CSV para JSON;
4. Executar um script (js) para interar sobre os registros e obter os dados de latitude e longitude através da API do Google Geocoding;
5. Salvar os dados no banco de dados (MongoDB);
6. Remover registros com problemas;

## Licença

MIT

## Equipe

* Felipe Fontana
* Leonardo Braun
* Marlon Ourives
* Nelson Viana
* Roger Resmini

## Tecnologias
### APIs Externas

* Google Geocoding API

### Desenvolvimento

* Implementação da API com: Node JS (4.6.1) e MongoDB
* Frontend: Twitter Bootstrap + jQuery
* Versionamento: Git (repositório Github)
* Hospedagem: Digital Ocean usando Docker Container