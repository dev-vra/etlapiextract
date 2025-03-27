# etlapiextract

Um projeto ETL (Extract, Transform, Load) desenvolvido em Python para extrair, transformar e carregar dados de APIs.

## Descrição

Este projeto é uma ferramenta ETL que utiliza a biblioteca `requests` do Python para realizar operações de extração de dados de APIs, transformação dos dados e carregamento em um destino específico.

## Requisitos

- Python 3.8+
- pip (gerenciador de pacotes Python)

## Instalação

1. Clone o repositório:
```bash
git clone https://github.com/seu-usuario/etlapiextract.git
cd etlapiextract
```

2. Instale as dependências:
```bash
pip install -r requirements.txt
```

## Estrutura do Projeto

```
etlapiextract/
├── src/
│   ├── extract.py
│   ├── transform.py
│   └── load.py
├── config/
│   └── config.py
├── requirements.txt
└── README.md
```

## Como Usar

1. Configure as credenciais e parâmetros necessários no arquivo `config/config.py`
2. Execute o script principal:
```bash
python src/main.py
```

## Funcionalidades

- Extração de dados de APIs REST
- Transformação de dados em formato adequado
- Carregamento dos dados processados
- Logging de operações
- Tratamento de erros

## Contribuição

Contribuições são bem-vindas! Por favor, sinta-se à vontade para submeter pull requests.

## Licença

Este projeto está licenciado sob a licença MIT - veja o arquivo [LICENSE](LICENSE) para detalhes.
