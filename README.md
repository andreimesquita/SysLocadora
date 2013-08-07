SysLocadora
===========

REQUISÍTOS EM DESENVOLVIMENTO

SISTEMA

  Vídeo Locadora

EQUIPE

  Ândrei d'Oliveira Mesquita Schuch - andreirs@outlook.com

RESUMO

      Este sistema baseia-se em uma Vídeo Locadora que dispõe de serviços como locação e venda de filmes.

REQUISÍTOS

  FUNCIONAIS

    O software deve permitir que o gerente e os funcionários cadastrem os clientes.
    O software deve permitir que o gerente e os funcionários excluam os clientes.
    O software deve permitir que o gerente e os funcionários atualizem as informações de cadastro dos clientes.
    O software deve permitir a consulta de clientes.
    O software deve permitir que o gerente e os funcionários cadastrem filmes.
    O software deve permitir que o gerente e os funcionários excluam filmes.
    O software deve permitir que o gerente e os funcionários atualizem as informações de cadastro dos filmes.
    O software deve permitir a consulta de filmes.
    O software deve permitir que o cliente alugue filmes.
    O software deve permitir que o cliente compre filmes.
    O software deve permitir que o gerente cadastre os fornecedores.
    O software deve permitir que o gerente exclua os fornecedores.
    O software deve permitir que o gerente altere as informações de cadastro dos fornecedores.
    O software deve permitir que o gerente faça backup do banco de dados.
    O software deve permitir que seja realizado o backup do banco de dados retornando-o a uma versão anterior.
    O software deve permitir que o gerente visualize os arquivos de backup criados.
    O software deve permitir a consulta de fornecedores.
    O sistema deve gerar relatórios gráficos e escritos.
    O sistema deve gerar o relatório de lucros.
    O sistema deve gerar o relatório de vendas.
    O sistema deve gerar o relatório de despesas.
    O sistema deve gerar o relatório de locações.
    O software deve permitir a impressão de relatórios gerados.

  NÃO FUNCIONAIS 

    Os relatórios devem ser gerados por um determinado período de dias, meses ou anos, escolhidos pelo gerente.
    O programa deve ser feito em Java.
    O banco de dados utilizado deve ser o PostgreSQL.
    Os relatórios escritos devem ser criados no programa IReport.
    O software deve contar com serviço de autenticação por meio de usuário e senha.
    As senhas devem ser salvas usando de encriptação MD5.
    As plataformas de filmes disponíveis são: DVD e Blu-ray.
    Os filmes devem set classificados em 3 três categorias: 'Lançamento', 'Novo' e 'Antigo'.
    Os arquivos de backup criados devem ser salvos em uma pasta padrão do programa.
    O usuário deve poder escolher uma das cópias de backup criadas para restaurar o seu banco de dados.
    Não existe limitação em relação a quantos backups podem ser realizados.
    Se não for possível realizar a conexão com o banco de dados, deve ser possível continuar o trabalho
    em forma off-line criando arquivos (.xml).
    
  NEGÓCIO

    Os filmes classificados como 'lançamento' são aqueles que estão no mercado a 6 meses ou menos, e são representados 
    por uma faixa dourada, na capa filme.
    Os filmes classificados como 'novo' são aqueles que estão no mercado entre 6 meses e 2 anos, e são representados 
    por uma faixa prateada, na capa filme.
    Os filmes classificados como 'antigo' são aqueles que estão no mercado acima de 2 anos, e são representados 
    por uma faixa azul, na capa filme.
    O tempo máximo para locação dos filmes classificados como 'lançamento' é de 24 horas (1 dia).
    O tempo máximo para locação dos filmes classificados como 'novo' é de 72 horas (3 dias).
    O tempo máximo para locação dos filmes classificados como 'antigo' é de 120 horas (5 dias).
    Os filmes que não são entregues no prazo contam como uma nova locação.
    O sistema conta com um serviço de tele-entrega, funcional das 13 as 16 horas.
    Na primeira locação, o cliente poderá levar no máximo 3 (três) filmes.
