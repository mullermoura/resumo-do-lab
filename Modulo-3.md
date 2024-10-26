
# Curso AZ-900: Conceitos Básicos do Microsoft Azure - Módulo 3

Este repositório contém os principais conteúdos abordados no módulo de **Gerenciamento e Governança** do curso **AZ-900**. O objetivo é fornecer uma compreensão sólida sobre conceitos essenciais para a gestão e governança no Microsoft Azure.

## Estrutura dos Conteúdos

### 1. Gerenciamento de Custos no Azure
- **Calculadora de Preços**: Ferramenta para estimar os custos dos produtos do Azure, configurável para diferentes produtos e regiões.
- **Calculadora de Custo Total de Propriedade (TCO)**: Auxilia na estimativa de economia ao migrar para o Azure, comparando infraestruturas locais com os custos de nuvem.
- **Orçamento e Alertas**: Possibilita definir limites de gastos e alertas de custo.
- **Recomendações de Custos**: Sugestões para otimização de despesas dentro do Azure.

### 2. Marcas
- **Organização de Recursos**: Uso de metadados para organizar recursos em uma taxonomia lógica.
- **Informações de Cobrança**: Facilitam a coleta de dados de cobrança por meio de um sistema de pares nome-valor.

### 3. Azure Marketplace
- **Exploração de Serviços e Aplicações**: Plataforma para pesquisa e aquisição de aplicativos e serviços de terceiros, certificados para execução no Azure.
- **Ferramentas e Softwares**: Disponibiliza mais de 10.000 itens, incluindo ferramentas de desenvolvimento, software de contêiner e máquinas virtuais.

### 4. Prática e Aplicação
- **Hands-On**: Exercícios práticos para consolidar o aprendizado de gerenciamento e governança dentro do ambiente Azure.




# Azure Resource Management

Este repositório contém informações sobre a gestão de recursos no Azure, abordando os conceitos de **Azure Policy**, **bloqueio de recursos**, **Azure Purview** e **Azure Managed Identity**.

## Azure Policy

O **Azure Policy** é um serviço que ajuda a impor regras e efeitos em recursos do Azure. Ele permite que as organizações governem seu ambiente de nuvem ao garantir que os recursos estejam em conformidade com as diretrizes corporativas. Com o Azure Policy, você pode:

- **Definir e aplicar políticas**: Crie políticas para restringir ou permitir ações específicas em recursos do Azure.
- **Auditar a conformidade**: Monitore recursos para garantir que eles atendam às diretrizes estabelecidas.
- **Ações automatizadas**: Aplique ações corretivas automaticamente quando um recurso não estiver em conformidade.

### Exemplos de Políticas

- Restringir a criação de recursos em regiões específicas.
- Garantir que todos os recursos tenham tags apropriadas.
- Impedir a utilização de tipos de recursos não permitidos.

## Bloqueio de Recursos

O **bloqueio de recursos** no Azure permite proteger recursos específicos de alterações acidentais ou exclusões. Existem dois tipos de bloqueios:

- **Não permitir exclusão**: Impede que um recurso seja excluído.
- **Não permitir alteração**: Impede que um recurso seja modificado.

### Como Configurar um Bloqueio

Você pode aplicar um bloqueio de recurso usando o **Azure Portal**, **CLI** ou **PowerShell**. Um bloqueio é definido no nível do recurso ou grupo de recursos e se aplica a todos os recursos contidos.


# AZ-900: Introdução aos Conceitos Básicos do Microsoft Azure

## Visão Geral

Este repositório contém materiais e recursos destinados ao estudo do módulo de **Gerenciamento e Governança** do curso AZ-900, que faz parte da certificação Microsoft Azure Fundamentals. O objetivo principal deste módulo é fornecer uma visão geral das ferramentas e serviços de gerenciamento oferecidos pelo Azure, incluindo a configuração, monitoramento e governança de recursos em um ambiente de nuvem.

## Conteúdos Abordados

### 1. Azure Resource Manager (ARM)
O **Azure Resource Manager (ARM)** é a camada de gerenciamento fundamental para o Azure, permitindo que usuários criem, atualizem e excluam recursos em uma assinatura do Azure. Os principais conceitos incluem:
- **Modelos ARM**: Arquivos JSON que facilitam a criação e a implantação de infraestrutura no Azure, promovendo consistência e escalabilidade.
- **Infraestrutura como Código**: Provisão de ambientes padronizados com configurações e builds reutilizáveis.
- **Vantagens**: Resultados repetíveis, orquestração modular e validação integrada, possibilitando uma gestão centralizada e eficiente.

### 2. Azure Arc
O **Azure Arc** expande o gerenciamento e governança do Azure para infraestruturas externas, incluindo ambientes locais e outras nuvens, permitindo:
- **Gerenciamento Consistente**: Aplicação de políticas e configurações em todos os recursos de forma uniforme.
- **Governança Multinuvem**: Controle e visibilidade aprimorados para cargas de trabalho híbridas.

### 3. Ferramentas de Implantação e Gerenciamento
No módulo, são abordadas várias ferramentas que facilitam a interação com os recursos do Azure:
- **Portal do Azure**: Interface gráfica para gerenciamento de recursos e serviços do Azure.
- **Azure PowerShell e CLI**: Ferramentas de linha de comando para automatizar e gerenciar recursos.
- **Azure Cloud Shell**: Shell interativo acessível diretamente do portal, integrando CLI e PowerShell.

### 4. Bicep
O **Bicep** é uma linguagem declarativa para a implementação de recursos no Azure, oferecendo uma sintaxe simplificada em relação aos modelos ARM JSON tradicionais, visando facilitar a criação de infraestrutura como código.


## Assistente do Azure

O **Assistente do Azure** é uma ferramenta que ajuda os usuários a gerenciar seus recursos na nuvem de maneira eficaz. Ele fornece recomendações personalizadas, sugestões de otimização e facilita a configuração e a monitorização de serviços. O Assistente é projetado para simplificar a gestão do ambiente do Azure, permitindo que os usuários aproveitem ao máximo suas implementações na nuvem.

## Integridade do Serviço do Azure

A **Integridade do Serviço do Azure** é um serviço que fornece informações sobre o status e a disponibilidade dos serviços do Azure. Ele permite que os usuários verifiquem se há interrupções, degradações de desempenho ou manutenção programada que possam afetar seus serviços. Com isso, os usuários podem monitorar a saúde dos serviços e tomar decisões informadas sobre suas aplicações e recursos.

## Azure Monitor

O **Azure Monitor** é uma solução abrangente de monitoramento que fornece uma visão unificada do desempenho e da integridade de seus aplicativos e recursos no Azure. Ele inclui várias ferramentas e funcionalidades, como:

- **Azure Log Analytics**: Permite coletar e analisar dados de logs e métricas em tempo real, ajudando a identificar problemas e otimizar o desempenho.

- **Alertas do Azure Monitor**: Ferramenta que permite configurar alertas baseados em métricas e logs, notificando os usuários sobre eventos críticos e anomalias no desempenho de seus serviços.

- **Application Insights**: Uma funcionalidade que fornece monitoramento de desempenho de aplicativos, permitindo que os desenvolvedores entendam como os usuários interagem com suas aplicações e identifiquem problemas de desempenho em tempo real.

