
# Projeto Conceitual - Modelagem de um sistema para oficina

 Realização do desafio proposto pela instrutora Juliana da Digital Innovation One.  
 Foi feito a modelagem de um sistema de um sistema de controle e gerenciamento de execução de ordens de serviço em uma oficina mecânica.

 ### 

### Escopo do Projeto
Objetivo  
* Criar o esquema conceitual para o contexto de oficina com base na narrativa fornecida  
\
Narrativa
* Clientes levam veículos à oficina mecânica para serem consertados ou para passarem por revisões  periódicas
* Cada veículo é designado a uma equipe de mecânicos que identifica os serviços a serem executados e preenche uma OS com data de entrega.
* A partir da OS, calcula-se o valor de cada serviço, consultando-se uma tabela de referência de mão-de-obra
* O valor de cada peça também irá compor a OSO cliente autoriza a execução dos serviços
* A mesma equipe avalia e executa os serviços
* Os mecânicos possuem código, nome, endereço e especialidade
* Cada OS possui: n°, data de emissão, um valor, status e uma data para conclusão dos trabalhos.

### Desafio Realizado
Os principais pontos feitos para a criação do esquema conceitual do sistema para oficina foram:
* Criação de uma entidade "Veículo" para cadastro de diferentes carros por um único cliente;
* Criação de duas entidades "Orçamento" e "Ordem de serviço" para separação de serviços avaliados para aprovação e de serviços aprovados para execução;
* Criação de entidades para "Peça" e "Mão de obra" para listagem dos itens e valores para cálculo dos orçamentos.
