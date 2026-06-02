# ciencia-de-dados
Machine Learning e Redes Neurais para segmentação de produtos e previsão de canais de venda em uma microempresa de doces.

Inteligência de Dados para Confeitaria Artesanal
Projeto usando os dados reais de produtos da minha própria empresa de doces. O objetivo principal é analisar o cardápio e usar inteligência artificial para descobrir qual é o melhor canal de venda (como iFood, Faculdade, Encomendas ou Internet) para cada tipo de doce.

O que o projeto faz?
Organiza o Cardápio (Grupos): O código analisa características dos doces (como preço, peso, margem de lucro, tempo de preparo e validade) e usa aprendizado não supervisionado (K-Means) para criar grupos de produtos parecidos.

Sugere onde vender: Se eu criar um doce novo hoje, o algoritmo analisa as características dele e me sugere em qual canal de venda ele terá mais chance de sucesso.

Mostra gráficos e padrões: O projeto cria visualizações para entender o negócio na prática, como:

A relação direta entre o peso do doce e o preço cobrado.

Gráficos em 3D para ver os produtos se separando no espaço.

Heatmaps (Mapas de calor): Gráficos que mostram a média e o desvio padrão (variância) de cada grupo, ajudando a ver se os produtos de um mesmo canal são realmente parecidos ou se variam demais.

Como funciona por trás do código?
Gráficos de Relações (Pairplot): Cruzam todas as informações para mostrar tendências (ex: se o tempo de preparo aumenta junto com o preço).

Modelos de Decisão (Random Forest e Rede Neural): Funcionam como "vendedores virtuais" treinados. Eles aprenderam o histórico da empresa e agora conseguem classificar qualquer produto novo automaticamente.

One-Hot Encoding: Uma técnica que usei para que o computador não ache que um canal de venda é "maior" ou "melhor" que o outro só por causa de um número de identificação. Todos ganham o mesmo peso na análise.

Por que isso ajuda o negócio?
Em vez de decidir onde vender um produto na base do "achismo", o projeto traz uma gestão baseada em dados reais. Isso ajuda a evitar o desperdício de ingredientes (olhando o tempo de validade) e garante que o doce certo vá para o cliente certo, aumentando o lucro.
