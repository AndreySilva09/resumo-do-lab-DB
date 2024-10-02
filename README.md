# resumo-do-lab-DB

IaaS, PaaS e SaaS no Azure
IaaS (Infrastructure as a Service): No Azure, o IaaS fornece infraestrutura em nuvem, como servidores, máquinas virtuais, redes e armazenamento. É ideal para empresas que querem gerenciar seus próprios servidores, sistemas operacionais e aplicativos, sem precisar se preocupar com hardware físico.

PaaS (Platform as a Service): O PaaS no Azure oferece um ambiente de desenvolvimento gerenciado. Ele inclui ferramentas para desenvolver, testar e implantar aplicativos, sem precisar gerenciar infraestrutura subjacente. É ideal para desenvolvedores que querem se concentrar apenas na criação de aplicativos.

SaaS (Software as a Service): O SaaS no Azure fornece softwares completos entregues pela internet, como o Office 365. Os usuários podem usar as aplicações sem se preocupar com a manutenção de servidores ou atualizações, pois tudo é gerenciado pela Microsoft.

Criação de um Banco de Dados SQL no Azure
Para criar um banco de dados SQL no Azure, você pode usar o Azure SQL Database, que é uma oferta PaaS. O processo envolve:

Criar um Servidor de Banco de Dados SQL: No portal do Azure, crie um servidor SQL especificando nome, localização e autenticação.
Criar um Banco de Dados: Selecione o servidor SQL e crie o banco de dados, escolhendo a camada de serviço (provisão de recursos).
Configurar Segurança e Rede: Defina regras de firewall para permitir conexões de IPs específicos e configure autenticação e permissões.
Conectar ao Banco de Dados: Use ferramentas como SQL Server Management Studio (SSMS) ou Azure Data Studio para gerenciar e consultar o banco.
O Azure SQL Database também oferece alta disponibilidade, recuperação de desastres e redimensionamento automático, facilitando o gerenciamento de cargas de trabalho em tempo real.
