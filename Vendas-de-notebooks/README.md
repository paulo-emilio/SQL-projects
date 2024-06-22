## Análise de Fatores que Afetam os Preços de Notebooks

### Visão Geral
Este projeto tem como objetivo analisar os fatores que afetam os preços dos computadores portáteis utilizando a plataforma Databricks e SQL. A análise inclui aspectos como marca, tipo de memória, processador, presença de touchscreen, entre outros. Os dados foram obtidos do Kaggle, mais especificamente do conjunto de dados "Lista de Preços de Laptops".


[![](vendasnotebooks.gif)](https://thunder-root-duchess.glitch.me/)

**Link para o projeto:** [databricks](https://thunder-root-duchess.glitch.me/)


### Conjunto de Dados
Os dados utilizados neste projeto incluem informações detalhadas sobre diversos modelos de laptops, abrangendo preços, marcas, tipos de memória, processadores, presença de touchscreen, e outros componentes e características.

### Análises Realizadas

- A primeira análise focou na média de preços das marcas, revelando que Alienware tem um preço significativamente mais alto em comparação com outras marcas, seguida pela Apple. Em contrapartida, Iball se destacou como a marca com a média de preço mais baixa, enquanto a Samsung, apesar de ser uma marca bem conhecida, foi identificada como a segunda mais barata.

- Em seguida, analisamos a participação dos diferentes tipos de memória (DDR3, DDR4, DDR5) nos preços dos laptops. Observamos que os preços variam em cerca de 2000 unidades monetárias entre os diferentes tipos de memória, com DDR4 se destacando por gerar a maior receita, possivelmente devido à necessidade de componentes de melhor qualidade.

- A análise dos preços médios por marca de processador mostrou que os processadores M1 têm uma média de preços que é o dobro dos processadores Intel e AMD, que estão na mesma faixa de preço. Isso indica que os laptops com processadores M1 são consideravelmente mais caros.

- Ao examinar a presença ou ausência de touchscreen, identificamos que a diferença média de preços entre laptops com e sem touchscreen é de aproximadamente 1100 unidades monetárias. Isso sugere que a presença de uma tela touch não é um fator extremamente caro.

- Por fim, analisamos a participação dos processadores Intel Core (i3, i5, i7, i9). Constatamos que os preços dos laptops com processadores i9 são significativamente mais altos, enquanto os preços dos laptops com processadores i3, i5 e i7 aumentam proporcionalmente conforme a performance melhora.

### Ferramentas e Técnicas Utilizadas
- **Databricks:** Plataforma utilizada para análise de dados e execução de consultas SQL.
- **SQL:** Linguagem utilizada para realizar a análise descritiva e consultas nos dados.

### Conclusão
Este projeto proporciona uma análise detalhada de vários fatores que influenciam os preços dos computadores portáteis. Através das análises realizadas, é possível entender como a marca, tipo de memória, processador e presença de touchscreen afetam os preços. Esses insights são valiosos para consumidores, fabricantes e revendedores na tomada de decisões informadas sobre a compra e venda de laptops.
