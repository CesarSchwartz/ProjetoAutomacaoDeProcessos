# ProjetoAutomacaoDeProcessos
 
 
 OBJETIVO DO PROJETO:
 
 Criar uma automação capaz de calcular indicadores de varias lojas simultaneamente tais como:(Faturamento, Diversidade de Produtos e Ticket Médio por Venda), através desses indicadores criar um e-mail personalizado para cada loja, contendo uma mensagem personalizada com "HTML"  com os indicadores da loja, e no Anexo do e-mail tem o arquivo da loja com todas as informações de vendas que foram usadas para calcular os indicadores. Ultimo passo é mandar um e-mail para a Diretoria com a melhor e a pior loja do ano e dia com base no faturamento, no Anexo do e-mail contendo dois arquivo com a ranking de todas as lojas do ano e dia com base no faturamento.
 
 BIBLIOTECAS USADAS:
 
 Pandas
 Pathlib
 Win32com
 
 ETAPAS DO PROJETO:
 
 1 Passo - Usar a biblioteca do Pandas para importar todos os arquivos que serão usados no projeto.
 
 2 Passo - Criar uma "Pasta de Backup", dentro desta pasta criar uma pasta para cada loja, com um arquivo que tem todas as informações de vendas da loja.
 
 3 Passo - Calcular os indicadores das lojas:(Faturamento, Diversidade de Produtos e Ticket Médio por Venda).
 
 4 Passo - Enviar um e-mail para cada lojas contendo as informações dos indicadores e um anexo.
 
 5 Passo - Criar um ranking com todas as lojas da melhor a pior com base no faturamento.
 
 6 Passo - Mandar um e-mail para a diretoria, contendo a informação do ranking das lojas e no anexo 2 arquivos, o primeiro referente ao ranking diario das lojas, e o outro arquivo com o ranking anual das lojas.
 

