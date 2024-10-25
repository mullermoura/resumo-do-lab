# # # Resumo-do-lab AZ900 - Microsoft Azure
Este repositório contém o resumo das lições aprendidas durante o desenvolvimento do lab na DIO.

# Aula 1: Introdução ao Azure

Nesta aula, aprendemos a acessar o portal do Microsoft Azure e exploramos suas principais funcionalidades. Além disso, configuramos a aparência do portal, alteramos idiomas e navegamos pelos serviços oferecidos pela plataforma.

Acesso ao Portal do Azure: Como realizar o login no portal, configurações de aparência (tema claro/escuro) e alteração de idiomas para facilitar o uso do portal.

Serviços por Categorias: Conhecemos as diferentes categorias de serviços oferecidos pelo Azure, com exemplos práticos:

Máquinas Virtuais (VM): Criação e gerenciamento de VMs. Exemplo: Azure Virtual Machines.

Redes: Configuração e gerenciamento de redes virtuais. Exemplo: Virtual Network (VNet).

Inteligência Artificial (IA): Serviços para criar modelos de machine learning e IA. Exemplo: Azure Cognitive Services.

Gateway: Configuração de gateways para redes híbridas. Exemplo: Application Gateway.

DNS: Gerenciamento de zonas e registros DNS. Exemplo: Azure DNS.

Armazenamento: Soluções de armazenamento em nuvem. Exemplo: Blob Storage e Disk Storage.


Importância da Computação em Nuvem: Discutimos o papel estratégico da computação em nuvem, suas vantagens e como ela está transformando a maneira como empresas e desenvolvedores criam e gerenciam soluções. Pilares abordados: escalabilidade, flexibilidade, redução de custos e alta disponibilidade.

# Aula 2: Benefícios da Nuvem Azure

Nesta aula, abordamos os principais benefícios oferecidos pela nuvem Azure, divididos em diferentes tópicos:

Escalabilidade e Elasticidade: Exploramos como o Azure permite que os recursos sejam escalados automaticamente com base na demanda, ajustando para cima ou para baixo conforme necessário.

Confiabilidade, Previsibilidade e Segurança: Discutimos como a nuvem Azure garante alta disponibilidade, segurança avançada e previsibilidade de desempenho através de seus SLAs e ferramentas integradas.

Governança e Gerenciabilidade: Abordamos como o Azure oferece ferramentas de governança para garantir conformidade, controle e gerenciamento eficiente de recursos na nuvem.


# Aula 3: Criação de Máquinas Virtuais no Azure

Criação de Máquinas Virtuais: Exploramos o processo de criação de máquinas virtuais no Azure, desde a escolha da imagem até as configurações de hardware e rede.

SLA e Níveis de Indisponibilidade: Discutimos o Acordo de Nível de Serviço (SLA) oferecido pelo Azure e como ele garante disponibilidade das máquinas virtuais, abordando os diferentes níveis de indisponibilidade e seus impactos no serviço.

Zonas de Disponibilidade: Entendemos como as Zonas de Disponibilidade afetam a resiliência das VMs e como podemos distribuir recursos para melhorar a redundância e alta disponibilidade.


# Aula 4: Tipos de Serviço de Nuvem na Azure

Nesta aula, aprendemos sobre os principais tipos de serviços de nuvem oferecidos pela Azure e como cada um deles se aplica em diferentes cenários:

IaaS, PaaS e SaaS na Azure: Discutimos os três modelos de serviço de nuvem, onde cada um oferece diferentes níveis de controle e responsabilidade para os usuários.

IaaS: Infraestrutura como Serviço, que oferece controle total sobre a infraestrutura de TI.

PaaS: Plataforma como Serviço, que fornece uma plataforma gerenciada para o desenvolvimento e implantação de aplicações.

SaaS: Software como Serviço, onde o Azure gerencia totalmente o aplicativo e a infraestrutura.


Modelo de Responsabilidade Compartilhada: Abordamos como a responsabilidade pela segurança e gerenciamento de dados e infraestrutura é dividida entre o cliente e a Microsoft Azure, dependendo do tipo de serviço (IaaS, PaaS ou SaaS).


