# Definição
O projeto consiste em uma sistema de gerenciamento de uma cantina, com foco no controle de vendas, estoque e relatório do local mas com muitas outras funcionalidades. 
Possui um controle de login para os Usuários da empresa para liberação de acesso de acordo com os Perfis do sistema, apresentando um conjunto de Menus personalizado vinculado com cada tipo Perfil cadastrado no sistema.
Todos os campos do sistema seguem os principios do (CRUD), porém, com o objetivo de manter o histórico da empresa sem desfalque, a opção de *deletar* foi alterado para *cancelar*, caso o usuário deseje fazer a manipulação.

## Entidades
Usuários:

Emição dos Relatorios:
A emissão de relatórios e feita com pacote de arquivos *itextpdf*, que cria um pdf com as informações do período selecionado pelo usúario, sendo elas:
- O id da venda
- O nome do vendedor (funcionário)
- O nome do Cliente
- O Valor Total da venda
