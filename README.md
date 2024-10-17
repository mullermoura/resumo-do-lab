# resumo-do-lab
Este repositório contém o resumo das lições aprendidas durante o desenvolvimento do lab na DIO.

Aula 1: Introdução ao Azure

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

Aula 2: Benefícios da Nuvem Azure

Nesta aula, abordamos os principais benefícios oferecidos pela nuvem Azure, divididos em diferentes tópicos:

Escalabilidade e Elasticidade: Exploramos como o Azure permite que os recursos sejam escalados automaticamente com base na demanda, ajustando para cima ou para baixo conforme necessário.

Confiabilidade, Previsibilidade e Segurança: Discutimos como a nuvem Azure garante alta disponibilidade, segurança avançada e previsibilidade de desempenho através de seus SLAs e ferramentas integradas.

Governança e Gerenciabilidade: Abordamos como o Azure oferece ferramentas de governança para garantir conformidade, controle e gerenciamento eficiente de recursos na nuvem.


Aula 3: Criação de Máquinas Virtuais no Azure

Criação de Máquinas Virtuais: Exploramos o processo de criação de máquinas virtuais no Azure, desde a escolha da imagem até as configurações de hardware e rede.

SLA e Níveis de Indisponibilidade: Discutimos o Acordo de Nível de Serviço (SLA) oferecido pelo Azure e como ele garante disponibilidade das máquinas virtuais, abordando os diferentes níveis de indisponibilidade e seus impactos no serviço.

Zonas de Disponibilidade: Entendemos como as Zonas de Disponibilidade afetam a resiliência das VMs e como podemos distribuir recursos para melhorar a redundância e alta disponibilidade.

Com base na imagem, o tema da Aula 4 será "Tipos de Serviço de Nuvem na Azure". A aula inclui os seguintes tópicos:

1. IaaS, PaaS e SaaS na Azure: Aborda os três principais modelos de serviço de nuvem — Infraestrutura como Serviço (IaaS), Plataforma como Serviço (PaaS) e Software como Serviço (SaaS) — e como eles são implementados no Azure.


2. Modelo de Responsabilidade Compartilhada: Explica como o Azure e os usuários compartilham responsabilidades relacionadas à segurança, gerenciamento e manutenção de dados e serviços.

Aula 4: Tipos de Serviço de Nuvem na Azure

Nesta aula, aprendemos sobre os principais tipos de serviços de nuvem oferecidos pela Azure e como cada um deles se aplica em diferentes cenários:

IaaS, PaaS e SaaS na Azure: Discutimos os três modelos de serviço de nuvem, onde cada um oferece diferentes níveis de controle e responsabilidade para os usuários.

IaaS: Infraestrutura como Serviço, que oferece controle total sobre a infraestrutura de TI.

PaaS: Plataforma como Serviço, que fornece uma plataforma gerenciada para o desenvolvimento e implantação de aplicações.

SaaS: Software como Serviço, onde o Azure gerencia totalmente o aplicativo e a infraestrutura.


Modelo de Responsabilidade Compartilhada: Abordamos como a responsabilidade pela segurança e gerenciamento de dados e infraestrutura é dividida entre o cliente e a Microsoft Azure, dependendo do tipo de serviço (IaaS, PaaS ou SaaS).


Aula 5. Arquitetura e serviços Azure

Nesta unidade, tivemos a oportunidade de explorar os datacenters da Microsoft a partir de um tour virtual, o que nos permitiu conhecer de forma mais interativa a infraestrutura física que sustenta a plataforma de nuvem Azure. Vimos como esses datacenters são altamente seguros, escaláveis e projetados para oferecer alta disponibilidade e redundância, com foco em inovação e sustentabilidade.

Além disso, realizamos um lab prático, no qual tivemos uma experiência hands-on ao criar e gerenciar recursos no Azure.

Exploramos os principais componentes e conceitos da arquitetura de nuvem do Azure:

Componentes de Arquitetura do Azure: Aprendemos que a arquitetura do Azure é composta por diversos elementos interconectados, como datacenters, regiões, zonas de disponibilidade, e redes globais. Esses componentes trabalham juntos para oferecer serviços robustos e de alta disponibilidade. Exploramos como as zonas de disponibilidade ajudam a garantir a continuidade dos serviços, e como os datacenters são distribuídos globalmente para oferecer resiliência e flexibilidade.

Entendendo Pares de Região e Grupos de Recursos: Um dos conceitos mais importantes que estudamos foi o de pares de região. Entendemos que cada região do Azure está emparelhada com outra em uma localização geográfica distante para garantir recuperação de desastres e alta disponibilidade. Isso garante que, se uma região sofrer uma interrupção, a outra pode assumir suas funções. Também exploramos a criação e a organização de grupos de recursos, que são usados para gerenciar e organizar os ativos relacionados de uma solução, como VMs, redes e bases de dados.

Criação de Grupo de Recursos: MM_Azure_AZ: Durante o lab prático, criamos um grupo de recursos chamado MM_Azure_AZ, o que nos deu uma experiência prática em como os grupos de recursos são fundamentais para gerenciar, organizar e aplicar políticas a um conjunto de recursos interconectados no Azure. Esse grupo serviu como uma estrutura para organizar e centralizar os serviços e recursos, tornando a gestão mais eficiente e permitindo monitoramento mais fácil.

Criação de uma Rede Virtual: Dentro do grupo de recursos MM_Azure_AZ, também configuramos uma rede virtual (Virtual Network), que é essencial para permitir a comunicação segura entre os diferentes recursos e serviços no Azure. A rede virtual criada permite a interconexão de máquinas virtuais e outros recursos de rede de forma isolada e segura, simulando um ambiente de rede local dentro da nuvem.

Assinatura da Azure e Grupos de Gerenciamento: Discutimos como funcionam as assinaturas do Azure, que são a base para o uso e a cobrança dos serviços. Aprendemos como uma assinatura permite acesso a uma vasta gama de serviços, sendo essencial para rastrear o uso e os custos. Também estudamos os grupos de gerenciamento, que facilitam o controle de várias assinaturas de forma centralizada, permitindo que as organizações apliquem políticas e controles de acesso em várias camadas, organizando os recursos de maneira eficiente e segura em grande escala.
