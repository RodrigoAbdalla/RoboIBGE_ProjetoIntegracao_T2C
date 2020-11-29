Robo IBGE (Projeto de Integracao T2C)

*** OBS: A parte do banco de dados do projeto foi retirado para preservar os dados da empresa T2C ***

Este projeto foi realizado com o intuito do aprendizado da ferramenta UIPath, uma poderosa ferramenta utilizada pela empresa T2C Consultoria.
Esta ferramenta permite criar robôs que podem automatizar processos repetitivos, trabalhosos e que demandam muito tempo dos funcionários. 
Para este projeto, o objetivo é buscar 100 cidades que possuam apenas um único CEP, coletar dados, e passá-los para uma planilha Excel.
Para melhor andamento do projeto, o mesmo foi dividido em 2 partes:

Na primeira, o robô utiliza o site de busca de CEPs dos correios, procurando assim cidades que possuam um único CEP. Uma forma de saber se o CEP é único é quando termina em 000.
Ao achar um CEP único, o robô passa o CEP e o nome da Cidade para uma planilha do Excel.

Na segunda parte, o robô pega os nomes das cidades coletadas na planilha e passa para o site do IBGE, onde coleta alguns dados solicitados pelo idealizador do exercício.
Estes dados são exportados para uma nova planilha, com todas as informações.

