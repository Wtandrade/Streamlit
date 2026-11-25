<div align="center">

# Projetos Streamlit

**Repositório central para experimentos, aplicações e dashboards desenvolvidos com Streamlit.**

[![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)](https://streamlit.io/)
[![GitHub](https://img.shields.io/badge/Repositório-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Wtandrade/Streamlit)
[![License](https://img.shields.io/badge/License-Em%20definição-lightgrey?style=for-the-badge)](#licença)

</div>

---

## Sobre o repositório

Este repositório reúne diversos projetos independentes construídos com **Streamlit**, uma biblioteca de Python para criação rápida de aplicações web voltadas para dados, automação e visualização.

Cada projeto possui seu próprio diretório, dependências e instruções de execução. Portanto, o repositório funciona como uma coleção/portfólio de aplicações, e não como um único projeto fechado.

## Projetos

| Projeto | Descrição |
|---------|-----------|
| [Análise de Vendas](./analise_vendas/) | Dashboard interativo de análise de vendas com filtros, indicadores e visualizações geográficas e temporais |

Novos projetos serão adicionados à medida que forem desenvolvidos e poderão receber estruturas e dependências próprias.

## Tecnologias

Os projetos deste repositório podem utilizar uma combinação das seguintes tecnologias:

- **Streamlit** para interfaces interativas em Python
- **Pandas** para manipulação e análise de dados
- **Plotly** e outras bibliotecas para visualização
- **NumPy** e bibliotecas científicas para processamento
- APIs, bancos de dados e outros serviços conforme a necessidade de cada aplicação

## Estrutura

```text
Streamlit/
├── analise_vendas/       # Projeto de dashboard de análise de vendas
│   ├── dashboard.py
│   ├── data.py
│   ├── views/
│   └── README.md
└── README.md             # Apresentação geral do repositório
```

Cada projeto pode adicionar seus próprios arquivos de configuração, dados, testes e documentação.

## Como executar um projeto

1. Clone o repositório:

```bash
git clone https://github.com/Wtandrade/Streamlit.git
cd Streamlit
```

2. Acesse o diretório do projeto desejado:

```bash
cd analise_vendas
```

3. Consulte o `README.md` específico e siga as instruções de instalação e execução daquele projeto.

## Adicionando um novo projeto

Para manter o repositório organizado, cada aplicação deve ficar em uma pasta própria na raiz do repositório e incluir:

- Código-fonte do projeto
- Arquivo `requirements.txt` ou configuração equivalente
- Arquivo `README.md` com propósito, dependências e instruções
- Dados localmente necessários ou instruções claras para obtê-los
- Arquivos de configuração ou exemplos, sem credenciais ou informações sensíveis

Também é recomendado atualizar a tabela da seção **Projetos** neste README.

## Licença

A licença deste repositório ainda não foi definida. Projetos ou códigos podem possuir regras próprias conforme forem documentados.
