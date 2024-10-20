# Criando Máquinas Virtuais no Microsoft Azure

## O que é uma Máquina Virtual (VM)?

Uma **Máquina Virtual (VM)** é uma instância de um ambiente de computação que simula o hardware de um computador físico. No Azure, as VMs permitem que você execute aplicativos e serviços sem a necessidade de gerenciar a infraestrutura física. As VMs são flexíveis e podem ser configuradas de acordo com as necessidades de processamento, armazenamento e rede de cada organização.

## Passos para Criar uma Máquina Virtual no Azure

### 1. Acessar o Portal do Azure
O primeiro passo para criar uma VM é acessar o [Portal do Azure](https://portal.azure.com). A partir do portal, você pode gerenciar todos os seus serviços e recursos na nuvem.

### 2. Iniciar o Processo de Criação
No menu principal do portal:
- Clique em **"Máquinas Virtuais"** e selecione **"Criar"**.
- Escolha a opção **"Máquina Virtual do Azure"**.

### 3. Configurações Básicas
Preencha os detalhes básicos da VM, como:

- **Assinatura**: Selecione a assinatura do Azure onde a VM será criada.
- **Grupo de Recursos**: Escolha ou crie um grupo de recursos, que será o container lógico para sua VM e outros recursos associados.
- **Nome da VM**: Dê um nome significativo à sua máquina virtual.
- **Região**: Escolha a região do data center do Azure mais próxima ou que melhor atenda às suas necessidades de desempenho e conformidade.
- **Imagem**: Selecione o sistema operacional que será usado na VM (ex: Windows Server, Ubuntu, etc.).
- **Tamanho da VM**: Defina a quantidade de CPU e RAM, de acordo com as necessidades da sua aplicação.

### 4. Configurações de Segurança
Nesta etapa, configure o acesso e a segurança da sua VM:

- **Autenticação**: Escolha entre autenticação por senha ou chave SSH para acessar a VM.
- **Rede Virtual**: Configure a rede virtual para conectar a VM com outros recursos e controle o tráfego de rede.
- **Grupos de Segurança de Rede (NSG)**: Defina regras de firewall para controlar o tráfego de entrada e saída da VM.

### 5. Configurações Avançadas (Opcional)
Você pode configurar outras opções, como:
- **Armazenamento**: Escolha o tipo de disco (gerenciado ou não) e o tipo de armazenamento (SSD ou HDD).
- **Monitoramento**: Habilite a opção de monitoramento de desempenho e diagnóstico de inicialização.

### 6. Revisar e Criar
Após preencher todas as configurações, clique em **"Revisar + Criar"**. O Azure fará uma validação das suas configurações. Se tudo estiver correto, clique em **"Criar"** para iniciar o processo de implantação da VM.

### 7. Acessando a Máquina Virtual
Depois que a VM for criada, você poderá acessá-la via:
- **RDP (para VMs Windows)**: Conecte-se à VM utilizando o Remote Desktop Protocol.
- **SSH (para VMs Linux)**: Conecte-se à VM Linux usando um cliente SSH e as credenciais criadas durante a configuração.

## Considerações de Custos
O custo de execução de uma VM no Azure depende de diversos fatores, como:
- Tamanho e tipo da VM.
- Tempo de uso (cobrança por hora).
- Tipo de disco e armazenamento utilizado.
- Tráfego de rede e outros recursos adicionais (como balanceadores de carga e IPs públicos).

O **Azure Pricing Calculator** pode ser usado para estimar os custos com base nas suas necessidades específicas.

## Gerenciamento de Máquinas Virtuais
Depois de criar a VM, você pode gerenciá-la no portal do Azure, onde é possível:
- Iniciar, parar, reiniciar ou excluir a VM.
- Monitorar o desempenho e usar alertas automáticos.
- Redimensionar a VM para ajustar as necessidades de processamento.

## Conclusão
Criar máquinas virtuais no Microsoft Azure é um processo simples e flexível, que oferece uma infraestrutura escalável para atender a diferentes tipos de aplicações e cargas de trabalho. Com a capacidade de ajustar os recursos conforme necessário e a segurança embutida, as VMs no Azure são uma solução poderosa para empresas de todos os tamanhos.

