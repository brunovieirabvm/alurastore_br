```markdown
🛒 Projeto Análise de Lojas

Este projeto faz parte do **Challenge Data Science** do programa **Alura ONE G8**.
O objetivo é praticar análise exploratória de dados, visualizações com Python e apresentar insights para tomada de decisão.


📊 Análise de Vendas das Lojas

Este projeto é parte de um **desafio de Data Science** com foco em análise exploratória de dados de quatro lojas distintas.  
O objetivo é comparar o desempenho das lojas a partir de métricas como **faturamento**, **frete médio**, **avaliação de compra** e **vendas por produto e categoria**.

---

✅ Sobre o Projeto

Neste notebook/script, são realizadas:
- Importação e consolidação de múltiplos arquivos `.csv` de cada loja.
- Cálculo do **faturamento total** por loja.
- Análise de vendas por **categoria** e **produto**.
- Análise da **média de avaliação** por loja.
- Cálculo do **frete médio** por loja.
- Visualizações gráficas (barras, linhas, bolhas) para melhor compreensão dos resultados.

---

⚙️ Tecnologias Utilizadas

- Python 3
- Pandas (tratamento de dados)
- Matplotlib e Seaborn (visualizações gráficas)
- Jupyter Notebook ou Google Colab

---

📂 Estrutura do Projeto


alurastore_br/
 ├── dados/
 │   ├── loja_1.csv
 │   ├── loja_2.csv
 │   ├── loja_3.csv
 │   └── loja_4.csv
 ├── graficos/
 │   ├── faturamento_por_loja.png
 │   ├── frete_medio_por_loja.png
 │   ├── avaliacao_vs_frete_faturamento.png
 ├── alurastore_br.ipynb  # ou alurastore_br.py
 └── README.md

---

🚀 Como Executar

1️⃣ Clone o repositório
```bash
git clone https://github.com/brunovieirabvm/alurastore_br.git
cd alurastore_br
```

2️⃣ Crie um ambiente virtual (opcional)
```bash
python -m venv venv
source venv/bin/activate  # Linux/Mac
venv\Scripts\activate     # Windows
```

3️⃣ Instale as dependências
```bash
pip install pandas matplotlib seaborn
```

4️⃣ Execute
- Abra o arquivo `.ipynb` em Jupyter Notebook ou Google Colab
- Ou rode o script `.py` no terminal:
  ```bash
  alurastore_br.py
  ```

---

🔍 Principais Resultados

- Comparação de **faturamento total** entre as lojas.
- Produtos **mais vendidos** e **menos vendidos**.
- Relação entre **frete médio** e **avaliação média**.
- Visualizações claras e salvas na pasta `graficos/`.

---

⚠️ **Possíveis Problemas**

- Se algum arquivo `.csv` não for carregado, verifique o link ou o caminho local.
- Verifique se todas as bibliotecas estão instaladas (`pandas`, `seaborn`, `matplotlib`).
- Para emojis nos gráficos, pode haver **avisos de fonte**, mas não afetam os resultados.

---

🌍 Análise Geográfica

Como atividade complementar, este projeto também explorou os dados de **coordenadas geográficas** (latitude e longitude) para entender **onde as vendas estão concentradas**.

Foram criados:
- 📌 **Gráfico de Dispersão:** mostrando os pontos de vendas de cada loja em um plano cartesiano de coordenadas.
- 🔥 **Mapa de Calor (Heatmap):** destacando áreas com maior densidade de pedidos, facilitando a identificação de regiões estratégicas.

**Objetivo:**  
Verificar **padrões de concentração geográfica**, analisar como a localização influencia o **faturamento**, o **custo de frete** e a **satisfação dos clientes**, além de mostrar possíveis oportunidades para otimizar a logística de cada loja.

Essa análise reforçou a recomendação final de **venda da Loja 3**, que se mostrou **bem distribuída geograficamente**, com alcance equilibrado e bons resultados logísticos.

Os gráficos e mapas estão salvos na pasta `/graficos` e também podem ser gerados novamente executando os notebooks do projeto.

---

🙌 **Autor**

Bruno Vieira Maciel  
[Meu LinkedIn](https://www.linkedin.com/in/brunovieirabvm/) | [Meu GitHub](https://github.com/brunovieirabvm)

---

📌 **Este projeto é um exemplo de análise de dados exploratória para seleção e portfólio. Fique à vontade para clonar, usar e melhorar!**
```