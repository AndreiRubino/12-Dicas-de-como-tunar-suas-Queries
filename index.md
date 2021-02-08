# 12 Dicas de como tunar suas Queries

Este é o segundo artigo [Leia aqui o primeiro](https://andreirubino.github.io/16-Dicas-de-como-tunar-suas-Queries/)
com algumas dicas de como tunar suas Queries. As dicas abaixo não garantem por si só um melhor desempenho, cada query deve ser analisada a parte com base na sua necessidade.

-	Atenção em Queries que utilizam views pois o problema pode estar na view.
-	Evite utilizar o ORDER BY no banco e procure fazer a ordenação na aplicação. 
-	Utilize Sequence com Cache.
-	Utilize a cláusula WITH em queries recursivas.
-	Utilize UNION ALL em vez de UNION sempre que possível.
-	Utilize Queries Hierárquicas em casos de auto relacionamento.
-	Utilize variáveis BIND para queries que alterem somente o valor do parâmetro no where.
-	Utilize o MERGE quando for preciso Inserir/Atualizar dados comparando dados de uma tabela ou instrução.
-	Utilize o Index Oracle Text para busca em grandes textos. 
-	Evite o Index Bitmap em colunas com alta cardinalidade.
-	Utilize o SQL Loader para importações de grandes arquivos de dados.
-	Utilize BULK COLLECT e BULK BINDING para operações em massa.
