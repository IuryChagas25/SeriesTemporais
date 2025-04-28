# Análise Hidrológica - Séries Temporais

Este projeto tem como objetivo a análise de dados hidrológicos obtidos de três pontos de monitoramento, contendo registros históricos de precipitação (chuva) e vazão. A análise visa apoiar o desenvolvimento de soluções em Inteligência Artificial, focadas em modelagem preditiva e previsão do comportamento hidrológico.

---

## Descrição do Problema

Temos um conjunto de dados contendo as seguintes séries temporais:

- Chuva no Ponto A (precipitação registrada em um determinado local da bacia hidrográfica);
- Vazão no Ponto A (vazão observada no rio neste mesmo ponto);
- Vazão no Ponto B;
- Vazão no Ponto C.

**Desafio:**  
Propor uma metodologia para prever a **vazão no ponto A** com até **15 dias de antecedência**.

---

## Recomendações e Orientações

- Instale a extensão **Jupyter** no **VSCode** para abrir e executar o notebook `Case_Tecnico.ipynb`.
- Utilize o **Python 3.9.7**: [Download Python 3.9.7](https://www.python.org/downloads/release/python-397/).
- No notebook, encontram-se instruções detalhadas para a instalação do ambiente de execução, garantindo a correta instalação das dependências.

---

## Instalação do Ambiente Python

1. Crie um ambiente virtual para este projeto:

   ```bash
   python -m venv nome_do_ambiente
   ```

2. Copie o arquivo `requirements.txt` para o diretório do ambiente e, utilizando o terminal (cmd) com o ambiente ativado, execute:

   ```bash
   pip install -r requirements.txt
   ```