# Aula 5: Arquitetura e serviços Azure

Nesta unidade, tivemos a oportunidade de explorar os datacenters da Microsoft a partir de um tour virtual, o que nos permitiu conhecer de forma mais interativa a infraestrutura física que sustenta a plataforma de nuvem Azure. Vimos como esses datacenters são altamente seguros, escaláveis e projetados para oferecer alta disponibilidade e redundância, com foco em inovação e sustentabilidade.

Além disso, realizamos um lab prático, no qual tivemos uma experiência hands-on ao criar e gerenciar recursos no Azure.

Exploramos os principais componentes e conceitos da arquitetura de nuvem do Azure:

Componentes de Arquitetura do Azure: Aprendemos que a arquitetura do Azure é composta por diversos elementos interconectados, como datacenters, regiões, zonas de disponibilidade, e redes globais. Esses componentes trabalham juntos para oferecer serviços robustos e de alta disponibilidade. Exploramos como as zonas de disponibilidade ajudam a garantir a continuidade dos serviços, e como os datacenters são distribuídos globalmente para oferecer resiliência e flexibilidade.

Entendendo Pares de Região e Grupos de Recursos: Um dos conceitos mais importantes que estudamos foi o de pares de região. Entendemos que cada região do Azure está emparelhada com outra em uma localização geográfica distante para garantir recuperação de desastres e alta disponibilidade. Isso garante que, se uma região sofrer uma interrupção, a outra pode assumir suas funções. Também exploramos a criação e a organização de grupos de recursos, que são usados para gerenciar e organizar os ativos relacionados de uma solução, como VMs, redes e bases de dados.

# Aula 6: Computação e Rede no Azure

Na última aula, exploramos as principais tecnologias de computação e rede oferecidas pelo Azure, com foco em como esses serviços podem ser usados para construir e gerenciar ambientes na nuvem de forma eficiente e escalável. Aqui estão os tópicos abordados:

- Serviços de Computação e Máquinas Virtuais do Azure: 
  Discutimos os serviços de computação do Azure, com destaque para as Máquinas Virtuais (VMs), que permitem rodar sistemas operacionais completos na nuvem. As VMs são essenciais para hospedar aplicativos, testar novos sistemas e expandir a capacidade computacional conforme necessário.

- Conjuntos de Disponibilidade de Máquinas Virtuais: 
  Aprendemos sobre os Conjuntos de Disponibilidade, que ajudam a proteger suas VMs contra falhas de hardware no datacenter. Eles garantem que as VMs estejam distribuídas em diferentes racks, evitando interrupções em caso de problemas físicos.

- Área de Trabalho Virtual e Contêineres no Azure: 
  Exploramos o Azure Virtual Desktop, uma solução que permite configurar desktops virtuais acessíveis de qualquer lugar. Também vimos como os contêineres ajudam a executar aplicações em ambientes isolados e portáteis, trazendo mais flexibilidade e escalabilidade.

- Azure Functions e Serviços de Aplicativo do Azure: 
  Falamos sobre o Azure Functions, que oferece uma abordagem serverless, permitindo executar código sob demanda sem precisar gerenciar servidores. Além disso, discutimos os App Services, que facilitam o desenvolvimento, hospedagem e escalabilidade de aplicativos web e APIs.

- Azure Kubernetes Service (AKS): 
  Por fim, discutimos o Azure Kubernetes Service (AKS), uma solução para gerenciar contêineres em grande escala. O AKS facilita a implantação e o gerenciamento de aplicações baseadas em Kubernetes, proporcionando automação, balanceamento de carga, atualizações contínuas e segurança para arquiteturas de microserviços.

Configurando Recursos e Dimensionamento de Máquinas Virtuais no Azure

Na parte prática, aprendemos a configurar e dimensionar máquinas virtuais no Azure. Aqui está um guia simples de como fizemos isso:

Criando uma Máquina Virtual no Azure

