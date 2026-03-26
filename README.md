📊 Segmentação de Clientes: Projeto Mall Customers
📌 Visão Geral
Este projeto utiliza o algoritmo K-Means para identificar perfis de consumo em uma base de clientes de um shopping. O objetivo é transformar dados brutos em segmentos estratégicos, permitindo entender melhor quem são os consumidores e como eles se comportam financeiramente.
📂 Estrutura dos Dados
Trabalhamos com o dataset Mall_Customers.csv, focando em três pilares:
Idade: Recorte demográfico.
Renda Anual (k$): Capacidade financeira.
Pontuação de Gastos (1-100): Comportamento real de compra.
Nota: O ID do cliente foi removido por ser apenas um identificador sem valor estatístico.
🛠️ Preparação e Modelagem
Para garantir a precisão do algoritmo, os dados passaram por uma padronização (StandardScaler), equilibrando as diferentes escalas de renda e idade.
A definição do modelo final utilizou os métodos de Cotovelo e Silhouette Score, que apontaram o número ideal de 6 clusters (k=6). Essa configuração garantiu grupos bem separados e com interpretações lógicas.
📈 Resultados Obtidos
O modelo mapeou seis perfis distintos, destacando-se:
Clientes Premium: Alta renda e alto gasto.
Potencial de Ativação: Alta renda, mas baixo gasto atual.
Perfil Impulsivo: Baixa renda com alto índice de despesa.
Conservadores: Baixa renda e baixo gasto.
Segmentos Intermediários: Grupos de classe média definidos pela faixa etária.
🚀 Conclusão e Próximos Passos
O projeto prova que a base possui uma estrutura natural para segmentação, gerando grupos economicamente relevantes. Como evolução, planeja-se incluir a variável de gênero e criar visualizações 2D para facilitar a tomada de decisão estratégica.
