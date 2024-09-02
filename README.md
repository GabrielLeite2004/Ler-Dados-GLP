# Sistema de Manipulação de Dados GLP em C

## Descrição
Este repositório contém um sistema em C para manipulação e análise de dados de GLP (Gás Liquefeito de Petróleo). O projeto inclui a leitura de arquivos CSV, o processamento desses dados, e a persistência em estruturas de dados dinâmicas como listas encadeadas. O código foi estruturado para ser facilmente compilado e executado em diferentes ambientes.

## Estrutura dos Arquivos

- **main.c**: Contém a função principal do programa, responsável por coordenar a leitura dos dados, o processamento e a interação com o usuário.
- **Makefile**: Automação do processo de compilação do projeto, facilitando a geração do executável.
- **replit.nix**: Arquivo de configuração para o ambiente de desenvolvimento no Replit, especificando as dependências e configurações necessárias.
- **tad_lst2.h**: Cabeçalho que define e implementa as funções relacionadas à manipulação de listas encadeadas, utilizadas para armazenar os dados lidos do arquivo CSV.
- **glp-2004-01.csv**: Arquivo CSV contendo os dados de GLP, que serão lidos e processados pelo sistema.
- **main**: Arquivo binário resultante da compilação do código em `main.c`.

## Como Usar

### Compilação

1. Para compilar o projeto, utilize o `Makefile` incluído. Na linha de comando, execute:
   ```bash
   make
   ```
   Isso gerará o executável principal a partir do código fonte em `main.c`.

### Execução

2. Após a compilação, execute o programa gerado:
   ```bash
   ./main
   ```
   O programa irá ler os dados do arquivo `glp-2004-01.csv` e processá-los conforme as funções implementadas.

### Estrutura de Dados Utilizada

O projeto utiliza uma lista encadeada para armazenar os registros lidos do arquivo CSV. As operações básicas sobre a lista (inserção, remoção, busca, etc.) são implementadas no arquivo `tad_lst2.h`.

### Arquivo de Dados

- **glp-2004-01.csv**: Este arquivo contém dados históricos sobre o GLP que são processados pelo sistema. O formato do arquivo é delimitado por ponto e vírgula (`;`).

## Ambiente de Desenvolvimento

O arquivo `replit.nix` está incluído para facilitar a configuração do ambiente de desenvolvimento em plataformas como o Replit. Ele especifica as dependências necessárias para compilar e executar o projeto.

## Contribuições

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou enviar pull requests para melhorias no código, correções de bugs ou novas funcionalidades.

## Licença

Este projeto está licenciado sob a [MIT License](LICENSE).

```

Este README fornece uma visão geral do propósito do repositório, a estrutura dos arquivos, como compilar e executar o projeto, e outros detalhes relevantes. Se precisar de ajustes ou mais alguma coisa, estou à disposição!
