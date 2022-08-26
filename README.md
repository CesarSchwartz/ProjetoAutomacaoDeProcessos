# ProjetoAutomacaoDeProcessos

 INTRODUÇÃO:
 
 Imagine que você trabalha em uma grande rede de lojas de roupa com 25 lojas espalhadas por todo o Brasil.
Todo dia, pela manhã, a equipe de análise de dados calcula os chamados One Pages e envia para o gerente de cada loja o OnePage da sua loja, bem como todas as          informações usadas no cálculo dos indicadores.
Um One Page é um resumo muito simples e direto ao ponto, usado pela equipe de gerência de loja para saber os principais indicadores de cada loja e permitir em 1        página (daí o nome OnePage) tanto a comparação entre diferentes lojas, quanto quais indicadores aquela loja conseguiu cumprir naquele dia ou não.
 
 
 OBJETIVO DO PROJETO:
 
 Criar uma automação capaz de calcular indicadores de varias lojas simultaneamente tais como:(Faturamento, Diversidade de Produtos e Ticket Médio por Venda), através  desses indicadores criar um e-mail personalizado para cada loja, contendo uma mensagem personalizada com "HTML"  com os indicadores da loja, e no Anexo do e-mail tem o arquivo da loja com todas as informações de vendas que foram usadas para calcular os indicadores. Ultimo passo é mandar um e-mail para a Diretoria com a melhor e a pior loja do ano e dia com base no faturamento, no Anexo do e-mail contendo dois arquivo com a ranking de todas as lojas do ano e dia com base no faturamento.
 
 
 BIBLIOTECAS USADAS:
 
 Pandas
 Pathlib
 Win32com
 
 
 ETAPAS DO PROJETO:
 
 1 ETAPA - Usar a biblioteca do Pandas para importar todos os arquivos que serão usados no projeto.
 
 2 ETAPA - Criar uma "Pasta de Backup", dentro desta pasta criar uma pasta para cada loja, com um arquivo que tem todas as informações de vendas da loja.
 
 3 ETAPA - Calcular os indicadores das lojas:(Faturamento, Diversidade de Produtos e Ticket Médio por Venda).
 
 4 ETAPA - Enviar um e-mail para cada lojas contendo as informações dos indicadores e um anexo.
 
 5 ETAPA - Criar um ranking com todas as lojas da melhor a pior com base no faturamento.
 
 6 ETAPA - Mandar um e-mail para a diretoria, contendo a informação do ranking das lojas e no anexo 2 arquivos, o primeiro referente ao ranking diario das lojas, e o outro arquivo com o ranking anual das lojas.
 

