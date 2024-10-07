# resumo-do-lab
Este repositório contém o resumo das lições aprendidas durante o desenvolvimento do lab na DIO

###* Primeiro desafio
  
Principais serviços do Azure, organizados por categorias:

### Computação
- **Máquinas Virtuais (VMs)**
- **Azure Kubernetes Service (AKS)**
- **App Services**
- **Azure Functions**
- **Azure Batch**

### Rede
- **Virtual Network**
- **Azure DNS**
- **Load Balancer**
- **Application Gateway**
- **VPN Gateway**

### Armazenamento
- **Blob Storage**
- **File Storage**
- **Queue Storage**
- **Disk Storage**
- **Data Lake Storage**

### Banco de Dados
- **Azure SQL Database**
- **Cosmos DB**
- **Azure Database for MySQL**
- **Azure Database for PostgreSQL**
- **Azure Database for MariaDB**

### Inteligência Artificial e Machine Learning
- **Azure Machine Learning**
- **Cognitive Services**
- **Bot Service**
- **Azure OpenAI Service**

### Análise
- **Azure Synapse Analytics**
- **HDInsight**
- **Data Factory**
- **Stream Analytics**
- **Power BI Embedded**

### Segurança
- **Azure Security Center**
- **Azure DDoS Protection**
- **Key Vault**
- **Azure Information Protection**
- **Azure Sentinel**

### DevOps
- **Azure DevOps**
- **Azure Pipelines**
- **Azure Repos**
- **Azure Artifacts**
- **Azure Test Plans**

### Internet das Coisas (IoT)
- **IoT Hub**
- **IoT Central**
- **Azure Sphere**
- **Azure Digital Twins**
- **Time Series Insights**

### Ferramentas de Desenvolvimento
- **Visual Studio Code**
- **Azure SDKs**
- **Azure CLI**
- **Azure PowerShell**
- **Azure DevTest Labs**

###* Segundo desafio

Como criar uma máquina virtual no Azure via portal:

