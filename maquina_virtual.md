# Guia de Máquinas Virtuais no Microsoft Azure

As Máquinas Virtuais (VMs) no Microsoft Azure permitem que você crie e gerencie servidores virtuais na nuvem. Este guia fornece um passo a passo para criar, configurar e gerenciar VMs no Azure.

## Passo 1: Acessar o Azure Portal

1. **Abra o navegador**: Use seu navegador de internet preferido.
2. **Acesse o Azure Portal**: Vá para [Azure Portal](https://portal.azure.com).
3. **Faça login**: Entre com suas credenciais de conta da Microsoft/Azure.

## Passo 2: Criar uma Nova Máquina Virtual

1. **Navegar para VMs**: No painel esquerdo, clique em **"Máquinas Virtuais"**.
   - ![Máquinas Virtuais](https://docs.microsoft.com/en-us/azure/media/virtual-machines/windows/tutorial-create-vm/azure-portal-vm-icon.png)

2. **Adicionar Nova VM**: Clique em **"Adicionar"** e selecione **"Máquina virtual"**.
   - ![Adicionar VM](https://docs.microsoft.com/en-us/azure/media/virtual-machines/windows/tutorial-create-vm/add-vm-button.png)

## Passo 3: Configurar a Máquina Virtual

1. **Configurações Básicas**:
   - **Assinatura**: Selecione a assinatura do Azure.
   - **Grupo de Recursos**: Escolha um grupo de recursos existente ou crie um novo.
   - **Nome da VM**: Dê um nome à sua VM.
   - **Região**: Escolha a região onde a VM será criada.
   - **Imagem**: Selecione o sistema operacional (Windows, Linux, etc.).
   - **Tamanho**: Escolha o tamanho da VM (CPU, memória).
   - ![Configurações Básicas](https://docs.microsoft.com/en-us/azure/media/virtual-machines/windows/tutorial-create-vm/basic-settings.png)

2. **Configurações de Disco**:
   - **Disco do SO**: Selecione o tipo de disco (HDD/SSD).
   - **Discos de Dados**: Adicione discos adicionais conforme necessário.

3. **Configurações de Rede**:
   - **Rede Virtual**: Escolha ou crie uma rede virtual.
   - **Sub-rede**: Selecione uma sub-rede.
   - **IP Pública**: Configure o endereço IP público, se necessário.
   - **Grupo de Segurança de Rede**: Configure regras de firewall para controlar o tráfego de entrada e saída.

4. **Gerenciamento**:
   - Configure opções de monitoramento, diagnóstico e backup.

5. **Revisão e Criação**:
   - Revise todas as configurações.
   - Clique em **"Revisar + Criar"** e depois em **"Criar"** para provisionar a VM.

## Passo 4: Acessar a Máquina Virtual

1. **Painel de VMs**: Após a VM ser criada, navegue até o painel de VMs no Azure Portal.
2. **Selecionar VM**: Clique na VM que você criou para abrir seu painel de gerenciamento.
3. **Conectar**: Use o botão **"Conectar"** para acessar a VM. Dependendo do SO:
   - **Windows**: Use Remote Desktop (RDP).
   - **Linux**: Use SSH.

## Passo 5: Gerenciar a Máquina Virtual

1. **Iniciar/Parar/Redefinir**: No painel da VM, você pode iniciar, parar e redefinir a VM conforme necessário.
   - ![Gerenciamento de VM](https://docs.microsoft.com/en-us/azure/media/virtual-machines/windows/tutorial-manage-vm/overview.png)

2. **Redimensionar**: Se você precisar mudar o tamanho da VM, clique em **"Redimensionar"** e escolha uma nova configuração de tamanho.
   - ![Redimensionar VM](https://docs.microsoft.com/en-us/azure/media/virtual-machines/windows/tutorial-manage-vm/resize.png)

3. **Monitoramento**: Use o painel de monitoramento para visualizar métricas de desempenho, logs e alertas.

4. **Backup e Recuperação**: Configure políticas de backup e recuperação para garantir a integridade dos dados.

## Conclusão

Agora você sabe como criar, configurar e gerenciar Máquinas Virtuais no Microsoft Azure. As VMs oferecem uma solução flexível e escalável para diversas necessidades de computação na nuvem.

## Recursos Adicionais

- [Documentação do Azure sobre VMs](https://docs.microsoft.com/en-us/azure/virtual-machines/)
- [Azure Learn: Criação e Gerenciamento de VMs](https://learn.microsoft.com/en-us/training/paths/create-linux-virtual-machine-in-azure/)
- [Suporte do Azure](https://azure.microsoft.com/en-us/support/)

