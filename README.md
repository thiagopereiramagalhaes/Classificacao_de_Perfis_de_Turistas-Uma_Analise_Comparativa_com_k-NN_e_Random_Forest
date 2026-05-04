# Classificação de Perfis de Turistas

## 1. O que é este projeto?

Este projeto utiliza Inteligência Artificial (Aprendizado de Máquina) para classificar diferentes tipos de turistas com base na sua comunicação verbal e noutras características. O objetivo principal é descobrir qual modelo matemático consegue identificar com maior precisão a qual "perfil" um turista pertence.

Entender o perfil de um turista é fundamental para agências de viagens, hotéis e profissionais do turismo. Com esta informação, é possível personalizar pacotes de viagens, melhorar o atendimento ao cliente e criar campanhas de marketing mais direcionadas e eficazes. 

Para resolver este desafio, o projeto compara o desempenho de dois algoritmos populares de Inteligência Artificial:
* **k-NN (k-Vizinhos Mais Próximos):** Um modelo que classifica um novo turista comparando-o com os turistas mais parecidos (seus "vizinhos") que já existem na base de dados.
* **Random Forest (Floresta Aleatória):** Um modelo mais complexo que cria uma "floresta" de dezenas de árvores de decisão, onde cada árvore dá o seu palpite e a maioria decide o perfil final do turista.

Em resumo, este projeto resolve o problema de categorização de clientes no setor do turismo, transformando dados complexos de comunicação em informações valiosas e fáceis de interpretar, permitindo que empresas ofereçam experiências personalizadas.

## 2. Como o fiz?

O projeto foi desenvolvido de forma estruturada utilizando a linguagem de programação Python e um ambiente interativo (*Jupyter Notebook*). O processo seguiu as principais etapas e boas práticas da ciência de dados:

1. **Receção e Exploração dos Dados:** Carregámos uma base de dados contendo informações sobre a forma como diferentes turistas se comunicam. Analisámos estes dados para entender os padrões e as diferentes categorias de perfis existentes.
2. **Preparação e Limpeza:** Como os computadores lidam melhor com números, organizámos e transformámos as informações para que os modelos as pudessem compreender. Além disso, dividimos os dados em duas partes distintas: um grupo de dados para "ensinar" a Inteligência Artificial (dados de treino) e um grupo isolado para testar se ela realmente aprendeu (dados de teste).
3. **Construção dos Modelos:**
    * Construímos e treinámos o algoritmo **k-NN**, ajustando as suas configurações para encontrar o equilíbrio ideal na comparação de semelhanças entre os turistas.
    * Construímos e treinámos o algoritmo **Random Forest**, gerando múltiplas árvores de decisão para criar um sistema de classificação robusto e confiável.
4. **Comparação e Avaliação:** Colocámos os dois modelos à prova utilizando os dados de teste (que eles nunca tinham visto antes). Comparamos os resultados utilizando métricas de desempenho (como a taxa de acertos e erros) para determinar qual dos dois "adivinhava" o perfil do turista de forma mais correta e consistente.
5. **Conclusão:** Finalizámos o projeto com uma análise comparativa clara, definindo qual dos algoritmos se mostrou mais apto e preciso para ser utilizado no mundo real por empresas do setor do turismo.