1. Acesse o portal do Azure.
2. No menu lateral, clique em Máquinas Virtuais e depois em Criar.
3. Preencha os campos principais, como Grupo de Recursos, Nome da VM e Região.
4. Escolha o sistema operacional (Linux, Windows, etc.) e selecione o Tamanho da VM. Existem diferentes opções dependendo do tipo de workload que você precisa, como:
   - Série B: Ideal para cargas de trabalho mais leves e intermitentes.
   - Série D: Balanceada para uso geral.
   - Série F: Para demandas intensivas de CPU.
5. Crie as credenciais de login (usuário e senha).

Configurando a Rede

1. Escolha ou crie uma Rede Virtual para conectar sua VM.
2. Defina as regras de segurança, como permitir acesso RDP (Windows) ou SSH (Linux).
3. Se precisar, configure um IP Público para acessar a máquina remotamente.

Dimensionando a Máquina Virtual

1. Com a VM criada, você pode ajustá-la conforme a necessidade. Basta acessar a VM e selecionar Redimensionar.
   - Para escalar verticalmente, você pode aumentar ou diminuir os recursos de CPU e memória da VM.
   - Para escalar horizontalmente, é possível criar várias instâncias da mesma VM para distribuir a carga e aumentar a disponibilidade.
2. Selecione o novo tamanho e aplique as alterações. O processo pode causar uma breve interrupção enquanto as mudanças são feitas.

Monitorando a Máquina Virtual

1. Acesse a aba Métricas para monitorar o desempenho da VM (uso de CPU, memória e rede).
2. Com base nesses dados, você pode ajustar os recursos para garantir um uso eficiente e otimizar custos.


# Aula 7: Armazenamento e Migração no Azure

Neste módulo, exploramos os principais serviços de armazenamento oferecidos pela plataforma Azure e suas funcionalidades. Discutimos as diversas opções de armazenamento, suas camadas e os diferentes tipos de redundância que garantem a segurança e a disponibilidade dos dados.

Serviços de Armazenamento do Azure:

- Azure Blob Storage: Otimizado para armazenar grandes quantidades de dados não estruturados, como texto e arquivos binários.
  Exemplo: Armazenar backups diários de uma aplicação web em blobs, garantindo recuperação rápida e eficiente.

- Azure Disk Storage: Fornece discos para máquinas virtuais e aplicativos, garantindo desempenho consistente para operações intensivas de leitura e gravação.
  Exemplo: Utilizar discos premium para melhorar o desempenho de uma base de dados SQL que demanda alta velocidade de leitura.

- Azure Files: Oferece compartilhamentos de arquivos de rede acessíveis via protocolo SMB (Server Message Block), permitindo a integração entre soluções locais e na nuvem.
  Exemplo: Compartilhar arquivos entre diferentes departamentos de uma empresa, acessando-os diretamente pela rede, sem a necessidade de mover dados entre servidores locais e a nuvem.


Redundância de Armazenamento:
Explicamos as diferentes opções de redundância que garantem alta disponibilidade e proteção de dados, como:

- LRS (Locally Redundant Storage): Armazena várias cópias dos dados dentro de um único datacenter.
  Exemplo: Armazenar registros de log de uma aplicação com alta frequência de gravação, mas que não requerem redundância geográfica.

- GRS (Geo-Redundant Storage): Replica os dados em regiões geograficamente distantes para maior resiliência em caso de desastres.
  Exemplo: Armazenar informações críticas de clientes em GRS para garantir recuperação mesmo em caso de falha total de um datacenter.


Ferramentas de Migração:
Exploramos várias opções para migração de dados, como:

- AzCopy: Um utilitário de linha de comando que permite copiar dados entre contas de armazenamento de forma rápida e eficiente.
  Exemplo: Migrar dados de backups de um servidor local para o Azure Blob Storage usando o AzCopy.

- Azure Data Box: Uma solução para migração de grandes volumes de dados (até 80 TB), usada quando há pouca ou nenhuma conectividade de rede disponível. Ele protege os dados durante o transporte físico.
  Exemplo: Utilizar o Azure Data Box para mover grandes quantidades de vídeos e imagens de um escritório remoto sem boa conexão com a internet.