1. **Acesse o Portal do Azure**:
   - Vá para [portal.azure.com](https://portal.azure.com) e faça login com sua conta.

2. **Inicie a Criação da Máquina Virtual**:
   - No menu de navegação à esquerda, clique em "Máquinas Virtuais".
   - Clique em "Adicionar" e selecione "Máquina Virtual".

3. **Configurações Básicas**:
   - **Assinatura**: Selecione sua assinatura do Azure.
   - **Grupo de Recursos**: Escolha um grupo de recursos existente ou crie um novo.
   - **Nome da Máquina Virtual**: Insira um nome para sua VM.
   - **Região**: Escolha a região onde a VM será hospedada.
   - **Imagem**: Selecione o sistema operacional desejado (Windows ou Linux).
   - **Tamanho**: Escolha o tamanho da VM com base nas suas necessidades de desempenho e custo.

4. **Configurações de Administração**:
   - **Nome de Usuário**: Crie um nome de usuário para acessar a VM.
   - **Senha**: Defina uma senha segura.

5. **Discos**:
   - Escolha o tipo de disco (SSD ou HDD) e configure os discos adicionais, se necessário.

6. **Rede**:
   - Configure as opções de rede, como a rede virtual, sub-rede e IP público.

7. **Gerenciamento**:
   - Configure opções de monitoramento, backup e outras configurações avançadas.

8. **Revisar e Criar**:
   - Revise todas as configurações e clique em "Criar" para iniciar a implantação da VM.

9. **Acessar a Máquina Virtual**:
   - Após a implantação, vá para a página da VM e copie o endereço IP público.
   - Use uma ferramenta de conexão remota (como RDP para Windows ou SSH para Linux) para acessar a VM.

###* Terceiro desafio

Como configurar um instância de banco de dados no Azure.

Para configurar uma instância de banco de dados no Azure, você pode seguir os passos abaixo:

1. Acesse o Portal do Azure:

  - Vá para [portal.azure.com](https://portal.azure.com) e faça login com sua conta.

2. Crie um Banco de Dados SQL:

  - No menu à esquerda, selecione "SQL databases" e clique em "Add".

3. Configurações Básicas:

  - Escolha a assinatura e o grupo de recursos.

  - Dê um nome ao banco de dados.

  - Crie um novo servidor ou selecione um existente. Para um novo servidor, defina o nome, o usuário administrador e a senha.

4. Configurações de Escalabilidade:

  - Escolha a camada de preço que melhor se adapta às suas necessidades (por exemplo, Basic, Standard, Premium).

5. Configurações de Segurança:

  - Configure as regras de firewall para permitir o acesso ao banco de dados a partir do seu IP ou de uma faixa de IPs.

6. Revisão e Criação:

  - Revise todas as configurações e clique em "Create".

7. Conexão ao Banco de Dados:

  - Após a criação, você pode se conectar ao banco de dados usando ferramentas como SQL Server Management Studio (SSMS) ou Azure Data Studio.

###* Quarto desadio

Como e porque criar um grupo de recursos no azure:

1. Acesse o portal do Azure: Entre na sua conta do Azure e vá para o portal.

2. Selecione "Grupos de recursos": No menu à esquerda, clique em "Grupos de recursos".

3. Clique em "Criar": No topo da página, clique no botão "Criar".

4. Preencha os detalhes:

  - *Assinatura: Selecione a assinatura do Azure que você deseja usar.

  - Nome do grupo de recursos: Insira um nome para o grupo.

  - Região: Escolha a localização onde os metadados do grupo serão armazenados.

5. Revise e crie: Clique em "Revisar + Criar" e depois em "Criar" para finalizar.

Por que criar um grupo de recursos no Azure:

1. Organização: Agrupar recursos que compartilham o mesmo ciclo de vida facilita a gestão e a visualização de todos os componentes de uma solução específica.

2. Gerenciamento Simplificado: Permite implantar, atualizar e excluir recursos como um grupo, economizando tempo e reduzindo a complexidade.

3. Controle de Acesso: Facilita a aplicação de políticas de segurança e controle de acesso a todos os recursos dentro do grupo.

4. Monitoramento e Custos: Ajuda a monitorar o desempenho e os custos associados a um conjunto específico de recursos, permitindo uma gestão financeira mais eficaz.

###* Quinto desafio

Configurando Recursos e Dimensionamentos em Máquinas Virtuais na Azure

Configurar e dimensionar máquinas virtuais (VMs) no Azure envolve alguns passos importantes para garantir que os recursos atendam às suas necessidades de desempenho e custo. Aqui está um guia básico para te ajudar:

1. **Acessar o Portal do Azure**:
   - Faça login no [Portal do Azure](https://portal.azure.com) com suas credenciais.

2. **Criar uma Máquina Virtual**:
   - No painel, procure por "Máquinas Virtuais" ou clique em "Criar Recurso" e selecione "Máquina Virtual".
   - Escolha uma assinatura e um grupo de recursos existente ou crie um novo.
   - Defina o nome da VM e escolha a região mais próxima dos seus usuários para melhor performance.
   - Selecione o sistema operacional desejado (Windows ou Linux) e a imagem correspondente.
   - Defina as credenciais de login: para Windows, nome de usuário e senha; para Linux, utilize chaves SSH para uma conexão mais segura⁴.

3. **Configurar o Tamanho da Máquina Virtual**:
   - O tamanho da VM define a quantidade de CPU, memória e armazenamento temporário disponível.
   - Escolha o tamanho que melhor se ajuste à sua carga de trabalho:
     - **Tamanhos Gerais**: Adequado para aplicações comuns e balanceadas.
     - **Tamanhos Otimizados para Memória**: Ideal para bancos de dados e aplicações com alta demanda de RAM.
     - **Tamanhos Otimizados para Computação**: Recomendado para cargas que exigem alto poder de processamento⁴.

4. **Configurar o Armazenamento**:
   - Na aba de Discos, selecione o tipo de disco mais adequado para sua VM:
     - **SSD Premium**: Recomendado para aplicações de alta performance e ambientes de produção.
     - **SSD Padrão**: Um meio-termo, para cargas moderadas.
     - **HDD Padrão**: Ideal para cargas com baixo custo e menor exigência de desempenho⁴.

5. **Configurar a Rede**:
   - Associe a VM a uma Rede Virtual (VNet) existente ou crie uma nova.
   - Configure as opções de rede, como endereços IP, sub-redes e grupos de segurança⁴.
  
   
###* Sexto Desafio

Como criar uma conta de armazenamento no azure 

Para criar uma conta de armazenamento no Azure, você pode seguir estes passos:



1. Acesse o Portal do Azure: Entre no [portal do Azure](https://portal.azure.com/).

2. Selecione "Contas de armazenamento": No menu à esquerda, clique em "Contas de armazenamento". Se o menu não estiver visível, clique no ícone de menu para ativá-lo.

3. Clique em "Criar": Na página de contas de armazenamento, clique no botão "Criar".

4. Preencha os Detalhes:

  - Assinatura: Escolha a assinatura do Azure que você deseja usar.

  - Grupo de Recursos: Selecione um grupo de recursos existente ou crie um novo.

  - Nome da Conta de Armazenamento: Insira um nome único para a sua conta de armazenamento.

  - Região: Escolha a região onde deseja criar a conta.

  - Desempenho: Selecione entre "Standard" ou "Premium", dependendo das suas necessidades.

  - Redundância: Escolha o tipo de redundância (LRS, GRS, etc.).

5. Configurações Adicionais: Configure as opções adicionais conforme necessário, como rede, segurança e tags.

6. Revisar e Criar: Revise suas configurações e clique em "Criar" para finalizar a criação da conta.

###* Setimo Desafio

Como funciona a Identidade, Acesso e Segurança no AZURE.

No Azure, a gestão de identidade, acesso e segurança é fundamental para proteger recursos e dados. Aqui estão alguns dos principais componentes e funcionalidades:


1. Entra ID Antigo - (Azure Active Directory (Azure AD)): É o serviço de gerenciamento de identidade e diretório baseado em nuvem da Microsoft. Ele oferece:

  - Logon Único (SSO): Permite que os usuários acessem vários aplicativos com uma única autenticação.

  - Autenticação Multifator (MFA): Adiciona uma camada extra de segurança exigindo mais de uma forma de verificação.

  - Acesso Condicional: Define políticas baseadas em critérios como usuário, localização e dispositivo para determinar se o acesso deve ser permitido ou bloqueado.


2. Controle de Acesso Baseado em Função (RBAC): Permite gerenciar permissões de acesso aos recursos do Azure com base nas funções dos usuários dentro da organização.


3. Proteção de Identidade: Utiliza inteligência artificial para monitorar e responder a atividades suspeitas, ajudando a proteger contra ameaças de segurança.


4. Gerenciamento de Identidade Híbrida: Integra identidades locais com o Azure AD, permitindo uma gestão unificada de identidades em ambientes híbridos.


5. Privileged Identity Management (PIM): Gerencia, controla e monitora o acesso a recursos importantes, garantindo que apenas usuários autorizados tenham acesso a funções privilegiadas.


Esses recursos ajudam a garantir que apenas usuários autorizados possam acessar os recursos necessários, protegendo a infraestrutura e os dados da sua organização.

* O que é o entra ID no AZURE

O Microsoft Entra ID, anteriormente conhecido como Azure Active Directory (Azure AD), é um serviço de gerenciamento de identidades e acesso baseado em nuvem. Ele permite que funcionários, clientes e parceiros acessem aplicativos, dispositivos e dados de forma segura.


Aqui estão alguns dos principais recursos do Microsoft Entra ID:

- Autenticação forte e políticas de acesso adaptáveis: Protege o acesso a recursos e dados sem comprometer a experiência do usuário.

- Logon único (SSO): Simplifica o acesso a aplicativos em praticamente qualquer lugar com uma única autenticação.

- Gerenciamento de identidades unificado: Permite gerenciar todas as identidades e acessos a partir de um único lugar, seja na nuvem ou no local.


Se você já utiliza serviços como Microsoft 365, Office 365, Azure ou Dynamics CRM Online, você já está usando o Microsoft Entra ID para gerenciar suas identidades e acessos.

###* Oitavo Desafio

Como usar a calculadora de custo do azure para levar seu ambiente on-premises para nuvem


Migrar um ambiente on-premises para a nuvem pode ser uma decisão estratégica importante, e entender os custos associados é fundamental. Vamos explorar como usar a Calculadora de Preços do Azure para estimar os custos da sua migração.


1. Acessando a Calculadora de Preços do Azure:

  Existem duas maneiras de chegar à calculadora:

  - Você pode acessá-la diretamente através deste [link](https://azure.microsoft.com/pricing/calculator/).

  - Ou, visite o site do Azure e selecione o link da calculadora de preços em "Preço" no menu de navegação.


2. Entendendo a Calculadora de Preços:

  A página da calculadora de preços possui três seções principais:

  - Seletor de produtos: Aqui, você verá todos os serviços do Azure para os quais a calculadora pode estimar os custos. Você pode pesquisar serviços específicos, explorar categorias e ver detalhes dos produtos.

  - Estimativa e configuração do produto: Nesta área, você criará estimativas semelhantes a um carrinho de compras. Adicione os serviços que planeja usar e configure-os conforme necessário.

  - Resumo da estimativa: Abaixo da configuração do produto, você verá um resumo da sua estimativa de custos.


3. Criando uma estimativa:

  Como é sua primeira vez, você começará com uma estimativa vazia. Comece adicionando os serviços que deseja usar. Por exemplo, se você planeja usar máquinas virtuais, vá até a seção "Compute" e selecione "Virtual Machines". Lá, você pode configurar os detalhes das máquinas virtuais e adicionar à sua estimativa.


4. Calculadora de Custo Total de Propriedade (TCO):

  Além da Calculadora de Preços, considere também a Calculadora de TCO do Azure. Ela permite estimar as economias possíveis ao migrar suas cargas de trabalho de aplicativos para o Microsoft Azure. Basta fornecer uma breve descrição do seu ambiente local para obter um relatório instantâneo.


Lembre-se de que os preços mostrados na calculadora são exemplos e não refletem os preços reais. Explore e experimente diferentes cenários para obter uma estimativa mais precisa para sua migração para a nuvem.

###* Nono Desafio

Como funciona a linha de comando dentro do Azure

A Interface de Linha de Comando (CLI) do Azure é uma ferramenta poderosa que permite criar e gerenciar recursos no Microsoft Azure usando comandos de texto. Vamos dar uma olhada mais detalhada:

1. O que é a CLI do Azure?
   - A CLI do Azure é um conjunto de comandos que você pode usar para interagir com serviços e recursos do Azure diretamente da linha de comando.
   - Ela está disponível em várias plataformas, incluindo Windows, macOS e Linux.

2. Principais recursos e benefícios:
   - **Automatização: A CLI do Azure é excelente para automação de tarefas repetitivas. Você pode criar scripts e fluxos de trabalho para gerenciar recursos em escala.
   - Acesso rápido: Com a CLI, você pode executar comandos diretamente no terminal, sem precisar navegar pela interface gráfica do portal.
   - Flexibilidade: A CLI oferece uma ampla gama de comandos para criar, listar, atualizar e excluir recursos, além de gerenciar assinaturas e grupos de recursos.

3. Como começar:
   - **Instalação**: Você pode baixar e instalar a CLI do Azure em seu sistema operacional. Ela está disponível para Windows, macOS e Linux.
   - Autenticação: Após a instalação, você precisa se autenticar usando suas credenciais do Azure. Isso permite que a CLI acesse sua conta e execute comandos em seu nome.
   - **Comandos básicos**: Experimente comandos como `az login` para fazer login, `az group create` para criar um grupo de recursos e `az vm create` para criar uma máquina virtual.

4. Exemplo de uso:
   - Digamos que você queira criar uma máquina virtual no Azure. Você pode fazer isso usando a CLI com um comando como este:
     ```
     az vm create --resource-group MeuGrupoDeRecursos --name MinhaVM --image UbuntuLTS --admin-username meuusuario --admin-password minhasenha
     ```

5. Azure Cloud Shell:
   - Além da instalação local, você também pode usar o Azure Cloud Shell, que é uma experiência de linha de comando baseada no navegador. Ele está disponível no portal do Azure e é autenticado automaticamente em cada sessão.


###* Decimo Desafio 

Ferramentas de monitoramento do Azure

O **Azure** oferece várias ferramentas de monitoramento para ajudar você a obter visibilidade e insights sobre seus recursos na nuvem. Vou apresentar algumas delas:

1. **Azure Monitor**:
   - O **Azure Monitor** é uma ferramenta abrangente que permite observabilidade de ponta a ponta em seus aplicativos, infraestrutura e rede em ambientes híbridos e de nuvem.
   - Com o Azure Monitor, você pode coletar dados de várias fontes, incluindo aplicativos, contêineres, sistemas operacionais convidados, recursos do Azure e alterações de recursos.
   - Ele oferece recursos como alertas, métricas, logs e rastreamento de aplicativos para ajudar a solucionar problemas, otimizar recursos e garantir o desempenho ideal¹.

2. **Azure Log Analytics**:
   - O **Azure Log Analytics** é uma solução de gerenciamento de dados e análise de log que coleta, correlaciona e visualiza dados de várias fontes.
   - Ele permite que você consulte e analise logs de máquinas virtuais, contêineres, aplicativos e muito mais. Você pode criar painéis personalizados e definir alertas com base em consultas específicas.

3. **Azure Application Insights**:
   - O **Application Insights** é focado em monitoramento de aplicativos. Ele fornece insights detalhados sobre o desempenho e o comportamento de seus aplicativos.
   - Com o Application Insights, você pode rastrear solicitações, exceções, dependências e métricas personalizadas. Ele também oferece recursos de rastreamento de usuário e análise de funil.

4. **Azure Security Center**:
   - Embora não seja exclusivamente uma ferramenta de monitoramento, o **Azure Security Center** ajuda a monitorar a segurança de seus recursos.
   - Ele oferece recomendações de segurança, alertas de ameaças e insights sobre a postura de segurança de suas máquinas virtuais, bancos de dados e outros serviços.

5. **Outras ferramentas**:
   - Além das mencionadas acima, existem outras ferramentas de terceiros que podem ser integradas ao Azure para monitoramento, como o **SolarWinds Server & Application Monitor**, o **AppDynamics**, o **New Relic** e o **BMC TrueSight**³.
