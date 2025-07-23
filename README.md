---

# AluraStore — Análise de Dados das Lojas do Sr. João

Projeto de Data Science para análise dos dados das quatro lojas do Sr. João, com o objetivo de orientá-lo na decisão sobre qual loja vender. Através da análise exploratória dos dados, buscamos entender o desempenho de cada loja em faturamento, avaliações, categorias mais vendidas e outros insights relevantes ao negócio.

---

## Sumário

- [Sobre o Projeto](#sobre-o-projeto)
- [Como Executar](#como-executar)
- [Estrutura dos Dados](#estrutura-dos-dados)
- [Principais Resultados](#principais-resultados)
- [Ferramentas Utilizadas](#ferramentas-utilizadas)
- [Contribuição](#contribuição)
- [Licença](#licença)

---

## Sobre o Projeto

O Sr. João possui quatro lojas de varejo e precisa decidir qual delas vender. Este projeto faz uma análise dos dados de vendas, produtos, categorias, avaliações de clientes, métodos de pagamento e outros fatores de cada loja para apoiar essa decisão de forma embasada.

Principais análises realizadas:
- Faturamento total de cada loja
- Vendas por categoria de produto
- Média das avaliações dos clientes
- Produtos mais e menos vendidos
- Visualização gráfica dos principais indicadores

---

## Como Executar

1. **Clone o repositório:**
   ```bash
   git clone https://github.com/linomar31/AluraStore.git
   cd AluraStore
   ```

2. **(Opcional) Crie um ambiente virtual:**
   ```bash
   python -m venv venv
   source venv/bin/activate  # Linux/Mac
   venv\Scripts\activate     # Windows
   ```

3. **Instale as dependências:**
   ```bash
   pip install -r requirements.txt
   # ou instale manualmente: pandas, matplotlib, jupyter, etc.
   ```

4. **Execute o notebook:**
   - No Jupyter Notebook local:
     ```bash
     jupyter notebook
     ```
     E abra o arquivo `AluraStoreBr.ipynb`
   - Ou diretamente no Google Colab:  
     [![Abrir no Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/linomar31/AluraStore/blob/main/AluraStoreBr.ipynb)

---

## Estrutura dos Dados

Cada arquivo CSV contém as seguintes colunas principais:
- **Produto**
- **Categoria do Produto**
- **Preço**
- **Frete**
- **Data da Compra**
- **Vendedor**
- **Local da compra**
- **Avaliação da compra**
- **Tipo de pagamento**
- **Quantidade de parcelas**
- **Latitude (lat) e Longitude (lon)**

---

## Principais Resultados

- **Faturamento Total:** Apresentado para cada loja, acompanhado de gráficos comparativos.
- **Análise por Categoria:** Quais categorias mais vendem em cada loja.
- **Média de Avaliação:** Indicador de satisfação dos clientes por loja.
- **Produtos em Destaque:** Top 5 mais e menos vendidos em cada loja.
- **Visualizações:** Gráficos de barras, linhas, dispersão e pizza para melhor compreensão dos dados.

<sub>Inclua imagens/gráficos se desejar.</sub>

---

## Ferramentas Utilizadas

- Python
- Jupyter Notebook
- Pandas
- Matplotlib

---

## Contribuição

Contribuições são bem-vindas! Para contribuir:
1. Fork este repositório
2. Crie uma branch (`git checkout -b feature/sua-feature`)
3. Commit suas alterações (`git commit -m 'feat: nova feature'`)
4. Push para o branch (`git push origin feature/sua-feature`)
5. Abra um Pull Request

---

## Licença

Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

---
