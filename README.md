# Scraping-AL-MS
Web scraping legislative propositions from Assembleia Legislativa de Mato Grosso do Sul
O site onde constam as proposições gera uma tabela na qual cada linha contém algumas informações básicas de cada proposição e um link para o usuário clicar, levando-o a outra página, que por sua vez tem mais detalhes daquela proposição.
Além disso, no site de busca é possível filtrar por categorias (educação, saúde etc.).
Sendo assim, a estratégia de raspagem foi: 
1°) Selecionar a primeira categoria e fazer a busca;
2°) Raspar os links resultantes dessa primeira busca;
3°) Selecionar a segunda categoria, fazer a busca, salvar os links. Repetir até raspar todos os links, de todas as categorias;
Essa primeira etapa tem um script próprio.
Em seguida, com outro script, o programa percorre a lista de links das proposições, acessa o sistema por meio delas e raspa os dados.
