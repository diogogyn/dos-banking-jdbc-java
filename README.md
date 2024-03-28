# dos-banking-jdbc-java

Esta aplicação, chamada "DosbankApplication" tem o intuito realizar operações que faríamos em um banco, como cadastro e listagem de contas, bem como transferências de valores.
Esta aplicação conta(rá) com as opções:
- listas contas;
- abrir conta;
- encerrar conta;
- consultar saldo;
- realizar saque;
- realizar depósito;
  
Neste projeto, o objetivo será integrar uma aplicação com o banco de dados, e:
- Aprender a utilizar o Factory Pattern e as cláusulas de inserção do SQL para salvar dados no banco
- Entender como reaproveitar as conexões com o banco de dados usando um pool de conexões
- Compreender como fazer alterações em dados já existentes no banco, utilizando a cláusula UPDATE do SQL
- Saber usar a cláusula DELETE para apagar dados do banco, além de entender como realizar a exclusão lógica

Topicos que serão abordados para a construção desta aplicação:
- Conhecendo a aplicação
  - Projeto inicial
  - Configurando o conector (Instalação do MySQL e configuração do banco de dados)
    - Tratamento de erros: erro Access denied for user 'root'@'localhost' (using password: YES)
    - Exceção ao recuperar a conexão
  - Cadastro de Informações
  -   Isolando conexões com factory
      - Padrão factory
  - Preparando para salvar a conta (INSERT)
    - exceções checked e unchecked
    - Revisando padrão Factory;
    - Salvando contas no banco
    - Retorno do método execute()
    - O que é SQL Injection? Como prevenir?
    - Erros de compilação
    - Utilizando a classe DAO
  - Criando uma listagem (SELECT)
    - Preparando para listar contas
    - Listando contas do banco
      - Desafio: listando conta pelo número  
    - Fechando recursos com o banco
    - Escalabilidade de conexões
    - Diversos clientes
    - Pool com conexões ocupadas
  - Atualização de informações (UPDATE)
    - Depositando valor na conta
      - Desafio: sacando valor da conta
    - Arrumando os valores do saque
    - Ajustando o saldo zerado
    - Transferência entre contas
      - lidando com erros
  - Exclusão de informações (DELETE)
    - Excluindo contas
    - Comando delete
    - Exclusão lógica
      - Erro Parameter index out of range (6 > number of parameters, which is 5)
    - Realizando delete 




