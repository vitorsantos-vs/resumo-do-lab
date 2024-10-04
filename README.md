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


