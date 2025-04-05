# resumo-do-lab
Este repositório contém o resumo das lições aprendidas durante o desenvolvimento do lab na DIO
Benefícios da alta disponibilidade e da escalabilidade na nuvem.
Benefícios da confiabilidade e da previsibilidade na nuvem.
Benefícios da segurança e da governança na nuvem.
Benefícios da capacidade de gerenciamento na nuvem.
Criar uma conta no Azure 
Definir computação em nuvem.
Definir modelos de nuvem, incluindo público, privado e híbrido.
Identificar os casos de uso apropriados para cada modelo de nuvem.
Descrever o modelo baseado no consumo.
Comparar os modelos de preços de nuvem
O que é a computação em nuvem?
Modelos de Computaçao 
NUvem Privada 
Nuvem Publica 
Nuvem Hibrida
comparaçao entre os modelo de Nuvem 
Comparar CapEx e OpEx
Despesas de capital (CapEx)
Despesas operacionais (OpEx)
Melhor previsão de custos.
São fornecidos preços para recursos e serviços individuais.
A cobrança é feita com base no seu uso real.

Após logar no Azure. 
. Crie um Servidor SQL
No menu de busca, digite e selecione “SQL Server”.

Clique em “+ Criar”.

Preencha:

Nome do servidor

Login e senha do administrador

Região (ex: Brazil South)

Clique em “Revisar + criar” e depois em “Criar”.

3. Crie um Banco de Dados SQL
No menu de busca, digite e selecione “SQL Database”.

Clique em “+ Criar”.

Preencha:

Nome do banco de dados

Grupo de recursos (ou crie um novo)

Selecione o servidor criado no passo anterior

Defina o plano de performance (DTU/vCore)

Clique em “Revisar + criar” e depois em “Criar”.

4. Configure o Firewall do Servidor
Após a criação, vá até o servidor SQL.

Clique em "Configurações de firewall".

Adicione o seu IP ou permita acesso de serviços do Azure.

Salve as configurações.

5. Conecte-se ao Banco de Dados
Use o SQL Server Management Studio (SSMS) ou outro cliente SQL.

Dados de conexão:

Nome do servidor (ex: nomeservidor.database.windows.net)

Usuário e senha definidos

Banco de dados especificado

6. Crie Tabelas e Insira Dados
Após conectar-se com sucesso, você pode:

Criar tabelas com comandos SQL

Inserir, consultar e manipular dados normalmente




