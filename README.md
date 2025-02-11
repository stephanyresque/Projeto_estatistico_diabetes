# Análise estatística de uma base de dados sobre diabetes

No projeto, utilizei ferramentas estatísticas para explorar e analisar uma base de dados sobre diabetes, com o objetivo de identificar padrões e insights relevantes relacionados à condição. O trabalho foi dividido em três etapas principais: exploração dos dados, testes estatísticos, modelagem e visualização.

## Organização do projeto

```
├── .gitignore         <- Arquivos e diretórios a serem ignorados pelo Git
├── ambiente.yml       <- O arquivo de requisitos para reproduzir o ambiente de análise
├── LICENSE            <- Licença de código aberto (MIT)
├── README.md          <- README principal para desenvolvedores que usam este projeto.
|
├── dados              <- Arquivos de dados para o projeto.
|
|
├── notebooks          <- Cadernos Jupyter.
│
|   └──src             <- Código-fonte para uso neste projeto.
|      │
|      ├── __init__.py  <- Torna um módulo Python
|      ├── config.py    <- Configurações básicas do projeto
|      └── auxiliares.py  <- Scripts para criar visualizações exploratórias e orientadas a resultados
|
├── referencias        <- Dicionários de dados.
|
├── relatorios         
│   └── imagens        
```

## Configuração do ambiente

1. Faça o clone do repositório que será criado a partir deste modelo.

    ```bash
    git clone ENDERECO_DO_REPOSITORIO
    ```

2. Crie um ambiente virtual para o seu projeto utilizando o gerenciador de ambientes de sua preferência.

    a. Caso esteja utilizando o `conda`, exporte as dependências do ambiente para o arquivo `ambiente.yml`:

      ```bash
      conda env export > ambiente.yml
      ```

## Um pouco mais sobre a base

[Clique aqui](referencias/01_dicionario_de_dados.md) para visualizar um dicionário de dados da base utilizada
