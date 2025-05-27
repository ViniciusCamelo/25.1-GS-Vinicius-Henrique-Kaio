# 25.1-GS-Vinicius-Henrique-Kaio

1ª parte 
Entrada de Dados
Nesta etapa do projeto, foi implementado um sistema de entrada de dados interativo no qual o usuário informa a quantidade de desastres registrados. Para cada desastre, o programa solicita uma série de informações e armazena tudo em listas organizadas.
As informações coletadas incluem:
Tipo de desastre (ex: incêndio, enchente, etc.)
País, cidade, bairro e rua onde ocorreu o desastre
Quantidade total de pessoas afetadas
Detalhamento do número de pessoas afetadas por categoria:
Crianças
Adultos
Idosos
Pessoas com mobilidade reduzida
Feridos
Essa estrutura facilita a coleta de dados padronizados para futuras análises ou geração de relatórios.

2ª parte 
Armazenamento em Listas
Para organizar e manipular os dados de forma eficiente, foram utilizadas listas separadas para cada tipo de informação:
Informações do desastre:
tipo_desastres, países, cidades, bairros, ruas, total_afetados
Categorias de pessoas afetadas:
crianças, adultos, idosos, mobilidade_reduzida, feridos
Essa estrutura facilita o acesso e o processamento das informações para análises posteriores.
 
Análise de Dados
Após o preenchimento das listas, foram realizadas diversas análises para extrair informações relevantes:
Exibição do total de desastres registrados
Cálculo do total geral de pessoas afetadas
Soma do total de pessoas afetadas em cada categoria
Identificação da categoria mais afetada no geral
Localização do desastre mais grave, ou seja, aquele com o maior número de pessoas afetadas (informando rua, bairro, cidade e país)
 
Relatório de Resultados
Ao final da execução, o programa gera um relatório consolidado com:
Quantidade total de desastres registrados
Total de pessoas afetadas em cada categoria:
Categoria mais afetada
Total geral de pessoas afetadas
Local completo do desastre mais grave (rua, bairro, cidade, país)
