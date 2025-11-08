<!-- Capa animada superior -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=2F2F2F&height=120&section=header" alt="Capa animada superior" width="1000" />
</p> 



# 🏪 Projeto Alura Store - Decisão de negócio com Dados. 
Neste projeto irei ajudar o Senhor João a decidir qual loja da sua rede Alura Store vender para iniciar um novo empreendimento. Para isso, irei analisará dados de vendas, desempenho e avaliações das 4 lojas fictícias da Alura Store. O objetivo é identificar a loja com menor eficiência e apresentar uma recomendação final baseada nos dados.

O que realizei:
- Carregar e manipular dados CSV com a biblioteca Pandas;
- Criar visualizações de dados com biblioteca Matplotlib;
- Analisar métricas como faturamento, avaliações e desempenho de vendas;
- Apresentar uma recomendação.

**Descrição**

O objetivo desta análise foi identificar qual loja o Senhor João deve vender, com base em indicadores financeiros, de desempenho de vendas e de satisfação dos clientes. Foram analisados:  
- O faturamento total de cada loja;  
- As categorias de produtos mais e menos vendidas;  
- A média das avaliações dos clientes;  
- Os produtos mais e menos vendidos;  
- O frete médio por loja.  

A partir dessas informações, foi possível comparar o desempenho geral de cada unidade e recomendar aquela que apresenta os piores resultados para uma eventual venda.


**Desenvolvimento das Análises**

Faturamento Total:
- Maior faturamento: Loja 1 - R$ 1.534.509,12

- Menor faturamento: Loja 4 - R$ 1.384.497,58  

A Loja 1 apresentou o melhor desempenho financeiro, enquanto a Loja 4 teve o menor faturamento total, indicando menor volume de vendas ou ticket médio mais baixo.


**Categorias de Produtos Mais e Menos Vendidas**

| Categoria             | Loja que Mais Vendeu | Loja que Menos Vendeu |
| --------------------- | -------------------- | --------------------- |
| Brinquedos            | Loja 4 (338)         | Loja 2 (313)          |
| Eletrodomésticos      | Loja 1 (312)         | Loja 4 (254)          |
| Eletrônicos           | Loja 3 (451)         | Loja 2 (422)          |
| Esporte e Lazer       | Loja 1 (284)         | Loja 2 (275)          |
| Instrumentos Musicais | Loja 2 (224)         | Loja 4 (170)          |
| Livros                | Loja 2 (197)         | Loja 1 (173)          |
| Móveis                | Loja 3 (499)         | Loja 2 (442)          |
| Utilidades Domésticas | Loja 4 (201)         | Loja 1 (171)          |

As Lojas 1 e 3 se destacam em várias categorias com bom desempenho em eletrodomésticos, esportes e móveis.
Já a Loja 2 tem resultados medianos, mas se destaca em instrumentos musicais e livros.
A Loja 4 aparece com menor desempenho em múltiplas categorias, especialmente em eletrodomésticos e instrumentos musicais.


**Média das Avaliações dos Clientes**

- Melhor avaliada: Loja 3 — 4,04  
- Pior avaliada: Loja 1 — 3,97  

A Loja 3 se sobressai na satisfação dos clientes, com avaliações médias mais altas. Apesar do bom faturamento, a Loja 1 apresenta a pior média de avaliação.


**Produtos Mais e Menos Vendidos**
- Mais vendidos: Lojas 1, 2 e 3 — 2.359 unidades  
- Menos vendidos: Loja 4 — 2.358 unidades  

Mesmo com diferença pequena, a Loja 4 novamente aparece na última posição, reforçando o padrão de desempenho mais baixo em volume de vendas.


**Frete Médio por Loja**
- Maior frete: Loja 1 — R$ 34,60  

- Menor frete: Loja 4 — R$ 31,20  

A Loja 1 apresenta o maior custo médio de frete. Já a Loja 4 tem o menor custo logístico.


**Síntese Comparativa**

| Indicador | Melhor Desempenho | Pior Desempenho |
|------------|-------------------|-----------------|
|Faturamento | Loja 1 | Loja 4 |
| Categorias vendidas | Loja 3 | Loja 4 |
| Avaliação dos clientes | Loja 3 | Loja 1 |
| Produtos vendidos | Lojas 1, 2, 3 | Loja 4 |
| Frete médio | Loja 4 | Loja 1 |


**Conclusão e Recomendação**

Com base em todos os dados analisados, a Loja 4 apresenta o pior desempenho geral, pois:

- Possui menor faturamento total (R$ 1.384.497,58);  
- Registra menor volume de categorias e produtos vendidos;  
- Apesar de ter o menor frete médio, isso não se reflete em lucro ou competitividade;  
- Não lidera em nenhum dos indicadores positivos, mostrando resultados consistentes abaixo das demais.

 Recomenda-se que o Senhor João venda a Loja 4, por ser a unidade menos rentável e com menor potencial de crescimento, permitindo concentrar esforços e recursos nas lojas com melhor desempenho (especialmente a Loja 3, que combina boas vendas, boa avaliação e mix de produtos sólido).

**Confira o notebooks completos:**
- Arquivo: 
- Link: https://colab.research.google.com/drive/1XZ2RcDxkic45hIJcpC8D4FjDX47fYfXY?usp=sharing

**Ferramentas Utilizadas**

- Python (Pandas, Matplotlib, Folium)

- Google Colab

- Bibliotecas:
  - pandas → tratamento de dados
  - matplotlib → visualização de gráficos
  - folium → criação de mapas interativos

## 👩🏽 Sobre Mim

Sou **Larissa dos Santos Silva**, estudante do Programa ONE (Oracle + Alura).
Aqui compartilho os principais projetos que desenvolvi durante minha formação na Área de Dados.
Este projeto faz parte do meu processo de aprendizado e desenvolvimento pessoal e profissional. 

Estou super aberta para sugestôes e dicas!



### 📫 Contato

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Perfil%20Profissional-blue?style=flat-square&logo=linkedin)](https://www.linkedin.com/in/seu-perfil)  
www.linkedin.com/in/laris-santos

https://unique-onion-409.notion.site/Ol-meu-nome-Larissa-dos-Santos-1ffae8705fee800499d2fd44643ebcf5?source=copy_link

✉️ larissa.santos.silva9902@gmail.com


---

<p align="center">Feito com 🖤 por Larissa dos Santos Silva</p>

<!-- Capa animada inferior -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=2F2F2F&height=120&section=footer" alt="Capa animada inferior" width="1000" />
</p>

