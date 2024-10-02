# resumo-do-lab
Este repositório contém o resumo das lições aprendidas durante o desenvolvimento do lab na DIO

* Primeiro desafio
  
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

* Segundo desafio

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

* Terceiro desafio

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
