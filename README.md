# criacao-db-sql-azure
Passo a passo simples para a criação de um banco de dados SQL na plataforma Microsoft Azure

1 -  Acesse o Portal do Azure:

Vá para portal.azure.com e faça login com sua conta.

2. Criar um Banco de Dados:

No menu à esquerda, clique em "Criar um recurso".

Pesquise por "Banco de Dados SQL do Azure" e selecione.

3. Configurar Detalhes do Banco de Dados:

Escolha a assinatura e um grupo de recursos (crie um novo ou use um existente).

Defina um nome para seu banco de dados.

Escolha se deseja um servidor novo ou um existente.

4. Configurar o Servidor:

Se estiver criando um novo servidor, defina nome do servidor, região e método de autenticação.

5. Escolher a Camada de Serviço:

O Azure oferece diferentes níveis de desempenho (como básico, standard, premium).

Escolha conforme a necessidade de escalabilidade e armazenamento.

6. Configurar Segurança e Acesso:

Configure o firewall para permitir conexões externas.

Defina regras para acesso via IP público ou VNET.

7. Revisar e Criar:

Revise todas as configurações e clique em "Criar".

Aguarde até que a implantação seja concluída.

8. Acessar o Banco de Dados:

Para se conectar ao banco, use SQL Server Management Studio (SSMS), Azure Data Studio ou uma aplicação compatível.

Utilize a string de conexão disponível na página do banco de dados.

9. Configurar Usuários e Permissões:

Crie usuários no SQL Server e defina permissões adequadas para segurança.