Gerenciamento de Arquivos:

- Gerenciador de Armazenamento do Azure: Uma interface gráfica que facilita a navegação e o gerenciamento de arquivos, com compatibilidade para Windows, MacOS e Linux.
  Exemplo: Usar o Gerenciador de Armazenamento para organizar arquivos e verificar o status de contêineres no Azure Blob sem necessidade de usar a linha de comando.

- Sincronização de Arquivos do Azure: Sincroniza arquivos entre a nuvem e ambientes locais, permitindo manter os arquivos mais acessados localmente enquanto otimiza o armazenamento em nuvem.
  Exemplo: Sincronizar arquivos de projetos de engenharia entre servidores locais e o Azure, permitindo que engenheiros acessem rapidamente arquivos críticos enquanto mantêm backups na nuvem.

Este módulo também abordou as migrações para o Azure, incluindo o uso de ferramentas integradas que facilitam a avaliação e migração de dados de forma eficiente, garantindo conformidade e atendendo a necessidades regulatórias.

# Aula 8: Identidade, Acesso e Segurança no Azure

Neste módulo, discutimos os principais serviços de identidade, acesso e segurança no Azure, essenciais para proteger dados e recursos. Exploramos os conceitos fundamentais para garantir a segurança e controle de acesso na nuvem.

- Microsoft Entra ID: O serviço de gerenciamento de identidades baseado em nuvem do Azure, anteriormente conhecido como Azure Active Directory. Ele permite gerenciar identidades de usuários e controlar o acesso a recursos na nuvem, com suporte para autenticação de logon único (SSO), autenticação multifator (MFA) e gerenciamento de dispositivos.
  Exemplo: Usar o Microsoft Entra ID para autenticar funcionários que acessam recursos corporativos de forma segura, evitando a necessidade de gerenciar senhas locais.

- Microsoft Entra Domain Services: Fornece serviços de domínio na nuvem sem a necessidade de gerenciar controladores de domínio. Isso permite executar aplicativos legados que ainda dependem de autenticação baseada em domínio.
  Exemplo: Migrar um sistema de ERP legado para a nuvem enquanto mantém o controle de autenticação tradicional via domínio.

- Autenticação e Autorização: A autenticação identifica usuários ou serviços, solicitando credenciais para garantir o acesso legítimo, enquanto a autorização define o que esses usuários podem fazer após a autenticação.
  Exemplo: Um funcionário se autentica com credenciais corporativas (autenticação) e tem acesso apenas ao seu departamento específico de arquivos (autorização).

- Acesso Condicional: Uma ferramenta que permite aplicar políticas de acesso baseadas em sinais, como localização do IP, grupo de usuários, dispositivo e outros fatores de risco.
  Exemplo: Restringir o acesso de usuários a partir de localizações geográficas incomuns ou dispositivos desconhecidos.

- Controle de Acesso Baseado em Função (RBAC): Uma forma de gerenciar permissões granulares, concedendo aos usuários somente o nível de acesso necessário para realizar suas tarefas.
  Exemplo: Um desenvolvedor pode ter acesso completo a máquinas virtuais para desenvolvimento, mas acesso limitado a dados sensíveis de clientes.

- Modelo de Confiança Zero: Este conceito parte do princípio de que nenhuma identidade, dispositivo ou rede é confiável por padrão. Tudo deve ser verificado e autenticado a cada etapa, garantindo segurança contínua.
  Exemplo: A aplicação de políticas de Confiança Zero impede que usuários autenticados acessem recursos sem validação adicional.

- Microsoft Defender para Nuvem: Um serviço de monitoramento que fornece proteção contra ameaças em ambientes de nuvem e datacenters locais. Ele oferece recomendações de segurança, detecta e bloqueia malwares e outros ataques, e garante o controle de acesso com o just-in-time (JIT), que permite a liberação temporária de portas de rede.
  Exemplo: O Defender alerta sobre vulnerabilidades nas configurações de segurança e sugere correções automáticas para proteger os recursos da nuvem.


