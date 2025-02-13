# Dashboard de Vendas do Supermercado

Este projeto é um dashboard interativo desenvolvido com Streamlit e Plotly para visualizar e analisar os dados de vendas de um supermercado. O objetivo é permitir uma análise detalhada do faturamento, desempenho dos produtos, formas de pagamento e avaliações das filiais.

## 📊 Funcionalidades

- **Faturamento por dia**: Exibe o total de vendas diárias segmentadas por cidade.
- **Faturamento por tipo de produto**: Analisa quais tipos de produtos tiveram maior faturamento.
- **Faturamento por filial**: Mostra a contribuição de cada unidade de negócio para o faturamento total.
- **Desempenho das formas de pagamento**: Identifica quais métodos de pagamento são mais utilizados.
- **Avaliação das filiais**: Exibe a média de avaliações recebidas por cada filial.

## 🚀 Tecnologias Utilizadas

- [Streamlit](https://streamlit.io/) - Framework para visualização de dados interativa.
- [Pandas](https://pandas.pydata.org/) - Manipulação e análise de dados.
- [Plotly](https://plotly.com/python/) - Criação de gráficos dinâmicos.

## 📂 Estrutura do Projeto

```
📂 supermarket_dashboard
 ├── supermarket_sales.csv  # Base de dados
 ├── app.py                 # Código principal do dashboard
 ├── README.md              # Documentação do projeto
```

## 📌 Como Executar o Projeto

1. Clone este repositório:
   ```bash
   git clone https://github.com/seu-usuario/supermarket-dashboard.git
   ```
2. Acesse o diretório do projeto:
   ```bash
   cd supermarket-dashboard
   ```
3. Crie um ambiente virtual e instale as dependências:
   ```bash
   python -m venv venv
   source venv/bin/activate  # No Windows: venv\Scripts\activate
   pip install -r requirements.txt
   ```
4. Execute o Streamlit:
   ```bash
   streamlit run app.py
   ```
5. Acesse no navegador o link fornecido pelo Streamlit.

## 📈 Exemplo de Uso

Ao executar o dashboard, selecione o mês desejado na barra lateral para visualizar as métricas e gráficos correspondentes.

## 📜 Licença

Este projeto está licenciado sob a [MIT License](LICENSE).

---
Desenvolvido por [Seu Nome](https://github.com/seu-usuario).

