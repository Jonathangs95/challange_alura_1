
# Alura Store Brasil – Análise de Lojas

Projeto de análise de dados das lojas da **Alura Store Brasil**, desenvolvido a partir do desafio *Alura Challenge Data Science – E-commerce*. O objetivo é entender o desempenho das quatro lojas do Sr. João em relação a faturamento, avaliação dos clientes, categorias de produtos, frete e meios de pagamento.

---

## 📂 Estrutura do Projeto

O projeto está concentrado no arquivo:

- `alurastorebrasil.py`  
  Script principal com toda a análise exploratória e geração de gráficos.

Os dados são carregados diretamente de arquivos CSV hospedados no GitHub oficial do challenge:

- `loja_1.csv`  
- `loja_2.csv`  
- `loja_3.csv`  
- `loja_4.csv`  

---

## 🧰 Tecnologias Utilizadas

- **Python**
- **Pandas** – tratamento e agregação dos dados
- **Matplotlib** – criação de gráficos e visualizações

---

## 📊 Principais Análises Realizadas

1. **Faturamento por Loja**  
   Cálculo do faturamento total (soma da coluna `Preço`) para cada uma das quatro lojas.  

2. **Vendas por Categoria de Produto**  
   Agrupamento por `Categoria do Produto`, obtendo:  
   - Quantidade de produtos vendidos  
   - Faturamento por categoria  
   para cada loja.  

3. **Média de Avaliação das Lojas**  
   Cálculo da média da coluna `Avaliação da compra` para cada loja, permitindo comparar a satisfação dos clientes entre as unidades.  

4. **Produtos Mais Vendidos por Loja**  
   Identificação do produto mais vendido em cada loja e criação de um gráfico de barras horizontais comparando o volume de vendas por produto-chave.

5. **Análise de Formas de Pagamento**  
   Para cada loja, é feita a análise por `Tipo de pagamento`, calculando:  
   - Quantidade de vendas por tipo  
   - Média de parcelas nas compras a prazo  

6. **Relatório Final e Recomendação de Negócio**  
   Com base nas análises, é elaborado um relatório final indicando qual loja o Sr. João deveria vender, considerando:  
   - Faturamento total de cada loja  
   - Participação de cada loja no faturamento total  
   - Avaliação dos clientes  
   - Perfil de pagamento (à vista x parcelado)  

---

## 📝 Principais Insights de Negócio

- A **Loja 4** apresenta o **menor faturamento**, com aproximadamente **R$ 1.384.497,58**, representando cerca de **23,6%** do faturamento total do Sr. João.  
- Mesmo possuindo indicadores interessantes em formas de pagamento (como bom volume de pagamento à vista e média menor de parcelas), a Loja 4 segue como a unidade menos lucrativa.  
- A recomendação final do projeto é que o Sr. João considere **vender a Loja 4**, dado seu desempenho abaixo das demais lojas em termos de faturamento.

---

## 🚀 Como Executar o Projeto

1. **Clonar o repositório**

```bash
git clone https://github.com/seu-usuario/alurastorebrasil.git
cd alurastorebrasil
```

2. **Criar e ativar um ambiente virtual (opcional, mas recomendado)**

```bash
python -m venv venv
venv\Scripts\activate  # Windows
# ou
source venv/bin/activate  # Linux/Mac
```

3. **Instalar as dependências**

```bash
pip install -r requirements.txt
```

*(Caso não tenha um `requirements.txt`, você pode instalar manualmente:)*

```bash
pip install pandas matplotlib
```

4. **Executar o script**

```bash
python alurastorebrasil.py
```

O script irá:  

- Carregar os dados das quatro lojas via URL  
- Realizar os cálculos de faturamento, vendas por categoria, avaliação e tipos de pagamento  
- Exibir os principais resultados no terminal e gráficos com Matplotlib  


---

## 📄 Licença

Este projeto foi desenvolvido para fins de estudo com base no *Alura Challenge Data Science*.  
Sinta-se à vontade para usar, adaptar e evoluir o código para seus próprios estudos.
