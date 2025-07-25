# Tela 3: Fluxo de Adição de Alimentos

* Este é um micro-fluxo que começa no Dashboard.


### Passo A: Clicar para Adicionar (na Tela 4)
  * O usuário clica no [+] ao lado de "Almoço".
  



### Passo B: Busca de Alimentos

+-------------------------------------------+
|          Adicionar ao Almoço              |
|   +-----------------------------------+   |
|   | 🔍  Procure um alimento...        |   |
|   +-----------------------------------+   |
|                                           |
|   RECENTES                                |
|   - Arroz branco (100g)                   |
|   - Filé de frango grelhado (150g)        |
|   --------------------------------------- |
|   RESULTADOS DA BUSCA ("bata")            |
|   - Batata Doce (cozida)                  |
|   - Batata Inglesa (assada)     [>]       | <-- Item clicável
|   - Batata Frita (industrializada)        |
|                                           |
+-------------------------------------------+

Ação: Clicar em "Batata Inglesa (assada)" leva ao Passo C.





### Passo C: Detalhes e Quantidade

+-------------------------------------------+
|      <-- Voltar                           |
|      Batata Inglesa (assada)              |
|                                           |
|   Informação Nutricional (por 100g)       |
|   Calorias: 93 kcal                       |
|   Proteínas: 2.5 g                        |
|   Carboidratos: 21 g                      |
|   Gorduras: 0.1 g                         |
|   --------------------------------------- |
|   DEFINA A QUANTIDADE                     |
|                                           |
|            [    150    ] [      g      v] |  <-- Campos editáveis
|                                           |
|   [   ADICIONAR AO ALMOÇO (140 kcal)    ] |
+-------------------------------------------+

Ação: Ao clicar em "ADICIONAR", o app retorna para a Tela 4, agora com o item adicionado e as calorias atualizadas.